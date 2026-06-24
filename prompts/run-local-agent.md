# Run the local agent

Use this prompt after installing or selecting the local `appsec-alert-triage` agent.

```text
Use the appsec-alert-triage agent to analyze alerts/dependabot-sample.json.

Produce a recommendation for a human AppSec reviewer.

Requirements:
- separate facts from assumptions
- list missing evidence
- choose one route: fix-now, campaign-candidate, needs-reachability-analysis, needs-codeql-timeout-investigation, or human-escalation
- do not propose automatic dismissal, severity reduction, or risk acceptance
```
