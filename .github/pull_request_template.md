## ELI5

<!-- Required, always first. A few plain-language sentences the repository
owner understands without reading the diff: what problem, what changes for
them, what they need to do (if anything). Write in the repository's
documentation language. -->

## What changed

<!-- Before and after as the user experiences it, and the mechanism you
changed, not just the symptom. Concise; do not walk the diff. -->

## Why this approach

<!-- Alternatives considered and why this one. -->

Fixes #

## Testing

<!-- Commands run and their results. Tests check real behaviour, including
failure paths. State plainly what was NOT tested and why. -->

## Outside this repository

<!-- Changes to home-directory configuration, global git config, scheduled
tasks, other repositories: what, backup, rollback. Write "None" if none. -->

## Self-review

- [ ] One issue, one PR: no unrelated edits; review findings outside this PR's scope became new issues
- [ ] "How does this fail?": failure paths are reported, never silent
- [ ] Every call site of a fixed pattern was checked, not only the reported one
- [ ] No secrets or personal data in code, logs, state or this description
- [ ] The repository's own `AGENTS.md` / `CLAUDE.md` rules and path boundaries respected
- [ ] Docs updated where behaviour changed

Made by: <!-- agent and model, e.g. Claude Code (Opus 5.5), Codex (gpt-6.1-sol) -->
