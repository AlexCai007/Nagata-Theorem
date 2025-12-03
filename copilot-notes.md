# Copilot Notes

Response style
- Terse mode by default (under 10s per patch)
- Action-oriented, minimal explanations
- Ask for time extension only if necessary; propose smaller sub-steps

Lean preferences
- Keep section-level variables for shared assumptions
- Use explicit local `haveI` when Away-localization API is needed
- Prefer small, local lemmas over broad refactors
- Tight `simp` calls (explicit lemma lists), avoid heavy tactics unless necessary

Workflow
- One or two errors per patch; stop after each fix
- Batch related edits into a single patch when possible
- If large changes needed, split into small, verifiable steps. If it is risky, ask me for permission and lay out the steps

Project continuity
- Apply these notes across new formalization projects in this account
- If conventions change, update this file at the project root
