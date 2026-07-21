# Devaanga Prakash

### Applied AI Builder

I build AI products people can inspect, test, and trust.

My current focus is **behavioral version control for AI agents**: making changes in outputs, tools, traces, and release behavior understandable before they reach production.

[Portfolio](https://legendairy93.github.io) · [LinkedIn](https://www.linkedin.com/in/devaanga-prakash-0a8482196) · [Email](mailto:devaanga1234@gmail.com)

---

## Building now

### [PromptDiff](https://github.com/LegenDairy93/promptdiff)

**Behavioral version control and release governance for prompts and agents.**

PromptDiff is a local-first TypeScript CLI that captures how an AI system behaved, compares it with an approved baseline, and gives teams a reviewable artifact for deciding what ships.

- Treats prompts and agents as different system types
- Captures outputs, ordered traces, tool calls, argument contracts, and violations
- Promotes accepted runs into named, integrity-checked behavioral baselines
- Records promotion history, reviewer intent, Git state, and CI provenance
- Produces self-contained HTML reports and configurable regression gates
- Keeps tool drift informational by default; explicit policy decides what blocks CI
- Protected by **72 tests** in the current v0.3 release

[Read the repository](https://github.com/LegenDairy93/promptdiff) · [See v0.3](https://github.com/LegenDairy93/promptdiff/blob/main/docs/release-0.3.0.md) · [Open an issue](https://github.com/LegenDairy93/promptdiff/issues)

`TypeScript` `Node.js` `JSON Schema` `Vitest` `GitHub Actions` `agent evaluation`

### Why it exists

Evaluation platforms answer questions such as “which prompt or model scores better?” PromptDiff owns the change-control loop around a release:

```text
capture behavior → compare candidate → review the path → approve a baseline → gate what ships next
```

The final answer is only one part of agent behavior. If two runs return identical text but use different tools, data, or execution paths, that difference should be visible—even when policy chooses not to block it.

---

## What I am building toward

- Policy-as-code for behavioral release decisions
- Deterministic replay and incident-to-regression workflows
- GitHub pull-request annotations and approval checks
- Adapters for common agent runtimes and OpenTelemetry traces
- A collaboration layer without sacrificing portable, local-first artifacts

## Background

I studied Business Administration and learned software by building products. That combination shapes how I work: start with the user and operating constraint, then build the smallest system that proves its value.

I am based in India and open to applied AI, AI product, developer tooling, agent infrastructure, and automation opportunities—including remote collaborations.

## Build with me

- Try PromptDiff and open an issue with a reproducible failure case.
- Contribute an adapter, assertion, example, policy, or documentation improvement.
- Reach out if you are building AI systems where reliability and auditability matter.

**Contact:** [devaanga1234@gmail.com](mailto:devaanga1234@gmail.com)