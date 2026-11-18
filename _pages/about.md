---
permalink: /
title: "Zhi Zheng's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html


---

I am a **third-year Ph.D. candidate** from [School of Computing](https://www.comp.nus.edu.sg/), [National University of Singapore](https://nus.edu.sg/), supervised by [Prof. Wee Sun Lee](https://www.comp.nus.edu.sg/cs/people/leews/), and [Prof. Yee Whye Teh](https://scholar.google.com/citations?user=y-nUzMwAAAAJ&hl=en) from Oxford.

Previously, I finished my undergraduate studies in June 2024 at the Southern University of Science and Technology (SUSTech), China, focusing on Neural Combinatorial Optimization and Reinforcement Learning, supervised by [Prof. Zhenkun Wang](https://scholar.google.com/citations?user=r9ezy2gAAAAJ&hl=en), [Prof. Xin Yao](https://scholar.google.com/citations?hl=en&user=UUtYPl4AAAAJ), and [Prof. Ke Tang](https://scholar.google.com/citations?user=mzLHFbAAAAAJ&hl=en). I am still working with them now.

**[Curriculum Vitae (PDF)](https://zz1358m.github.io/zhizheng.github.io/assets/CV_Zhi_Zheng.pdf)** / Email: zhi.zheng@u.nus.edu / [Google Scholar](https://scholar.google.com/citations?user=nxJ4qM4AAAAJ&hl=en) / [GitHub](https://github.com/zz1358m) / [alphaXiv](https://www.alphaxiv.org/@zhi-zheng) / [ORCID](https://orcid.org/0009-0005-8785-8177)

## Research Overview

My current research focuses on the **optimization of LLMs under limited resources**: fine-tuning LLMs and LLM agents with minimal GPU memory and compute, toward on-device deployment. This includes inference-only fine-tuning with Evolution Strategies (ES) and zeroth-order methods (e.g., [**Agentic-ESOpt**](https://arxiv.org/abs/2608.17310), [**Hyper-ES**](https://arxiv.org/abs/2608.05541), [**Understanding ES**](https://arxiv.org/abs/2608.27351), [**AIM-ZO**](https://arxiv.org/abs/2609.35257)).

More broadly, I am interested in **LLM optimization as a whole**, including:

* **Reinforcement learning** for LLM reasoning (e.g., [**SofT-GRPO**](https://arxiv.org/pdf/2511.06411)).
* **LLM acceleration** through latent reasoning and memory, diffusion LLMs, and multi-token prediction (e.g., [**ATP-Latent**](https://arxiv.org/pdf/2601.21598), [**Latent Memory**](https://arxiv.org/pdf/2606.10572)).
* **LLMs as optimizers** that solve challenging problems through agentic test-time search (e.g., [**Agentic-ESOpt**](https://arxiv.org/abs/2608.17310), [**MCTS-AHD**](https://arxiv.org/abs/2501.08603), [**APEX**](https://arxiv.org/abs/2605.21240), [**GraphSkillEvo**](https://arxiv.org/abs/2609.21749)), building on my earlier work on learned heuristics for combinatorial optimization (e.g., [**UDC**](https://arxiv.org/abs/2407.00312), [**DPN**](https://arxiv.org/abs/2405.17272)).

I am willing to discuss the above topics via email!

## Publications

(\* Equal contribution; <u>underlined</u>: research mentees; † corresponding author. Full list on [Google Scholar](https://scholar.google.com/citations?user=nxJ4qM4AAAAJ&hl=en).)

### Preprints

* **\[p.1\]** Ziqiao Meng, <u>Rongsheng Chen</u>, **Zhi Zheng**, Nikita Kazeev, Zhenkun Wang, Andrey Ustyuzhanin, Wee Sun Lee. *CrystalAR: Autoregressive Modeling for Symmetric Crystal Generation.* arXiv:2610.27762. [[Paper](https://arxiv.org/abs/2610.27762)].

* **\[p.2\]** Yibo Li, Jinhang Qiu, **Zhi Zheng**†, Qianyun Guo, Jiaying Wu, Shuo Ji, Bryan Hooi. *Learn2Play Bench: How Well Do LLM Agents Learn from Experience in Unfamiliar Environments?* arXiv:2610.08215. [[Paper](https://arxiv.org/abs/2610.08215)].

* **\[p.3\]** <u>Yue Xie</u>\*, **Zhi Zheng**\*†, <u>Yunpeng Ba</u>, Xuyang Wu, Xialiang Tong, Zhichao Lu, Tao Zhong, Zhenkun Wang. *AIM-ZO: Activation-Informed Subspace Maintenance for Zeroth-Order LLM Fine-Tuning.* arXiv:2609.35257. [[Paper](https://arxiv.org/abs/2609.35257)].

* **\[p.4\]** <u>Rui Sun</u>\*, **Zhi Zheng**\*†, Zhenkun Wang, Zhichao Lu. *GraphSkillEvo: Evolutionary Optimization of Graph-Structured Agent Skills.* arXiv:2609.21749. [[Paper](https://arxiv.org/abs/2609.21749)].

* **\[p.5\]** <u>Yunpeng Ba</u>\*, **Zhi Zheng**\*†, <u>Yue Xie</u>, <u>Jiaqing Li</u>, Xialiang Tong, Tao Zhong, Mingxuan Yuan, Zhichao Lu, Xuyang Wu, Zhenkun Wang†. *Understanding Evolution Strategies for LLM Reasoning: Broader Reasoning Coverage than GRPO.* arXiv:2608.27351. [[Paper](https://arxiv.org/abs/2608.27351)].

* **\[p.6\]** **Zhi Zheng**, <u>Rongsheng Chen</u>, <u>Yunpeng Ba</u>, Zhenkun Wang, Yee Whye Teh, Wee Sun Lee. *Agentic ESOpt: Fine-Tuning Long-Horizon LLM Agents with Minimal GPU Requirements.* arXiv:2608.17310. NeurIPS 2026 Workshop on Resource-Aware Agentic AI. [[Project Page](https://zz1358m.github.io/Project-Agentic-ESOpt) & [Paper](https://arxiv.org/abs/2608.17310) & [Code](https://github.com/zz1358m/Agentic-ESOpt)].

* **\[p.7\]** <u>Yu Gu</u>\*, **Zhi Zheng**\*†, <u>Yunpeng Ba</u>, Xialiang Tong, Mingxuan Yuan, Zhenkun Wang†. *Hyper-ES: Effective Evolution Strategies for LLM Reasoning via Descent Direction Merging.* arXiv:2608.05541. [[Paper](https://arxiv.org/abs/2608.05541) & [Code](https://github.com/kuangrepi/Hyper-ES)].

* **\[p.8\]** **Zhi Zheng**, Ziqiao Meng, Hao Luan, Wei Liu, Wee Sun Lee. *One Token per Multimodal Evidence: Latent Memory for Resource-Constrained QA.* arXiv:2606.10572. ICML 2026 Workshop on Efficient Multimodal Question Answering. [[Paper](https://arxiv.org/abs/2606.10572) & [Code](https://github.com/zz1358m/Latent-Memory-Master)].

* **\[p.9\]** Yibo Li, Jiashuo Yang, **Zhi Zheng**, Zhiyuan Hu, Yuan Sui, Shizun Wang, Yufei He, Bryan Hooi. *APEX: Autonomous Policy Exploration for Self-Evolving LLM Agents.* arXiv:2605.21240. [[Paper](https://arxiv.org/abs/2605.21240)].

* **\[p.10\]** **Zhi Zheng**, Wee Sun Lee. *Beyond Imitation: Reinforcement Learning for Active Latent Planning.* arXiv:2601.21598. [[Paper](https://arxiv.org/abs/2601.21598) & [Code](https://github.com/zz1358m/ATP-Latent-master)].

* **\[p.11\]** **Zhi Zheng**, <u>Yu Gu</u>, Wei Liu, Yee Whye Teh, Wee Sun Lee. *SofT-GRPO: Surpassing Discrete-Token LLM Reinforcement Learning via Gumbel-Reparameterized Soft-Thinking Policy Optimization.* arXiv:2511.06411. [[Paper](https://arxiv.org/abs/2511.06411) & [Code](https://github.com/zz1358m/SofT-GRPO-master)].

* **\[p.12\]** **Zhi Zheng**, Wee Sun Lee. *Reasoning-CV: Fine-tuning Powerful Reasoning LLMs for Knowledge-Assisted Claim Verification.* arXiv:2505.12348. [[Paper](https://arxiv.org/abs/2505.12348) & [Code](https://github.com/zz1358m/Reasoning-CV)].

### Conference and Journal Publications

* **\[c.1\]** Fu Luo, Yaoxin Wu, **Zhi Zheng**, Zhenkun Wang†. *Rethinking Neural Combinatorial Optimization for Vehicle Routing Problems with Different Constraint Tightness Degrees.* **NeurIPS 2025**. [[Paper](https://arxiv.org/abs/2505.24627)].

* **\[c.2\]** **Zhi Zheng**, Zhuoliang Xie, Zhenkun Wang, Bryan Hooi†. *Monte Carlo Tree Search for Comprehensive Exploration in LLM-Based Automatic Heuristic Design.* **ICML 2025**. [[Paper](https://arxiv.org/abs/2501.08603) & [Code](https://github.com/zz1358m/MCTS-AHD-master/tree/main)].

* **\[c.3\]** Han Li, Fei Liu, **Zhi Zheng**, Yu Zhang, Zhenkun Wang†. *CaDA: Cross-Problem Routing Solver with Constraint-Aware Dual-Attention.* **ICML 2025**. [[Paper](https://arxiv.org/abs/2412.00346)].

* **\[c.4\]** **Zhi Zheng**, Changliang Zhou, Xialiang Tong, Mingxuan Yuan, Zhenkun Wang†. *UDC: A Unified Neural Divide-and-Conquer Framework for Large-Scale Combinatorial Optimization Problems.* **NeurIPS 2024**. [[Paper](https://arxiv.org/abs/2407.00312) & [Code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/UDC-Large-scale-CO-master)].

* **\[c.5\]** **Zhi Zheng**\*, Shunyu Yao\*, Zhenkun Wang†, Xialiang Tong, Mingxuan Yuan, Ke Tang. *DPN: Decoupling Partition and Navigation for Neural Solvers of Min-max Vehicle Routing Problems.* **ICML 2024**. [[Paper](https://arxiv.org/abs/2405.17272) & [Code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/DPN-minmaxVRP-master)].

* **\[c.6\]** <u>Rui Sun</u>\*, **Zhi Zheng**\*, Zhenkun Wang†. *Learning Encodings for Constructive Neural Combinatorial Optimization Needs to Regret.* **AAAI 2024**. [[Paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=nxJ4qM4AAAAJ&citation_for_view=nxJ4qM4AAAAJ:d1gkVwhDpl0C) & [Code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/LCH-Regret)].

* **\[c.7\]** **Zhi Zheng**\*, Shunyu Yao\*, Genghui Li, Linxi Han, Zhenkun Wang†. *Pareto Improver: Learning Improvement Heuristics for Multi-Objective Route Planning.* **IEEE Transactions on Intelligent Transportation Systems**, 25(1):1033–1043, 2024. [[Paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=nxJ4qM4AAAAJ&citation_for_view=nxJ4qM4AAAAJ:u-x6o8ySG0sC) & [Code](https://github.com/CIAM-Group/NCO_code/tree/main/multi-objective/PI)].

## Research Mentoring

Students I have mentored on research projects, in collaboration with Zhenkun Wang's group at SUSTech.

* **Yunpeng Ba** (SUSTech). Evolution strategies for LLM reasoning. Papers: \[p.5\] as first author, \[p.3\], \[p.6\], \[p.7\].
* **Yue Xie** (SUSTech). Zeroth-order LLM fine-tuning. Papers: \[p.3\] as first author, \[p.5\].
* **Yu Gu** (Nanjing University; intern at SUSTech). Descent-direction merging and continual learning with ES. Papers: \[p.7\] as first author, \[p.11\].
* **Rui Sun** (SUSTech; M.S. at City University of Hong Kong). Neural combinatorial optimization; evolutionary optimization of agent skills. Papers: \[c.6\] and \[p.4\] as first author.
* **Rongsheng Chen** (SUSTech). ES fine-tuning of long-horizon agents. Papers: \[p.6\], \[p.1\].
* **Jiaqing Li** (Harbin Institute of Technology, Weihai). Search-space compression for ES. Paper: \[p.5\].

## Honors & Awards

* NUS Research Scholarship, 2024 – Present.
* Outstanding Graduation Thesis, SUSTech, 2024.
* Outstanding Graduate, SUSTech, 2024.

## Invited Talks

* **Agentic ESOpt: Fine-Tuning Long-Horizon LLM Agents with Minimal GPU Requirements.** Southern University of Science and Technology. Host: Zhenkun Wang. 2026.
* **Recent Advances in LLM-Based Automatic Heuristic Design.** Dalian University of Technology. Host: Yaqing Hou. 02/2026. [[Video](https://www.bilibili.com/video/BV1BjcMzqE7R/)].
* **Monte Carlo Tree Search for Comprehensive Exploration in LLM-Based Automatic Heuristic Design.** NICE Student Seminar (online). Organizer: Handing Wang, Xidian University. 06/2025. [[Video](https://www.bilibili.com/video/BV1Ck7azREzp/)].

## Teaching

* **CS3263: Foundations of Artificial Intelligence**, NUS, Fall 2025. Teaching Assistant. Led tutorial sessions and graded course projects.
* **CS3244: Machine Learning**, NUS, Spring 2025. Teaching Assistant. Led tutorial sessions and graded course projects.

## Professional Service

* Conference reviewer: NeurIPS, ICML, ICLR (2023 – Present).
* Journal reviewer: IEEE Transactions journals.

## Open-Source Software

(GitHub stars as of 11/2026.)

* [**MCTS-AHD**](https://github.com/zz1358m/MCTS-AHD-master): LLM-based automatic heuristic design with Monte Carlo tree search (92 stars).
* [**Agentic ESOpt**](https://github.com/zz1358m/Agentic-ESOpt): full-parameter ES fine-tuning of long-horizon LLM agents (87 stars).
* [**SofT-GRPO**](https://github.com/zz1358m/SofT-GRPO-master): reinforcement learning for soft-thinking LLM reasoning (53 stars).
* Contributor to [**CIAM-Group/NCO_code**](https://github.com/CIAM-Group/NCO_code): UDC, DPN, LCH-Regret, and Pareto Improver (100 stars).
