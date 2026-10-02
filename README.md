## Chanbin Lim

MS CS @ USC (May 2027). I work on **LLM inference and AI infrastructure**:
serving systems, KV-cache movement, and the performance work that makes them fast.
Before grad school, 7 years of software engineering at Samsung and Continental.

**Open source: [vLLM](https://github.com/vllm-project/vllm)**

- [#57648](https://github.com/vllm-project/vllm/pull/57648) *(merged)*. Removed the `ray[default]` dependency from data-parallel placement-group setup, which broke elastic expert-parallel scale-up on Ray clusters without the dashboard.
- [#54483](https://github.com/vllm-project/vllm/pull/54483) *(merged)*. Coalesced NIXL host-buffer KV-cache copies across cache groups. Per-request copy latency 4.95ms to 1.27ms, device copy ops 96 to 16 at 6 KV-cache groups.

**Recently**

- **Amazon**, SDE intern (2026). Productionized prefill-decode disaggregation for LLM serving, and root-caused per-request KV-transfer variance down to the RDMA post stage.
- Second author on a paper evaluating how well LLMs reproduce community reactions to news, under review at **ICLR 2027**.

**Projects**: [EchoSlice](https://github.com/beenpow/echoslice), LLM-backed TED clip recommendation and spaced repetition.

[LinkedIn](https://www.linkedin.com/in/chanbin-lim/) · [chanbin.lim.cs@gmail.com](mailto:chanbin.lim.cs@gmail.com)
