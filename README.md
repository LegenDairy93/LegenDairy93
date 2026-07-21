# Devaanga Prakash Oza

### Applied AI Builder

I build AI systems that people can inspect, test, and trust.

My work sits between product thinking and implementation: offline inference, evidence grounding, schema validation, agent traces, behavioral evaluation, and the interfaces that make those systems understandable.

[Portfolio](https://legendairy93.github.io) · [LinkedIn](https://www.linkedin.com/in/devaanga-prakash-0a8482196) · [Email](mailto:devaanga1234@gmail.com)

---

## Selected work

### [Discharge Navigator](https://github.com/LegenDairy93/discharge-navigator)

An offline, CPU-only system that turns unstructured clinical notes into evidence-grounded discharge packets using MedGemma 4B.

- Runs on a consumer laptop with no internet after model download
- Grounds every extracted claim to an exact span in the source note
- Evaluated on 50 clinical notes: **92% parse rate** and **87.5% overall grounding**
- Catches invalid output at the schema gate and keeps a clinician in control

[Try the demo](https://huggingface.co/spaces/haguman/discharge-navigator-demo) · [View the model card](https://huggingface.co/haguman/discharge-navigator-medgemma) · [Watch the walkthrough](https://youtu.be/GjRunxRwvak)

`Python` `MedGemma` `Ollama` `Pydantic` `Gradio` `edge AI` `evaluation`

### [PromptDiff](https://github.com/LegenDairy93/promptdiff)

A local-first TypeScript CLI for reviewing how prompts and agents change—not just whether their final text changed.

- Treats a prompt and an agent as different system types
- Captures ordered model, tool, and final-output traces
- Validates declared tools and tool arguments as contracts
- Produces small JSON artifacts and a self-contained HTML review report
- Keeps tool drift informational by default; explicit policies decide what blocks CI

Promptfoo is a broad evaluation and red-teaming platform. PromptDiff has a narrower job: make one before/after behavioral change easy to review in a pull request.

`TypeScript` `Node.js` `JSON Schema` `Vitest` `GitHub Actions` `agent evaluation`

---

## How I build

- **Ground first:** outputs should point back to evidence, inputs, and execution history.
- **Validate boundaries:** schemas and explicit contracts catch failures before downstream use.
- **Show the path:** for agents, the tool calls and intermediate steps matter as much as the answer.
- **Design for constraints:** offline, CPU-only, local-first, and human-reviewable are product choices.
- **Measure honestly:** publish evaluation results and failure cases, not just the best demo.

## Background

I studied Business Administration and learned software by building products. That combination shapes how I work: start with the user and the operating constraint, then build the smallest system that can prove its value.

I am based in India and open to applied AI, AI product, developer tooling, and automation opportunities—including remote collaborations.

## Build with me

- Try a project and open an issue with a reproducible failure case.
- Contribute an adapter, assertion, example, or documentation improvement to PromptDiff.
- Reach out if you are building AI systems where reliability, privacy, or auditability matters.

**Contact:** [devaanga1234@gmail.com](mailto:devaanga1234@gmail.com)