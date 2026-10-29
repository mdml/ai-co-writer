# Working in this repository

Read `../ai-co-writer-context/context/README.md` and the relevant product and engineering notes there before making changes. They are in scope when the session is launched from the workspace directory one level up; if they are not available, stop and ask for them rather than inferring intent from this repository.

## Current phase

This repository is a scaffold awaiting human review. Do not infer authorization to build the application from the presence of proposed architecture or a task list in the context repository. Implementation begins when Max explicitly requests it.

## Authority

- Max owns product intent and prototype scope. Agents can propose options and explain tradeoffs.
- Keep decisions, proposals, and open questions distinct. Do not silently promote a proposal into a requirement.
- Editorial blockquotes in the context repository are prompts for Max. Preserve unanswered prompts unless asked to revise or remove them.
- Once implementation is authorized, make routine implementation choices within the reviewed scope. Ask when a consequential choice conflicts with or is not addressed by that scope.

## Changes and verification

- Keep changes scoped to the task. Do not rewrite unrelated material.
- Keep engineering notes in the context repository consistent with authorized decisions and implemented behavior.
- Soft-wrap prose: each paragraph and list item occupies one physical line.
- For bug fixes with a relevant test surface, first add a regression test, observe it fail, implement the fix, and observe it pass.
- Report which checks were actually performed; do not claim tests passed merely because a build succeeded.
- Keep private drafts, identifiable user feedback, credentials, and local authentication state out of this public repository.
