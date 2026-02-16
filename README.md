# Awesome Self-Evolving Systems [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of self-evolving ML systems that **autonomously improve their own models, algorithms, or training processes through closed feedback loops**.

## What is a Self-Evolving ML System?

A self-evolving ML system autonomously modifies and improves its own model or algorithm without human intervention in the loop. This requires:

1.  **Sensing:** Evaluating its own performance against goals or metrics.
2.  **Reasoning:** Identifying improvements, forming hypotheses, or generating candidate solutions.
3.  **Acting:** Autonomously modifying its own model, training data, reward function, or algorithm.

## Contents

- [Core Frameworks & Foundational Papers](#core-frameworks--foundational-papers)
- [Model & Algorithm Evolution](#model--algorithm-evolution)
- [Decision Pipeline & System Optimization](#decision-pipeline--system-optimization)
- [Self-Training & Self-Play](#self-training--self-play)
- [Surveys & Analysis](#surveys--analysis)
- [Contributing](#contributing)

## Core Frameworks & Foundational Papers

- **Self-Evolving Recommendation System** (Google, 2026) - A dual-loop, self-evolving system deployed at YouTube that uses LLM agents to autonomously generate, train, and deploy model changes. [[arXiv]](https://arxiv.org/abs/2602.10226)
- **Darwin Gödel Machine (DGM)** (Sakana AI, 2025) - A self-improving coding agent that rewrites its own code to improve performance, maintaining an expanding lineage of agent variants via Darwinian evolution and Gödel's self-reference principles. [[arXiv]](https://arxiv.org/abs/2505.22954) [[Website]](https://sakana.ai/dgm/)
- **Constitutional AI** (Anthropic, 2022) - A foundational method for training a model through self-improvement, using a set of principles to provide self-generated feedback and guide model behavior without human labels. [[arXiv]](https://arxiv.org/abs/2212.08073)
- **STaR: Bootstrapping Reasoning With Reasoning** (Zelikman et al., 2022) - A self-taught reasoning method where a model generates its own rationales, then uses them as training data to iteratively improve its own reasoning abilities. [[arXiv]](https://arxiv.org/abs/2203.14465)

## Model & Algorithm Evolution

- **AlphaEvolve: A Gemini-powered coding agent for designing advanced algorithms** (DeepMind, 2025) - An evolutionary coding agent that autonomously evolves and improves algorithms from a base seed, discovering novel solutions beyond human design. [[Blog]](https://deepmind.google/discover/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/)
- **SOAR: Self-Improving Language Models for Evolutionary Program Synthesis** (Pourcel et al., 2025) - Integrates LLMs into a self-improving evolutionary loop, alternating between evolutionary search and hindsight learning to fine-tune the LLM's own sampling and refinement capabilities. [[arXiv]](https://arxiv.org/abs/2507.14172) [[GitHub]](https://github.com/flowersteam/SOAR)
- **FunSearch: Making new discoveries in mathematical sciences using LLMs** (DeepMind, 2023) - An evolutionary method powered by an LLM that iteratively evolves and develops the highest-scoring programs to find novel solutions to mathematical problems. [[Nature]](https://www.nature.com/articles/s41586-023-06924-6)
- **SELF: Self-Evolution with Language Feedback** (Zhu et al., 2023) - An iterative self-evolution framework where an LLM acts as generator, evaluator, and analyzer to refine its own model through self-generated feedback cycles. [[arXiv]](https://arxiv.org/abs/2311.02302)
- **Eureka: Human-Level Reward Design via Coding Large Language Models** (Ma et al., 2023) - An algorithm that uses LLMs with evolutionary optimization to autonomously discover and evolve novel reward functions for complex RL tasks. [[GitHub]](https://github.com/eureka-research/Eureka)
- **Aletheia: Towards Autonomous Mathematics Research** (DeepMind, 2026) - A math research agent powered by Gemini Deep Think that iteratively generates, verifies, and revises candidate solutions in a closed loop, autonomously solving research-level problems including open conjectures. [[Blog]](https://deepmind.google/blog/accelerating-mathematical-and-scientific-discovery-with-gemini-deep-think/)

## Decision Pipeline & System Optimization

- **DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines** (Khattab et al., 2023) - A framework that self-optimizes entire ML pipelines end-to-end, automatically tuning the prompts and weights of each step against a defined metric. [[arXiv]](https://arxiv.org/abs/2310.03714) [[GitHub]](https://github.com/stanfordnlp/dspy)
- **QuantAgent: Seeking Holy Grail in Trading by Self-Improving Large Language Model** (Gao et al., 2024) - A self-improving LLM agent for quantitative trading that refines its own decision strategies through a closed feedback loop of market data and performance analysis. [[arXiv]](https://arxiv.org/abs/2405.10807)
- **QuantaAlpha: LLM-Driven Self-Evolving Framework for Factor Mining** (Han et al., 2026) - Combines LLM intelligence with evolutionary strategies to autonomously mine, evolve, and validate quantitative alpha factors through trajectory-based self-evolution. [[arXiv]](https://arxiv.org/abs/2602.07085) [[GitHub]](https://github.com/QuantaAlpha/QuantaAlpha)
- **TextGrad: Automatic "Differentiation" via Text** (Gao et al., 2024) - Propagates textual feedback through multi-component systems to iteratively optimize each piece, analogous to backpropagation for compound ML decision pipelines. [[arXiv]](https://arxiv.org/abs/2310.05628)
- **Reflexion: Language Agents with Verbal Reinforcement Learning** (Shinn et al., 2023) - A framework where agents reflect on failed decisions, store those reflections in memory, and use them to improve future decision-making in subsequent trials. [[arXiv]](https://arxiv.org/abs/2303.11366)
- **EvoFlow: Evolving Diverse Agentic Workflows On The Fly** (Chen et al., 2024) - Dynamically evolves multi-step decision workflows by composing and mutating agent modules, adapting the pipeline topology itself to new tasks. [[arXiv]](https://arxiv.org/abs/2406.03785)
- **Gödel Agent: A Self-Referential Framework for Agents Recursively Self-Improvement** (Hu et al., 2024) - A recursive self-improvement framework where a decision-making agent can rewrite its own logic and reasoning processes. [[arXiv]](https://arxiv.org/abs/2406.04235)
- **Self-Refine: Iterative Refinement with Self-Feedback** (Madaan et al., 2023) - An approach for iteratively refining decisions through self-generated feedback, improving output quality without additional training. [[arXiv]](https://arxiv.org/abs/2303.17651)

## Self-Training & Self-Play

- **Self-Play Fine-Tuning (SPIN)** (Chen et al., 2024) - A method that allows an LLM to improve itself by playing against its own previous versions, generating training data from self-play to iteratively refine its own policy. [[arXiv]](https://arxiv.org/abs/2401.01335)
- **Self-Rewarding Language Models** (Yuan et al., 2024) - Language models that generate their own training rewards via LLM-as-a-Judge, creating preference datasets to iteratively align and improve the model itself. [[arXiv]](https://arxiv.org/abs/2401.10020)

## Surveys & Analysis

- **A Survey on Self-Evolution of Large Language Models** (Tao et al., 2024) - A survey focused on self-evolution mechanisms within Large Language Models, proposing a conceptual framework and taxonomy. [[arXiv]](https://arxiv.org/abs/2404.14387)
- **A Survey of Self-Evolving Agents: On Path to Artificial Super Intelligence** (Gao et al., 2025) - A systematic review of self-evolving agents, organizing the field around what, when, and how agents evolve. [[arXiv]](https://arxiv.org/abs/2507.21046) [[GitHub]](https://github.com/CharlesQ9/Self-Evolving-Agents)
- **A Comprehensive Survey of Self-Evolving AI Agents** (Fang et al., 2025) - A unified conceptual framework for self-evolving agentic systems covering system inputs, agent systems, environments, and optimizers, with domain-specific evolution strategies for biomedicine, programming, and finance. [[arXiv]](https://arxiv.org/abs/2508.07407) [[GitHub]](https://github.com/EvoAgentX/Awesome-Self-Evolving-Agents)
- **The Devil Behind Moltbook: Anthropic Safety is Always Vanishing in Self-Evolving AI Societies** (Wang et al., 2026) - Proves a self-evolution trilemma: an isolated agent society cannot simultaneously achieve continuous self-evolution and safety invariance, establishing fundamental limits on self-evolving systems. [[arXiv]](https://arxiv.org/abs/2602.09877)
- **Introduction to Agents** (Google, 2025) - A whitepaper covering the foundational concepts of AI agents -- reasoning, tool use, and orchestration -- that underpin self-evolving system design. [[Kaggle]](https://www.kaggle.com/whitepaper-introduction-to-agents)

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a pull request. In short:

- The system must **autonomously evolve its own ML model or algorithm** -- not just prompts, memory, or agent workflows.
- Follow the existing format: `**Name** (Author/Org, Year) - One-sentence description. [[Link Type]](URL)`
- Add new entries to the **bottom** of the relevant section.
- One pull request per entry (or a small batch of closely related entries).

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
