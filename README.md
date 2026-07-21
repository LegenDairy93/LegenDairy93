# Devaanga Prakash

### PRODUCT × SOFTWARE × AI

I turn promising ideas into working products.

I combine product thinking with hands-on software building—from finding the real problem to designing, shipping, and improving the solution.

[Portfolio](https://legendairy93.github.io) · [LinkedIn](https://www.linkedin.com/in/devaanga-prakash-0a8482196) · [Email](mailto:devaanga1234@gmail.com)

---

## Building now

### [PromptDiff](https://github.com/LegenDairy93/promptdiff)

**Behavioral version control and release governance for prompts and agents.**

Compare outputs, tool calls, and execution traces. Approve behavioral baselines and enforce release policy.

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

I studied Business Administration and learned software by building products. That path taught me to move between user problems, product decisions, and implementation—and to stay with an idea until it becomes a complete, usable product.

I am based in India and open to product, software, AI, developer tooling, and automation opportunities—including remote collaborations.

## Build with me

- Try PromptDiff and open an issue with a reproducible failure case.
- Contribute an adapter, assertion, example, policy, or documentation improvement.
- Reach out if you are building ambitious products or AI systems where reliability and auditability matter.

**Contact:** [devaanga1234@gmail.com](mailto:devaanga1234@gmail.com)