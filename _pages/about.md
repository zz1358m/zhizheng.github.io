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

## Research Interests:

My current research focuses on the **optimization of LLMs under limited resources**: fine-tuning LLMs and LLM agents with minimal GPU memory and compute, toward on-device deployment. This includes inference-only fine-tuning with Evolution Strategies (ES) and zeroth-order methods (e.g., [**Agentic-ESOpt**](https://arxiv.org/abs/2608.17310), [**Hyper-ES**](https://arxiv.org/abs/2608.05541), [**Understanding ES**](https://arxiv.org/abs/2608.27351), [**AIM-ZO**](https://arxiv.org/abs/2609.35257)).

More broadly, I am interested in **LLM optimization as a whole**, including:

* **Reinforcement learning** for LLM reasoning (e.g., [**SofT-GRPO**](https://arxiv.org/pdf/2511.06411)).
* **LLM acceleration** through latent reasoning and memory, diffusion LLMs, and multi-token prediction (e.g., [**ATP-Latent**](https://arxiv.org/pdf/2601.21598), [**Latent Memory**](https://arxiv.org/pdf/2606.10572)).
* **LLMs as optimizers** that solve challenging problems through agentic test-time search (e.g., [**Agentic-ESOpt**](https://arxiv.org/abs/2608.17310), [**MCTS-AHD**](https://arxiv.org/abs/2501.08603), [**APEX**](https://arxiv.org/abs/2605.21240), [**GraphSkillEvo**](https://arxiv.org/abs/2609.21749)), building on my earlier work on learned heuristics for combinatorial optimization (e.g., [**UDC**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=nxJ4qM4AAAAJ&citation_for_view=nxJ4qM4AAAAJ:2osOgNQ5qMEC), [**DPN**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=nxJ4qM4AAAAJ&citation_for_view=nxJ4qM4AAAAJ:9yKSN-GCB0IC)).

I am willing to discuss the above topics via email!

My CV is here: [Zhi Zheng's Curriculum Vitae](https://github.com/zz1358m/zhizheng.github.io/blob/master/assets/CV_Zhi_Zheng.pdf).

Email: zhi.zheng@u.nus.edu / [Google Scholar Profile](https://scholar.google.com/citations?user=nxJ4qM4AAAAJ&hl=en) / [Github](https://github.com/zz1358m) / [alphaXiv](https://www.alphaxiv.org/@zhi-zheng)

## Selected Publications:

### Arxiv Preprints:


* **Agentic ESOpt: Fine-Tuning Long-Horizon LLM Agents with Minimal GPU Requirements**<br>**Zhi Zheng**, Rongsheng Chen, Yunpeng Ba, Zhenkun Wang, Yee Whye Teh, and Wee Sun Lee;<br>*Arxiv, NeurIPS2026 Workshop @ Resource-Aware Agentic AI*, 2026. [[Project Page](https://zz1358m.github.io/Project-Agentic-ESOpt) & [Paper](https://arxiv.org/abs/2608.17310) & [Code](https://github.com/zz1358m/Agentic-ESOpt)].


* **Understanding Evolution Strategies for LLM Reasoning: Broader Reasoning Coverage than GRPO**<br>Yunpeng Ba\*, **Zhi Zheng\***, Yue Xie, Jiaqing Li, Xialiang Tong, Tao Zhong, Mingxuan Yuan, Zhichao Lu, Xuyang Wu, and Zhenkun Wang;<br>*Arxiv*, 2026. [[Paper](https://arxiv.org/abs/2608.27351)].


* **Hyper-ES: Effective Evolution Strategies for LLM Reasoning via Descent Direction Merging**<br>Yu Gu\*, **Zhi Zheng\***, Yunpeng Ba, Xialiang Tong, Mingxuan Yuan, and Zhenkun Wang;<br>*Arxiv*, 2026. [[Paper](https://arxiv.org/abs/2608.05541)].


* **AIM-ZO: Activation-Informed Subspace Maintenance for Zeroth-Order LLM Fine-Tuning**<br>Yue Xie\*, **Zhi Zheng\***, Yunpeng Ba, Xuyang Wu, Xialiang Tong, Zhichao Lu, Tao Zhong, and Zhenkun Wang;<br>*Arxiv*, 2026. [[Paper](https://arxiv.org/abs/2609.35257)].


* **GraphSkillEvo: Evolutionary Optimization of Graph-Structured Agent Skills**<br>Rui Sun\*, **Zhi Zheng\***, Zhenkun Wang, and Zhichao Lu;<br>*Arxiv*, 2026. [[Paper](https://arxiv.org/abs/2609.21749)].


* **One Token per Multimodal Evidence: Latent Memory for Resource-Constrained QA**<br>**Zhi Zheng**, Ziqiao Meng, Hao Luan, Wei Liu, and Wee Sun Lee;<br>*Arxiv, ICML2026 Workshop @ Efficient Multimodal Question Answering*, 2026. [[Paper](https://arxiv.org/pdf/2606.10572) & [Code](https://github.com/zz1358m/Latent-Memory-Master)].


* **SofT-GRPO: Surpassing Discrete-Token LLM Reinforcement Learning via Gumbel-Reparameterized Soft-Thinking Policy Optimization**<br>**Zhi Zheng**, Yu Gu, Wei Liu, Yee Whye Teh, and Wee Sun Lee;<br>*Arxiv*, 2025. [[Paper](https://arxiv.org/pdf/2511.06411) & [Code](https://github.com/zz1358m/SofT-GRPO-master)].

* **Beyond Imitation: Reinforcement Learning for Active Latent Planning**<br>**Zhi Zheng** and Wee Sun Lee;<br>*Arxiv*, 2026. [[Paper](https://arxiv.org/pdf/2601.21598) & [Code](https://github.com/zz1358m/ATP-Latent-master)].


* **Reasoning-CV: Fine-tuning Powerful Reasoning LLMs for Knowledge-Assisted Claim Verification**<br>**Zhi Zheng** and Wee Sun Lee;<br>*Arxiv*, 2025. [[Paper](https://arxiv.org/abs/2505.12348) & [Code](https://github.com/zz1358m/Reasoning-CV)].



### Accepted Conference Papers:


* **Monte Carlo Tree Search for Comprehensive Exploration in LLM-Based Automatic Heuristic Design**<br>**Zhi Zheng**, Zhuoliang Xie, Zhenkun Wang, and Bryan Hooi;<br>*International Conference on Machine Learning **(ICML)***, 2025. [[Paper](https://arxiv.org/abs/2501.08603) & [Code](https://github.com/zz1358m/MCTS-AHD-master/tree/main)].

* **UDC: A Unified Neural Divide-and-Conquer Framework for Large-Scale Combinatorial Optimization Problems**<br>**Zhi Zheng**, Changliang Zhou, Xialiang Tong, Mingxuan Yuan, Zhenkun Wang;<br>*Advances in Neural Information Processing Systems **(NeurIPS)***, 2024. [[Paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=nxJ4qM4AAAAJ&citation_for_view=nxJ4qM4AAAAJ:2osOgNQ5qMEC) & [Code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/UDC-Large-scale-CO-master)].
* **DPN: Decoupling Partition and Navigation for Neural Solvers of Min-max Vehicle Routing Problems**<br>**Zhi Zheng\***, Shunyu Yao\*, Zhenkun Wang, Xialiang Tong, Mingxuan Yuan, Ke Tang;<br>*International Conference on Machine Learning **(ICML)***, 2024. [[Paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=nxJ4qM4AAAAJ&citation_for_view=nxJ4qM4AAAAJ:9yKSN-GCB0IC) & [Code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/DPN-minmaxVRP-master)].

* **Learning Encodings for Constructive Neural Combinatorial Optimization Needs to Regret**<br>Rui Sun\*, **Zhi Zheng\***, Zhenkun Wang;<br>*38th AAAI Conference on Artificial Intelligence **(AAAI)***, 2024. [[Paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=nxJ4qM4AAAAJ&citation_for_view=nxJ4qM4AAAAJ:d1gkVwhDpl0C) & [Code](https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/LCH-Regret)].

### Accepted Journal Articles:

* **Pareto Improver: Learning Improvement Heuristics for Multi-Objective Route Planning**<br>**Zhi Zheng**\*, Shunyu Yao\*, Genghui Li, Linxi Han, and Zhenkun Wang;<br>*IEEE Transactions on Intelligent Transportation Systems **(T-ITS)***, 2023. [[Paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=nxJ4qM4AAAAJ&citation_for_view=nxJ4qM4AAAAJ:u-x6o8ySG0sC) & [Code](https://github.com/CIAM-Group/NCO_code/tree/main/multi-objective/PI)].

\* for equal contribution

## Teaching:

* Teaching Assistant for CS3244, School of Computing, NUS (2025 Spring).

* Teaching Assistant for CS3263, School of Computing, NUS (2025 Fall).
