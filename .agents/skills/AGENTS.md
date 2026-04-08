# AGENTS.md

## Repository guidance

This repository uses qiushi-skill as its agent methodology layer.

## Instruction priority

1. User request
2. Host platform safety/system rules
3. This repository's AGENTS.md
4. Skills in `.agents/skills`

## Qiushi startup rule

At the start of each new top-level task, first read:

- `.agents/skills/arming-thought/SKILL.md`

Use it as the top-level methodology and routing constraint.

## Available qiushi skills

Load the following only when clearly useful for the task:

- `.agents/skills/contradiction-analysis/SKILL.md`
- `.agents/skills/practice-cognition/SKILL.md`
- `.agents/skills/investigation-first/SKILL.md`
- `.agents/skills/mass-line/SKILL.md`
- `.agents/skills/criticism-self-criticism/SKILL.md`
- `.agents/skills/protracted-strategy/SKILL.md`
- `.agents/skills/concentrate-forces/SKILL.md`
- `.agents/skills/spark-prairie-fire/SKILL.md`
- `.agents/skills/overall-planning/SKILL.md`
- `.agents/skills/workflows/SKILL.md`

## Expected behavior

- First inspect facts, then form judgments.
- Explicitly separate known facts, unknowns, and assumptions.
- Do not claim completion without verification.
- When blocked, investigate the cause and choose another path if needed.
- Do not mechanically invoke every skill unless the user explicitly requests broad multi-skill reasoning.

## Verification

Before declaring a coding task complete:

- run the relevant checks/tests if available
- summarize what was changed
- explain which qiushi skills were used and why
