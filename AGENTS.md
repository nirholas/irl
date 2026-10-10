# AGENTS.md

Instructions for AI coding agents working in or with `@three-ws/irl`.

## What this is

Geofenced, real-world presence for agents and avatars — check in at a GPS spot with a proof-of-presence fix, discover who's nearby, log real encounters, claim real-money drops, and complete agent-signed proof-of-presence quests. The three.ws IRL client.

## Use it

```bash
npm install @three-ws/irl
```

Full API reference: [README.md](README.md). Machine-readable summary: [llms.txt](llms.txt). Full text: [llms-full.txt](llms-full.txt).

## Work on it

- Node 20 or newer, ESM only.
- Run the tests with `npm test` before proposing a change.
- Keep runtime dependencies at their current count. Prefer a well-maintained library over new hand-rolled code, and say why in the pull request.
- No mocks, placeholders or TODO comments in committed code.
- Do not use em-dashes or en-dashes in code, comments or docs.

## Source of truth

This repository is exported from https://github.com/nirholas/three.ws/tree/main/packages/irl. Bug reports belong here; larger changes should be proposed against the monorepo path.
