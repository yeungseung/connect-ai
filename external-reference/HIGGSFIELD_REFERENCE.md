# Higgsfield Skills Reference

This directory pins the upstream Higgsfield Skills repository as an external reference for architecture and workflow analysis.

- Upstream: https://github.com/higgsfield-ai/skills
- Pinned upstream commit: `d071406147a37b835bed09543d85ab3e9bd85c7d`
- Upstream branch at capture: `main`
- Captured on: 2026-09-17
- Local policy: keep upstream content unchanged; perform our analysis separately

The pinned revision is included as a Git submodule at `external-reference/higgsfield-skills`.

## Why it is stored

The repository is being reviewed for reusable patterns relevant to our own content-production system, including skill routing, workflow orchestration, checkpoints, model selection, failure recovery, asset/reference handling, context management, QA gates, and generation/inspection/edit loops.

## Important

Do not edit files inside the submodule when adapting ideas. Extract patterns into our own implementation or analysis documents instead.
