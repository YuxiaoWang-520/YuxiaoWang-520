<h1 align="center">Hi, I'm Yuxiao Wang 👋</h1>

<p align="center">
  <b>AI Infrastructure Engineer @ Alibaba Group</b><br/>
  <i>Building agents that write the infra — so the infra can write itself.</i>
</p>

---

### 🔥 What I'm building

I work at the intersection of **AI agents** and **AI infrastructure** — pointing LLM agents at the
hardest, lowest-level parts of the stack and asking them to do my job (so far, so good).

- 🤖 **Kernel-generation agents** — LLM agents that auto-write and auto-tune GPU operators (算子)
  across **CUDA · Triton · CUTLASS**, compressing *"a senior engineer + two weeks"* into
  *"a prompt + a feedback loop."*
- 🏗️ **Agent harness architecture** — the scaffolding that makes coding agents actually reliable:
  context engineering, persistent memory, multi-agent orchestration, and long-horizon autonomous
  execution. → see **[harness-craft](https://github.com/YuxiaoWang-520/harness-craft)** ⭐

### 🧱 Built on deep infra

The agents are new; the foundation isn't. Day-to-day I live in large-scale LLM systems:

- **Training & inference at scale** — Megatron-LM · vLLM · SGLang · RTP-LLM
- **Distributed parallelism** — TP / PP / EP / DP, compute–comm overlap (DualPipe, EPLB)
- **GPU kernel optimization** — CUDA · Triton · CUTLASS / CuTe · FlashAttention
- **Cluster scheduling & orchestration** — Ray · Kubernetes (KubeDL / KubeRay)
- **Post-training / RLHF infra** — OpenRLHF · verl · ROLL

### 😎 Life goal

Become the richest person alive. Current roadmap:

1. Build an agent that writes GPU kernels. ✅ *(in progress)*
2. Build an agent harness so the agent does the rest of my job too.
3. `# TODO: figure out the part where this makes me rich`
4. **Profit.** 📈

Step 3 is under active research. Open to seed funding, spare H100s, and good ideas for step 3.

### 🚀 Featured

<a href="https://github.com/YuxiaoWang-520/harness-craft">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=YuxiaoWang-520&repo=harness-craft&theme=tokyonight&hide_border=true" alt="harness-craft" />
</a>

> **harness-craft** — a composable library of **skills & rules for AI coding agents**: repo memory,
> long-horizon execution, multi-agent coordination, TDD, security review, and delivery automation.

<sub>⚡ Fun fact: most of my commits live behind a corporate firewall, so this green-square garden looks suspiciously quiet. The kernels are real, I promise.</sub>
