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
- **Self-Taught Optimizer (STOP): Recursively Self-Improving Code Generation** (Zelikman et al., 2023) - A scaffolding program that uses a language model to improve its own improver code against a utility function, discovering better search strategies while leaving the underlying model weights unchanged. [[arXiv]](https://arxiv.org/abs/2310.02304)

## Model & Algorithm Evolution

- **AlphaEvolve: A Gemini-powered coding agent for designing advanced algorithms** (DeepMind, 2025) - An evolutionary coding agent that autonomously evolves and improves algorithms from a base seed, discovering novel solutions beyond human design. [[arXiv]](https://arxiv.org/abs/2506.13131) [[Blog]](https://deepmind.google/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/)
- **SOAR: Self-Improving Language Models for Evolutionary Program Synthesis** (Pourcel et al., 2025) - Integrates LLMs into a self-improving evolutionary loop, alternating between evolutionary search and hindsight learning to fine-tune the LLM's own sampling and refinement capabilities. [[arXiv]](https://arxiv.org/abs/2507.14172) [[GitHub]](https://github.com/flowersteam/SOAR)
- **FunSearch: Mathematical discoveries from program search with large language models** (DeepMind, 2023) - An evolutionary procedure that pairs a pretrained LLM with a systematic evaluator, iteratively searching the space of programs for better solutions to mathematical and algorithmic problems. [[Nature]](https://www.nature.com/articles/s41586-023-06924-6)
- **SELF: Self-Evolution with Language Feedback** (Lu et al., 2023) - Learns self-feedback and self-refinement, then iteratively fine-tunes on its own refined responses to unlabeled instructions without human intervention. [[arXiv]](https://arxiv.org/abs/2310.00533)
- **Eureka: Human-Level Reward Design via Coding Large Language Models** (Ma et al., 2023) - An algorithm that uses LLMs with evolutionary optimization to autonomously discover and evolve novel reward functions for complex RL tasks. [[arXiv]](https://arxiv.org/abs/2310.12931) [[GitHub]](https://github.com/eureka-research/Eureka)
- **Aletheia: Towards Autonomous Mathematics Research** (DeepMind, 2026) - A math research agent powered by Gemini Deep Think that iteratively generates, verifies, and revises natural-language solutions end-to-end, including autonomous solutions to open questions in Bloom's Erdős Conjectures database. [[arXiv]](https://arxiv.org/abs/2602.10177) [[Blog]](https://deepmind.google/blog/accelerating-mathematical-and-scientific-discovery-with-gemini-deep-think/)
- **A Self-Improving Coding Agent** (Robeyns et al., 2025) - A coding-agent system that autonomously edits its own orchestrating code and improves its benchmark performance through reflection and code updates without gradient-based learning. [[arXiv]](https://arxiv.org/abs/2504.15228)
- **Self-Adapting Language Models (SEAL)** (Zweiger et al., 2025) - Enables a language model to generate its own finetuning data and update directives, applies those self-edits as persistent weight updates, and uses the updated model's downstream performance as the reward for learning which self-edits to produce. [[arXiv]](https://arxiv.org/abs/2506.10943) [[GitHub]](https://github.com/Continual-Intelligence/SEAL)
- **Huxley-Gödel Machine: Human-Level Coding Agent Development by an Approximation of the Optimal Self-Improving Machine** (Wang et al., 2025) - Guides the search over self-modifying coding agents with clade metaproductivity, an estimate of the aggregated benchmark performance of an agent's descendants. [[arXiv]](https://arxiv.org/abs/2510.21614) [[GitHub]](https://github.com/metauto-ai/HGM)
- **Mendel Gödel Machine: Recursive Self-Improving Coding Agents via Comparative Evolution** (Liu et al., 2026) - Adds reaction-norm mutation, which edits an agent from its trajectories on multiple tasks, and cross-lineage hybridization, which edits an agent using another lineage's trajectory on the same task, to self-modifying coding agents. [[arXiv]](https://arxiv.org/abs/2608.07645) [[GitHub]](https://github.com/RealLcz/MGM)

## Decision Pipeline & System Optimization

- **DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines** (Khattab et al., 2023) - A framework that self-optimizes entire ML pipelines end-to-end, automatically tuning the prompts and weights of each step against a defined metric. [[arXiv]](https://arxiv.org/abs/2310.03714) [[GitHub]](https://github.com/stanfordnlp/dspy)
- **QuantAgent: Seeking Holy Grail in Trading by Self-Improving Large Language Model** (Wang et al., 2024) - A two-loop trading agent whose inner loop refines responses from a knowledge base and whose outer loop updates that knowledge base from real-world feedback. [[arXiv]](https://arxiv.org/abs/2402.03755)
- **QuantaAlpha: An Evolutionary Framework for LLM-Driven Alpha Mining** (Han et al., 2026) - Combines LLM intelligence with evolutionary strategies to autonomously mine, evolve, and validate quantitative alpha factors through trajectory-based self-evolution. [[arXiv]](https://arxiv.org/abs/2602.07085) [[GitHub]](https://github.com/QuantaAlpha/QuantaAlpha)
- **TextGrad: Automatic "Differentiation" via Text** (Yuksekgonul et al., 2024) - Propagates textual feedback through multi-component systems to iteratively optimize each piece, analogous to backpropagation for compound ML decision pipelines. [[arXiv]](https://arxiv.org/abs/2406.07496)
- **Reflexion: Language Agents with Verbal Reinforcement Learning** (Shinn et al., 2023) - A framework where agents reflect on failed decisions, store those reflections in memory, and use them to improve future decision-making in subsequent trials. [[arXiv]](https://arxiv.org/abs/2303.11366)
- **EvoFlow: Evolving Diverse Agentic Workflows On The Fly** (Zhang et al., 2025) - Uses tag-based retrieval, crossover, mutation, and niching selection to evolve a diverse population of heterogeneous agentic workflows. [[arXiv]](https://arxiv.org/abs/2502.07373)
- **Gödel Agent: A Self-Referential Agent Framework for Recursive Self-Improvement** (Yin et al., 2024) - A recursive self-improvement framework where a decision-making agent can rewrite its own logic and reasoning processes. [[arXiv]](https://arxiv.org/abs/2410.04444)
- **Self-Refine: Iterative Refinement with Self-Feedback** (Madaan et al., 2023) - An approach for iteratively refining decisions through self-generated feedback, improving output quality without additional training. [[arXiv]](https://arxiv.org/abs/2303.17651)
- **Automated Design of Agentic Systems (ADAS)** (Hu et al., 2024) - A meta-agent iteratively programs new agents in code from an archive of prior discoveries, searching over prompts, tools, and workflows. [[arXiv]](https://arxiv.org/abs/2408.08435) [[GitHub]](https://github.com/ShengranHu/ADAS)

## Self-Training & Self-Play

- **Self-Play Fine-Tuning (SPIN)** (Chen et al., 2024) - A method that allows an LLM to improve itself by playing against its own previous versions, generating training data from self-play to iteratively refine its own policy. [[arXiv]](https://arxiv.org/abs/2401.01335)
- **Self-Rewarding Language Models** (Yuan et al., 2024) - Language models that generate their own training rewards via LLM-as-a-Judge, creating preference datasets to iteratively align and improve the model itself. [[arXiv]](https://arxiv.org/abs/2401.10020)
- **Meta-Rewarding Language Models: Self-Improving Alignment with LLM-as-a-Meta-Judge** (Wu et al., 2024) - Adds a meta-judge step to self-rewarding training so the model evaluates its own judgments and iteratively improves both its instruction following and its judging ability. [[arXiv]](https://arxiv.org/abs/2407.19594)
- **Absolute Zero: Reinforced Self-play Reasoning with Zero Data** (Zhao et al., 2025) - A single model proposes coding tasks that maximize its own learning progress and improves its reasoning by solving them, using a code executor to validate tasks and verify answers without external training data. [[arXiv]](https://arxiv.org/abs/2505.03335) [[GitHub]](https://github.com/LeapLabTHU/Absolute-Zero-Reasoner)
- **R-Zero: Self-Evolving Reasoning LLM from Zero Data** (Huang et al., 2025) - Co-evolves a Challenger and a Solver from one base model with no pre-existing tasks: the Challenger is rewarded for proposing tasks at the Solver's frontier, and the Solver is trained to solve them. [[arXiv]](https://arxiv.org/abs/2508.05004)

## Surveys & Analysis

- **A Survey on Self-Evolution of Large Language Models** (Tao et al., 2024) - A survey focused on self-evolution mechanisms within Large Language Models, proposing a conceptual framework and taxonomy. [[arXiv]](https://arxiv.org/abs/2404.14387)
- **A Survey of Self-Evolving Agents: What, When, How, and Where to Evolve on the Path to Artificial Super Intelligence** (Gao et al., 2025) - A systematic review of self-evolving agents, organizing the field around what, when, and how agents evolve. [[arXiv]](https://arxiv.org/abs/2507.21046) [[GitHub]](https://github.com/CharlesQ9/Self-Evolving-Agents)
- **A Comprehensive Survey of Self-Evolving AI Agents** (Fang et al., 2025) - A unified conceptual framework for self-evolving agentic systems covering system inputs, agent systems, environments, and optimizers, with domain-specific evolution strategies for biomedicine, programming, and finance. [[arXiv]](https://arxiv.org/abs/2508.07407) [[GitHub]](https://github.com/ANative-Lab/Awesome-Self-Evolving-Agents)
- **The Devil Behind Moltbook: Anthropic Safety is Always Vanishing in Self-Evolving AI Societies** (Wang et al., 2026) - Formalizes a self-evolution trilemma and demonstrates, theoretically and empirically, that an isolated agent society cannot simultaneously achieve continuous self-evolution, complete isolation, and safety invariance. [[arXiv]](https://arxiv.org/abs/2602.09877)
- **Self-Improvement of Large Language Models: A Technical Overview and Future Outlook** (Yang et al., 2026) - Organizes LLM self-improvement as a closed loop of data acquisition, data selection, model optimization, and inference refinement, with the model driving each stage and an autonomous evaluation layer guiding the cycle. [[arXiv]](https://arxiv.org/abs/2603.25681) [[GitHub]](https://github.com/Zesearch/self-improvement-llm)

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a pull request. In short:

- The system must **autonomously evolve its own ML model or algorithm** -- not just prompts, memory, or agent workflows.
- Follow the existing format: `**Name** (Author/Org, Year) - One-sentence description. [[Link Type]](URL)`
- Add new entries to the **bottom** of the relevant section.
- One pull request per entry (or a small batch of closely related entries).

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
