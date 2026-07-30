# Agent Handoff — Live Baton

The single place that answers **"what is the live state, and whose turn is it?"** at the START of a
session. Claude, Codex and humans all read and write this file; per-agent memory is invisible across
agents, so the baton lives in the repo.

- **Live state, not history.** Narrative goes in `Journal.md`.
- **The protocol** is `~/.claude/HANDOFF.md`, included from both global agent configs. Read it once.
- **Rewrite "Current handoff" at every handoff.** Stale is worse than terse.

---

## Current handoff

⚠️ **STUB — no session has written this yet.** Created by `/init-project` on 2026-07-30, which wires
the repo but knows nothing about its live state. **Do not trust anything below until a real session
has rewritten it.** The first session to do work here should run `/handoff` or `/wrap`.

- **Last agent:** none
- **Updated:** never
- **Branch / HEAD:** run `git status --short` and `git log --oneline -1` — do not trust a stub for this
- **Working tree:** unknown
- **Validation:** never run
- **Whose turn:** whoever picks this up next

### What's left (priority order)

Unknown — no session has recorded anything.

### Do not touch / gotchas

Nothing recorded yet. Standing project gotchas live in `CLAUDE.md` / `AGENTS.md` under "Known issues".
