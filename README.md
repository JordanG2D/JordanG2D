# Gen 2 Dynamics

**AI agents that do accountable work.**

Nexus is a control layer for AI agents that act inside real systems. A person authorizes the work, the agent executes inside that authorization, and Nexus keeps one record of the whole task: request, approval, execution, evidence and decision.

Built by Joshua Jordan, Army veteran and solo technical founder.

**Website:** [gen2dynamics.com](https://gen2dynamics.com) · [Nexus](https://gen2dynamics.com/nexus.html)

## What has been demonstrated

- **A governed external-tool workflow (17 Oct 2026).** On a founder-signed, one-use grant, Nexus ran two completed QuantConnect backtests inside a fixed request budget (13 of 37 provider requests used). It produced a ten-file, hash-verified evidence packet, and the record was rebuilt identically with zero provider calls. Reviewed by an independent adversarial AI reviewer, not a human audit.
- **A live authenticated connection (1 Nov 2026).** The modular V3 rebuild accepted a real ChatGPT and Auth0 sign-in, passed its initial checks and completed an authenticated read.
- **Internal use.** Nexus is in use inside the author's own lab, queuing, dispatching and reporting AI-assisted engineering work under written rules for scope, authority, escalation and independent review. A ChatGPT-driven loop was proven in June 2026.

## What is not claimed

No customers or revenue yet. The QuantConnect run was attended and says nothing about trading performance. V3 is a development deployment: running real tools through the live connection, crash and reboot recovery and key rotation are still being qualified. It is not production-ready.

## Open source

- [soc-triage-evals](https://github.com/JordanG2D/soc-triage-evals): reproducible offline Inspect AI evaluation of SOC triage on synthetic alerts, with preserved evidence from live model runs. MIT.
- [durable-policy-workflow](https://github.com/JordanG2D/durable-policy-workflow): a TypeScript insurance workflow implemented by hand and with Temporal, with shared crash and retry tests. The AWS demo covers only the hand-built version. MIT.
- [livekit-durable-handoff](https://github.com/JordanG2D/livekit-durable-handoff): a LiveKit and Temporal example that follows up by SMS after a session ends, with a local demo and simulated SMS gateway. MIT.
- [g2d-discord-forge](https://github.com/JordanG2D/g2d-discord-forge): applies a Discord server template to an existing server without deleting what is already there. MIT.

## Contact

info@gen2dynamics.com

The Nexus code is private. An evidence packet and architecture walkthrough are available on request.
