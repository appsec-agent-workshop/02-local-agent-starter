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

If you know the local custom-agent path for your tool, copy `agents/appsec-alert-triage.agent.md` there. If you do not know the path or your environment does not support local custom-agent installation, skip installation and paste `prompts/run-local-agent.md` into Copilot with `agents/appsec-alert-triage.agent.md` open as context.

1. Load the agent by installation or by the fallback above.
2. Ask it to analyze `alerts/dependabot-sample.json`.
3. Tighten the agent prompt so it reflects your personal AppSec review preferences.

## Prompt

See `prompts/run-local-agent.md`.

## Done when

- The local agent separates facts from assumptions.
- The report lists missing evidence.
- The recommendation uses one route: `fix-now`, `campaign-candidate`, `needs-reachability-analysis`, `needs-codeql-timeout-investigation`, or `human-escalation`.
- Human approval remains required.
