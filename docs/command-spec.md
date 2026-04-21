# vstack Command Specification Standard

## Purpose

This document defines how vstack commands should be described.

A command is not just a persona. A command is a repeatable production function that creates a useful artifact.

## Command design rule

Every command must define:

1. Role
2. Purpose
3. Inputs
4. Action
5. Output artifact
6. Acceptance criteria
7. Handoff target
8. Human decision points
9. Failure modes

## Standard command template

```markdown
# /command-name

## Role

The production role this command represents.

## Purpose

The specific production problem this command solves.

## Inputs

Required files or information.

## Action

What the command should do with the inputs.

## Output artifact

The file the command produces.

## Acceptance criteria

What must be true before the output is considered useful.

## Handoff target

The next command, stage, or human action.

## Human decision points

Decisions that must remain with the creator.

## Failure modes

Common ways this command can produce weak or misleading output.
```

## Quality rules

A vstack command should:

- produce a concrete markdown artifact
- ask only necessary clarification questions
- state assumptions clearly
- preserve creative intent
- avoid generic advice
- avoid pretending to see footage unless footage, transcript, or frame descriptions are provided
- separate recommendation from decision

## Naming convention

Command folders should use simple lowercase names:

```text
commands/
  ep/
  writer/
  director/
  dp/
  editor/
  thumbnail/
  distro/
  analytics/
```

Each command folder should eventually contain:

```text
SKILL.md
examples/
  input.md
  output.md
```

## Human-in-the-loop principle

Commands may recommend, structure, critique, and package.

Commands must not claim final creative authority.

The creator owns:

- concept approval
- performance
- recording
- final edit
- publishing decision
- brand judgment
- ethical judgment
