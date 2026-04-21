# vstack Roadmap

## Principle

Build the smallest thing that proves the workflow is useful.

Do not start with a complex CLI, prompt router, or automation layer.

## Phase 0 — Concept capture

### Goal

Define the idea clearly enough that a real pilot can be run.

### Deliverables

- README
- vision document
- v0.1 workflow
- command specification standard
- initial project template

### Exit criteria

A creator can understand what vstack is and how to test it manually.

## Phase 1 — Manual pilot

### Goal

Run vstack on one real educational video.

### Deliverables

- one complete pilot project folder
- generated artifacts for each stage
- creator notes on what helped and what did not

### Exit criteria

At least three stages clearly reduce friction or improve output quality.

## Phase 2 — Template refinement

### Goal

Turn the pilot into a repeatable documented workflow.

### Deliverables

- improved artifact templates
- refined stage definitions
- removal of redundant stages
- explicit examples of good outputs

### Exit criteria

A second video can be run faster and with less ambiguity.

## Phase 3 — Command packaging

### Goal

Represent the workflow as reusable command modules.

### Deliverables

- command directories
- `SKILL.md` files
- example inputs and outputs
- style and formatting rules

### Exit criteria

The workflow can be executed consistently through structured prompting.

## Phase 4 — Tooling evaluation

### Goal

Decide whether tooling is justified.

### Candidate options

- simple prompt library
- markdown generator
- repo bootstrap script
- slash-command wrapper
- lightweight CLI

### Exit criteria

Tooling is only added if it removes real friction discovered in earlier phases.

## Explicit non-goals for now

- full application UI
- automated video generation
- heavy plugin architecture
- multi-user platform features
- analytics ingestion system
- premature framework integrations
