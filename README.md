## Hi, I'm Wesley 👋

I'm passionate about **ML research** and the **engineering** that makes models work in practice.

- 🔬 ML research at the **[Mahmood Lab](https://faisal.ai/), Harvard Medical School**
- 🎓 MSc Data Science, **ETH Zurich** (2026)
- 🎓 BSc Computer Science, **EPFL** (2024)
- 💡 Interests: (Multimodal) foundation models, Computer Vision, LLMs, Representation Learning, Reinforcement Learning, AI engineering

### Projects

**[Learning to ask the right questions](https://github.com/WesLeeO/AEI)** — An LLM interviews a simulated patient one question per turn, then commits to an ICD-10 diagnosis. Trained with SFT, then multi-turn **PPO** (per-turn credit from a value head) and **GRPO** (per-rollout credit), rewarding correct diagnoses with as few questions as possible. *Semester project, LAS Lab, ETH Zurich.*

**[PaperGraph](https://github.com/WesLeeO/PaperGraph)** — Semantic search and a research agent over ~580k arXiv ML papers, fully local: hybrid retrieval with cross-encoder reranking, query understanding (authors, venues, years), and an agentic RAG loop on a local Qwen3 that may only cite papers it actually retrieved.

**[ETH AI Center chatbot](https://github.com/WesLeeO/dsl25-7-center-bot)** — Slack assistant for the ETH AI Center under the Swiss AI Initiative: RAG over Notion, Google Drive, Airtable, web pages and Slack history (ChromaDB + MiniLM embeddings), plus MCP tools giving Claude live access to Airtable and Slack. I restructured the codebase into a clean architecture and wrote the documentation. *Data Science Lab, ETH Zurich (2025), team project.*

**[GymRL](https://github.com/WesLeeO/GymRL)** — Q-learning, DQN, PPO and DDPG from scratch in PyTorch:
- **CartPole & Acrobot** — tabular Q-learning on CartPole; DQN and PPO solve both (DQN: 500/500 on CartPole)
- **Pendulum** — DDPG for continuous torque control
- **LunarLander** — DQN lands safely between the flags in 50/50 episodes
- **Atari Pong from raw pixels** — CNN-based DQN and PPO win every game, typically 21–1
