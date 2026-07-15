# Max Hutchinson

**Applied AI Systems Architect**

I build AI-enabled systems, distributed platforms and integration-heavy
products. I care about what happens when the model is wrong, the queue backs up,
the connection disappears, or a person needs to overrule the machine.

My direct Applied AI work is recent. The engineering judgement behind it comes
from more than 12 years of building and leading software in regulated,
high-throughput and failure-prone environments.

[Website](https://maxlauriehutchinson.co.uk/) |
[Work](https://maxlauriehutchinson.co.uk/work/) |
[Writing](https://maxlauriehutchinson.co.uk/writing/) |
[LinkedIn](https://www.linkedin.com/in/maxlauriehutchinson)

## How I Build

- **Make state explicit.** If a workflow matters, I want to know what happened,
  which version made the decision and how to reconstruct it.
- **Treat recovery as product behaviour.** Retries, idempotency, backpressure,
  rollback and human handover belong in the design, not in a later runbook.
- **Keep hard boundaries around soft judgement.** Models can analyse and propose;
  code, policy and named people decide what is allowed to happen.
- **Use evidence to change direction.** Benchmarks, load tests, failure drills and
  real operating constraints beat architectural fashion.
- **Leave a system easier to own.** Good architecture should improve the next
  engineer's decisions, not make the original architect indispensable.

## What I Am Building

- [EvidenceGate](https://maxlauriehutchinson.co.uk/projects/evidence-gate/): a
  private proof of concept for engineering change assurance with deterministic
  checks, optional model findings and a named reviewer decision. It has no
  sponsoring organisation, external pilot or adoption claim.
- [Intention Engine](https://github.com/MaxLaurieHutchinson/Agent-autonomous-intention-engine):
  deterministic work discovery, risk routing and replay for agent workflows.
- [Marketing Automation System](https://github.com/MaxLaurieHutchinson/marketing-automation-system):
  visible orchestration, human feedback and staged automation for a workflow
  that non-technical owners can operate.

## Systems Evidence

- Deterministic ingestion and reconciliation across nine regulated data streams,
  including late corrective data and replayable lineage.
- Architecture across about 14 enterprise integrations, replacing a roughly
  30-day process with seconds-level digital flow.
- Edge-to-cloud telemetry for 153 multimodal signals at 30Hz per participant,
  designed to keep working through unreliable connectivity.

## Selected Code

- [Fintech Account Operations](https://github.com/MaxLaurieHutchinson/fintech-account-operations):
  explicit domain behaviour, transactional consistency and post-commit effects.
- [Quant Systems Lab](https://github.com/MaxLaurieHutchinson/quant-systems-lab):
  event-driven simulation, replay, risk controls and market-system experiments.
- [Agentic AI Skill Library](https://github.com/MaxLaurieHutchinson/skill-library):
  versioned, testable capability packaging for agent platforms.

## Current Questions

I am exploring how agent systems earn autonomy, how evaluation connects to live
operating decisions, and what replay should mean when part of the decision path
is probabilistic.

> The model proposes. The system defines what can happen.

[Read: The Control Plane for Applied AI Workflows](https://maxlauriehutchinson.co.uk/writing/applied-ai-control-plane/)
