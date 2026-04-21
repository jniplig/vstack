# vstack

**vstack** is an AI-assisted video production framework for solo creators and small teams.

It adapts the idea of a structured AI specialist workflow to video production. Instead of using one generic chatbot for every production task, vstack defines clear production roles, handoff artifacts, and repeatable workflows.

## Working definition

vstack is a repo-based production operating system for educational and creator video.

It helps a creator move from:

```text
Idea → Greenlight → Script → Shot Plan → Shoot → Edit Notes → Publish Package → Review
```

The framework does not replace the human creator. It reduces planning friction, improves production discipline, and preserves reusable production knowledge.

## Current status

This repository is at concept-capture stage.

The current priority is to document the minimum viable workflow before building tooling.

## Initial scope

vstack v0.1 focuses on short educational videos, especially:

- vocabulary and etymology videos
- explainer videos
- product-building updates
- InsightEdu / Lexicon content
- short-form educational clips

## Core principle

AI plans, structures, critiques, and packages.

The human creator records, performs, selects, approves, edits, and publishes.

## Repository structure

```text
README.md
LICENSE
docs/
  vision.md
  workflow-v0.1.md
  command-spec.md
  roadmap.md
templates/
  video-project/
    README.md
    00_brief/
    01_script/
    02_preproduction/
    03_production/
    04_post/
    05_publish/
    06_review/
```

## Near-term build strategy

1. Capture the concept clearly.
2. Define the minimum viable workflow.
3. Create reusable markdown templates.
4. Test the workflow on one real pilot video.
5. Only then consider CLI tooling, slash-command integrations, or automation.

## License

License not yet selected.
