# Repository contributor instructions

## Before anything else

Get the shared context: run `git clone --depth 1 https://github.com/oyzuai/context ../context`,
or `git -C ../context pull --ff-only` if it exists. Read `CONSTITUTION.md` and
`INDEX.md` there, open the entries and skills your task touches, and print
`context commit <sha>`. Generic skills live in https://github.com/oyzuai/agent-workflows
under `skills/`; clone it the same way when a task needs one. This repo's rules below
add to the context; they never weaken the constitution's gates.

## Issue taxonomy

Before creating, splitting, transferring or reclassifying an issue in any
`oyzuai` repository, read and apply the shared
[`classify-issues` skill](https://github.com/oyzuai/agent-workflows/blob/main/skills/classify-issues/SKILL.md) and its bundled
[taxonomy catalog](https://github.com/oyzuai/agent-workflows/blob/main/skills/classify-issues/references/taxonomy.json).
Explicitly fetch these files with repository tools if the skill is not installed;
a link is not an automatic import. Apply exactly one `type:*` and one or two
`area:*` labels, with relevant optional ecosystem, surface, host and concern
labels. Leave priority unset without recorded triage. Preserve `agent:*` and
other workflow labels; read back the issue to verify classification. Keep the
vocabulary in the shared catalog rather than copying it into this repository.
This applies only to authorized issue work and grants no additional authority.
