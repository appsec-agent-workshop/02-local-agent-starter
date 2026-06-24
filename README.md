# 02 - Local custom agent starter

Use this repository during the workshop section:
**Local custom agents**.

## Goal

Create a personal AppSec alert triage agent that helps an individual engineer or reviewer reason about Dependabot and CodeQL alerts.

## What is already scaffolded

```text
agents/appsec-alert-triage.agent.md
alerts/dependabot-sample.json
prompts/run-local-agent.md
```

## Exercise

1. Copy `agents/appsec-alert-triage.agent.md` to the local custom-agent path for your delivery environment.
2. Ask the agent to analyze `alerts/dependabot-sample.json`.
3. Tighten the agent prompt so it reflects your personal AppSec review preferences.

## Prompt

See `prompts/run-local-agent.md`.

## Done when

- The local agent separates facts from assumptions.
- The report lists missing evidence.
- The recommendation uses one approved route.
- Human approval remains required.
