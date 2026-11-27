## Hi there 👋

LLM inference on Ascend NPUs: MoE dispatch, expert parallelism, and the serving stack around them.

## Open-source contributions

- [SGLang #46282](https://github.com/sgl-project/sglang/pull/46282) · Co-authored the Ascend Ops backend for MoE prefill and decode. Merged into SGLang.
- [SGLang #50691](https://github.com/sgl-project/sglang/pull/50691) · Co-authored fused MegaMoE support for prefill and decode on Ascend NPUs. Added a CANN fallback for older `sgl-kernel-npu` builds, shared a symmetric buffer across prefill and decode, and improved W8A8 weight loading. Merged into SGLang.

## Open-source projects

- [Inference ER](https://github.com/ShaqG/inference-er) · 60-second browser games that put you on call in an LLM serving stack: request scheduling, and MoE expert triage with stragglers, expert rebalancing, and redundant experts. [Play online](https://shaqg.github.io/inference-er/?lang=en).
- [Contribution Canvas](https://github.com/ShaqG/contribution-canvas) · An offline editor for GitHub contribution graph art, with JSON export and a local Git history generator.

<!--
**ShaqG/ShaqG** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
