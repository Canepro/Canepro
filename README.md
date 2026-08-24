# Vincent Mogah

I build agent systems for engineering and operations.

The model is one part. I work on how an agent gathers evidence, what it may
change, and how it proves the result.

## Agent systems

[codex-skills](https://github.com/Canepro/codex-skills) is a portable library of
engineering workflows for Codex, Claude Code, Cursor, and compatible agents. It
covers Kubernetes, GitOps, observability, CI investigation, and verification.

[PipelineHealer](https://github.com/Canepro/pipelinehealer) reads failed GitHub
Actions and Jenkins jobs. It opens a fix pull request only when policy permits
one. Otherwise, it files an issue with the failure evidence.

[SignalForge](https://github.com/Canepro/signalforge) collects infrastructure
snapshots and telemetry, ranks findings, and compares runs. It can explain
findings with an AI model, but it does not make infrastructure changes.

I use the same rule in each project. An agent should show the evidence behind
an action and stop when it cannot prove the next step.

## Platform work

- [Rocket.Chat on Kubernetes](https://github.com/Canepro/rocketchat-k8s) documents a monitored deployment with Prometheus and Grafana Cloud.
- [Central observability hub](https://github.com/Canepro/central-observability-hub-stack) collects metrics, logs, and traces across environments.

## Writing and contact

I write about failed builds, migrations, and deployment decisions on
[my portfolio](https://portfolio.canepro.me/).

[LinkedIn](https://www.linkedin.com/in/vincent-mogah/) ·
[Contact](https://portfolio.canepro.me/contact)
