---
name: analysis-router
description: Route Codex work to the right specialist by inspecting task scope, repo context, and risk. Use when a request is ambiguous, spans multiple areas, or needs a first-pass technical classification before implementation.
---

# Analysis Router

- Read the request and identify the primary task type.
- Check the real repository context before choosing a path.
- Prefer one specialist unless the task clearly needs a sequence.
- Flag missing evidence instead of guessing.
- Return the routing decision and the reason for it.
