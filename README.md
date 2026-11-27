## Hi, I’m ShaqG

I work on LLM serving on Ascend NPUs, focusing on MoE dispatch, expert-parallel communication, and prefill/decode execution.

**[Play Inference ER](https://shaqg.github.io/inference-er/)** · Four 60-second browser games about the trade-offs behind LLM serving. [Source code](https://github.com/ShaqG/inference-er)

## Open-source contributions

- [SGLang #46282](https://github.com/sgl-project/sglang/pull/46282) · Co-authored the Ascend Ops MoE backend. Implemented the MC2 low-latency decode path, including padding-buffer reuse and MXFP8 dispatch fixes.
- [SGLang #50691](https://github.com/sgl-project/sglang/pull/50691) · Co-authored fused MegaMoE for prefill and decode, including shared EP buffers, a CANN fallback for older `sgl-kernel-npu` builds, and W8A8 weight-loading improvements.

## Other projects

- [Contribution Canvas](https://github.com/ShaqG/contribution-canvas) · An offline editor for GitHub contribution graph art, with JSON export and a local Git history generator.
