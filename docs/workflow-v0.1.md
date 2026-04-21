# vstack v0.1 Workflow

## Scope

vstack v0.1 is deliberately narrow.

It supports one workflow:

> A short educational video moving from idea to publish-ready package.

The workflow should be tested manually before any CLI, slash-command, or automation layer is added.

## Workflow overview

```text
/ep
  ↓
/writer
  ↓
/director
  ↓
/dp
  ↓
/editor
  ↓
/thumbnail
  ↓
/distro
  ↓
/analytics
```

## Stage 1: /ep — Executive Producer

### Purpose

Validate whether the video is worth making.

### Inputs

- rough idea
- intended audience
- desired outcome
- time constraint
- production constraint

### Output

`00_brief/greenlight.md`

### Acceptance criteria

The greenlight document must answer:

- What is the video about?
- Who is it for?
- Why should this be made now?
- What should the viewer understand or do afterwards?
- What is out of scope?

## Stage 2: /writer — Scriptwriter

### Purpose

Turn the approved idea into a usable script or structured outline.

### Inputs

- `greenlight.md`

### Output

`01_script/script.md`

### Acceptance criteria

The script must include:

- a clear opening hook
- one central idea
- plain spoken language
- optional A-roll / B-roll notes
- estimated runtime

## Stage 3: /director — Director

### Purpose

Translate the script into visual execution.

### Inputs

- `greenlight.md`
- `script.md`

### Output

`02_preproduction/shot-list.md`

### Acceptance criteria

The shot list must include:

- A-roll requirements
- B-roll suggestions
- visual beats
- transitions or structural changes
- pacing notes

## Stage 4: /dp — Cinematographer

### Purpose

Plan the camera, lighting, and visual setup.

### Inputs

- `shot-list.md`
- available location details
- available equipment

### Output

`02_preproduction/camera-lighting-plan.md`

### Acceptance criteria

The plan must include:

- camera placement
- framing
- lighting setup
- audio capture assumptions
- setup risks
- fallback option

## Stage 5: /editor — Editor

### Purpose

Guide the structure and pacing of the edit.

### Inputs

- `script.md`
- `shot-list.md`
- shoot notes or transcript

### Output

`04_post/edit-notes.md`

### Acceptance criteria

The edit notes must include:

- recommended structure
- cuts or trims
- pacing risks
- B-roll or graphic needs
- rough title-card or lower-third notes if needed

## Stage 6: /thumbnail — Thumbnail Designer

### Purpose

Create strong visual packaging options.

### Inputs

- `greenlight.md`
- `script.md`
- final title direction if available

### Output

`05_publish/thumbnail-concepts.md`

### Acceptance criteria

The thumbnail concepts must include:

- 3–5 thumbnail directions
- suggested image composition
- suggested overlay text
- visual hierarchy notes
- rationale for the strongest option

## Stage 7: /distro — Distribution Strategist

### Purpose

Prepare the publish package.

### Inputs

- `greenlight.md`
- `script.md`
- `thumbnail-concepts.md`

### Output

`05_publish/distribution-package.md`

### Acceptance criteria

The package must include:

- recommended title
- alternate titles
- description
- tags or keywords
- platform-specific notes
- short social post text

## Stage 8: /analytics — Analytics Lead

### Purpose

Capture learning after publication.

### Inputs

- performance data
- retention observations
- subjective creator notes

### Output

`06_review/post-mortem.md`

### Acceptance criteria

The post-mortem must include:

- what worked
- what underperformed
- likely reasons
- one change to test next time
- reusable learning for the next `/ep` stage

## v0.1 rule

If a stage does not produce a useful artifact, the stage should be simplified or removed.
