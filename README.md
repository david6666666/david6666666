<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=24&amp;duration=3000&amp;pause=800&amp;color=2F81F7&amp;center=true&amp;vCenter=true&amp;width=620&amp;lines=Building+efficient+multimodal+inference;Text+%C2%B7+Image+%C2%B7+Audio+%C2%B7+Video;Profile+the+bottleneck.+Verify+the+gain." alt="Building efficient multimodal inference — text, image, audio and video" />

**WeiQing Chen** · **vLLM-Omni Committer** · 专注多模态与大模型推理：模型接入、分布式服务、GPU/NPU 性能优化，以及可复现的基准与质量验证。

</div>

## 🔭 Focus

- **多模态推理**：在 vLLM-Omni 中接入与优化图像、音频、视频等模型，打通模型加载与推理服务
- **性能优化**：从 profiling 定位瓶颈，优化 GPU kernel、通信与执行流程，同时验证输出质量
- **分布式服务**：关注专家并行负载均衡、异步专家重排，以及多模态投机解码
- **Agent 辅助优化**：通过 InferRSI 组织基准对比、质量检查与实验记录，让优化过程可追溯、经验可复用

## 🧩 Featured Projects

| 项目 | 说明 | 技术 |
| --- | --- | --- |
| [vLLM-Omni](https://github.com/vllm-project/vllm-omni) | Committer；面向文本、图像、音频与视频模型的高效推理框架，参与模型接入、性能优化与质量修复 | PyTorch · Diffusion · GPU/NPU |
| [InferRSI](https://github.com/InferMatrixLab/InferRSI) | 参与构建面向 coding agent 的推理优化工作台：组织受控基准对比、质量检查、实验报告与可复用调优知识 | Python · Benchmarking · Agent Skills |
| [AgentInfer](https://github.com/openJiuwen-ai/agent-infer) | 面向 Agent 工作负载的路由、调度与缓存框架；参与 InferRSI 源码集成 | vLLM · KV Cache · Agent Workloads |

## 🌱 Open Source

vLLM-Omni Committer，参与 vLLM 与 AgentInfer 开源协作。部分已合并贡献：

- **[vLLM-Omni #8739](https://github.com/vllm-project/vllm-omni/pull/8739)** — 优化 Qwen-Image-2.1-Turbo 在 NVIDIA B300 上的 BF16 推理；[实验与复现记录](https://github.com/InferMatrixLab/InferRSI/blob/main/docs/qwen-image-2.1-turbo-b300.md)
- **[vLLM-Omni #7610](https://github.com/vllm-project/vllm-omni/pull/7610)** — 支持直接加载 FastH3 8-Step V2 checkpoint
- **[vLLM #22179](https://github.com/vllm-project/vllm/pull/22179)** — 优化 EPLB 的异步专家重排
- **[vLLM #22872](https://github.com/vllm-project/vllm/pull/22872)** — 为 Qwen2.5-VL 接入 EAGLE / EAGLE3 多模态投机解码
- **[AgentInfer #51](https://github.com/openJiuwen-ai/agent-infer/pull/51)** — 集成完整 InferRSI 源码与工作台

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,kubernetes,git,linux&amp;perline=12" alt="Python, PyTorch, Kubernetes, Git, Linux" />
</p>

**Inference**：vLLM · vLLM-Omni · PyTorch　**Infrastructure**：CUDA · Ascend NPU · Ray · Kubernetes

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/david6666666/david6666666/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/david6666666/david6666666/output/github-snake.svg" alt="Animated snake tracing david6666666's GitHub contributions" />
</picture>
