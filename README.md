# Awesome Rubric-based Evaluation and Alignment for LLMs

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
![Stars](https://img.shields.io/github/stars/Venn2336/awesome-rubrics-based-llm?style=social)

A curated list of papers, benchmarks, and resources related to **rubric-based evaluation, benchmarking, and training for large language models (LLMs)**.

## 📝 Content
- [Rubric-based Benchmarks](#rubric-based-benchmarks)
- [Rubric-based Evaluation Methods](#rubric-based-evaluation-methods)
- [Rubric-based Reinforcement Learning / Training](#rubric-based-reinforcement-learning--training)
- [Rubric Generation](#rubric-generation)

---

# Rubric-based Benchmarks

- **RubricBench: Aligning Model-Generated Rubrics with Human Standards**  
  https://arxiv.org/abs/2603.01562

- **AdvancedIF: Rubric-Based Benchmarking and Reinforcement Learning for Advancing LLM Instruction Following**  
  https://arxiv.org/abs/2511.10507

- **ResearchRubrics: A Benchmark of Prompts and Rubrics For Evaluating Deep Research Agents**  
  https://arxiv.org/abs/2511.07685

- **Healthbench: Evaluating large language models towards improved human health**  
  https://arxiv.org/abs/2505.08775

- **PROFBENCH: MULTI-DOMAIN RUBRICS REQUIRING PROFESSIONAL KNOWLEDGE TO ANSWER AND JUDGE**  
  https://arxiv.org/pdf/2510.18941

- **CL-Bench: A Clinical Benchmark for Evaluating Medical LLMs**  
  https://arxiv.org/abs/2406.09945


- **Health-SCORE: Towards Scalable Rubrics for Improving Health-LLMs**
  https://arxiv.org/abs/2601.18706

- **WILDBENCH: BENCHMARKING LLMS WITH
CHALLENGING TASKS FROM REAL USERS IN THE WILD**
  https://arxiv.org/pdf/2406.04770

- **Prbench: Large-scale expert rubrics for evaluating high-stakes professional reasoning**
   https://arxiv.org/pdf/2511.11562

- **MT-Bench: Benchmarking LLMs in Multi-Turn Conversations**  
  https://arxiv.org/abs/2306.05685

- **Paperbench: Evaluating ai’s ability to replicate ai research**
  https://arxiv.org/abs/2504.01848

- **MultiChallenge: A realistic multi-turn conversation evaluation benchmark challenging to frontier LLMs**
  https://arxiv.org/pdf/2510.07284


---

# Rubric-based Evaluation Methods

- **LLM-Rubric: A Framework for Multi-Dimensional Evaluation of LLM Outputs**  
  https://aclanthology.org/2024.acl-long.745

- **Autorubric: A Unified Framework for Rubric-Based LLM Evaluation**  
  https://arxiv.org/pdf/2603.00077

- **AutoSCORE: Enhancing Automated Scoring with Multi-Agent LLMs**  
  https://arxiv.org/abs/2509.21910

- **G-Eval: NLG Evaluation using GPT-4 with Better Human Alignment**  
  https://arxiv.org/abs/2303.16634


- **Learning to Judge: LLMs Designing and Applying Evaluation Rubrics**
  https://arxiv.org/pdf/2602.08672



- **RUBRIC-MQM : Span-Level LLM-as-judge in Machine Translation For High-End Models**
  https://aclanthology.org/2025.acl-industry.12.pdf


- **SedarEval: Automated Evaluation using Self-Adaptive Rubrics**
  https://arxiv.org/pdf/2501.15595

- **Datasheets aren’t enough: Datarubrics
for automated quality metrics and accountability**
  https://arxiv.org/abs/2506.01789

- **Rubric is all you need: Enhancing llm-based code evaluation with question-specific rubrics**
  https://arxiv.org/pdf/2503.23989

- **Rubrics as an Attack Surface: Stealthy Preference Drift in LLM Evaluation**  
  https://arxiv.org/abs/2602.13576

---

# Rubric-based Reinforcement Learning / Training

- **Breaking the Exploration Bottleneck: Rubric-Scaffolded Reinforcement Learning**  
  https://arxiv.org/abs/2508.16949

- **Rubrics as rewards: Reinforcement learning beyond verifiable domains**  
  https://arxiv.org/pdf/2507.17746

- **Alternating Reinforcement Learning for Rubric-Based Reward Modeling in Non-Verifiable LLM Post-Training**
  https://arxiv.org/pdf/2602.01511




- **Kimi K2: Open Agentic Intelligence**
  https://www.kimi.com/blog/kimi-k2

- **Baichuan-M3: Modeling Clinical Inquiry for Reliable Medical Decision-Making**
  https://arxiv.org/pdf/2602.06570


- **DeepSeek-V3.2: Pushing the Frontier of Open Large Language Models**
  https://arxiv.org/pdf/2512.02556

- **Checklists are better than reward models for aligning language models**
  https://arxiv.org/pdf/2507.18624

- **Chasing the tail: Effective rubric-based reward modeling for large language model post-training**
   https://arxiv.org/pdf/2509.21500


- **Reinforcement learning with rubric anchors**
   https://arxiv.org/pdf/2508.12790


- **R3: Robust Rubric-Agnostic Reward Models**
   https://arxiv.org/pdf/2505.13388
---

# Rubric Generation

- **Generating High-Quality Rubrics for Automated Evaluation of LLMs**  
  https://arxiv.org/abs/2407.01445

- **Automatic Rubric Generation for Large Language Model Evaluation**  
  https://arxiv.org/abs/2406.08469

- **Rubrichub: A comprehensive and highly discriminative rubric dataset via automated coarse-to-fine generation**
   https://arxiv.org/pdf/2601.08430

- **OpenRubrics: Towards Scalable Synthetic Rubric Generation for Reward Modeling and LLM Alignment**
   https://arxiv.org/pdf/2510.07743

- **Auto-rubric: Learning to extract generalizable criteria for reward
modeling**
   https://arxiv.org/pdf/2510.17314v1

- **Online Rubrics Elicitation from Pairwise Comparisons**
   https://arxiv.org/pdf/2510.07284
---

## 🤝 Contributing

Contributions are welcome! If you want to add a paper, benchmark, or tool to this list:

1.  **Check for duplicates**: Ensure the paper isn't already listed.
2.  **Paper Quality**: We prioritize peer-reviewed papers (ACL, NeurIPS, ICML, etc.) or high-impact Arxiv preprints with open-source code/data.
3.  **Format**: Use the following format for your PR:
    ```markdown
    - **[Paper Title](Link)**
      - *Venue/Year* | [Code](Link) | [Project Page](Link)
      - *Quick Summary*: 1-2 sentences explaining the rubric's role or the alignment method.
    ```
4.  **Submit a PR**: Create a new branch and submit your pull request for review.
