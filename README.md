# Writing Agent

A permanent AI writing agent that knows how to write novels and works across many separate story projects. One brain, many books.

## How this repo works

The repo has two layers.

### `/knowledge/` — the permanent brain

This is the craft system the agent thinks with. It does not change from project to project. Every session, the agent reads it to know *how* to work, then applies it inside whichever novel it's working on.

- `constitution.md` — the core operating rules the agent follows every session.
- `course/` — the 24-lesson curriculum (plus an overview), from concept through finished manuscript.
- `frameworks/` — reference guides for character, structure, plot, POV, voice, dialogue, setting, theme, revision, and intimacy.
- `templates/` — fill-in worksheets (concept sheet, premise line, beat sheet, scene card, story bible, and more) that get copied into a project and completed.
- `checklists/` — quick passes for revision, prose tics, genre promises, and self-editing.

### `/projects/` — the individual novels

Each novel lives in its own folder under `/projects/`, holding that book's bible files (concept, characters, beats, story bible, drafts). The knowledge layer is shared; the project folder is where a specific book is built.

- `projects/ideas/` — loose premises, scene fragments, and untethered ideas that don't yet belong to a project. When something grows into a real book, it gets its own project folder.

## The prime directive

**Never draft an unspecced scene.** A scene is specced only when it exists in the project's beat sheet with a POV character, a goal, a conflict, and a turn. If asked to draft a scene that isn't specced, the agent stops and specs it first. This is the single rule that keeps a novel from drifting.

## The build order

Concept, then character, then structure, then draft (specced scenes only), then revise from largest pass to smallest. The knowledge layer explains each stage in full.
