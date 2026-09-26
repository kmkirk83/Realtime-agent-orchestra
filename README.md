# Realtime Agent Orchestra (RAO)

Codex/Claude-compatible skill for designing, scaffolding, and running realtime multi-agent systems.

## Install

Copy this folder into your agent skills directory:

```text
skills/realtime-agent-orchestra/
  SKILL.md
  references/
  assets/
```

Private mirror: `kmkirk83/codexskills`.

## Triggers

`start rao` · `/rao` · `/rao quick` · `daily overview` · `progress report` · voice / browser / multi-agent orchestration requests

## Modes

| Mode | When | What you get |
| --- | --- | --- |
| Normal | `start rao` | 4–6 ranked stacks with prompts, Docker, deploy, cost, security |
| Quickstart | `/rao quick` | Opinionated LangGraph + Pipecat + browser-use + FastAPI + Docker project |
| Full-repo | `expand` / `full repo` | Complete tree, zip, or GitHub push |
| Daily overview | `daily overview` / `progress report` | Stand-up: progress, blockers, pending decisions, next actions |

Default stack: LangGraph, CrewAI, Pipecat, browser-use, FastAPI, Docker → Modal / Railway / Fly.io.

The original upload archive remains at `realtime-agent-orchestra.zip`.
