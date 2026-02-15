---
layout: page
title: Overview
permalink: /
weight: 1
---

<div style="text-align: center; display: flex; width: 100%; justify-content: space-evenly; align-items: center; gap: 1em; padding: 2em">
  <img style="width: 40%;" src="https://github.com/Open-Finance-Lab/SecureFinAI_Contest_2025/blob/main/docs/assets/logos/acm_icaif.png?raw=true" alt="ACM ICAIF Logo">
  <img style="width: 30%;" src="https://github.com/Open-Finance-Lab/SecureFinAI_Contest_2025/blob/main/docs/assets/logos/finai.png?raw=true" alt="The Fin AI Logo">
</div>

### Thanks to the AI4Finance Foundation open source community for their support.



## Introduction

As AI continues to advance at a fast pace, more FinAI agents are being developed for the finance sector, such as FinRL trading agents [1,2,3], FinGPT agents [4,5] with multimodal capabilities [6], and regulatory reporting agents [7]. The **Secure FinAI Contest 2025** encourages the development of FinAI agents based on the frameworks FinRL [2,3] and FinGPT [4].

The Secure FinAI Contest 2025 explores and evaluates the capability of machine learning methods in finance, with following features:

1. **FinRL-Transformer for Cryptocurrency Trading**. Cryptocurrency markets are highly volatile, non-stationary, and sensitive to market sentiment. Traditional FinRL policy architectures, such as MLPs, often struggle to generalize under such conditions due to limited temporal memory and policy instability. Transformers, with their attention mechanism and scalability, provide a promising direction for learning complex temporal patterns and long-term dependencies in financial time series data. We aim to encourage the development of AI and ML trading systems for cryptocurrency markets. 

2. **Multimodal financial foundation models (MFFMs) for regulation and compliance**. Regulation and compliance are the foundations of the financial industry. Understanding regulatory texts, business contracts, SEC filings, and disclosures is essential for financial analysis and automated compliance. It requires understanding and reasoning over multimodal data, including text, tables, audio, etc. We aim to encourage the development of FinAI agents and systematically benchmark foundation models in financial analytics, regulation, and compliance to fill the gaps in the Open Financial LLM Leaderboard



We design three tasks: (1) FinRL-Transformer for Cryptocurrency Trading, (2) FinGPT Agents for SEC Filings Analysis, and (3) FinGPT Agents for Regulation and Compliance. These challenges allow contestants to participate in various financial tasks and contribute to secure finance using state-of-the-art technologies with privacy-preserving and verifiable computation frameworks. We welcome students, researchers, and engineers who are passionate about finance, machine learning, and security to partake in the contest.

## Tasks
Each team can choose to participate in one or more tasks. The prizes will be awarded for each task.

### Task I: FinRL-Transformer for Cryptocurrency Trading Agents

This task is to develop crypto trading agents by integrating transformer-based architectures and LLM-generated signals in FinRL, using financial news and market data. Participants can build upon transformer architectures (e.g., with new attention mechanisms, new ways to inject LLM-processed news signals into the transformer agent, new optimization algorithms) or explore more computationally intensive directions, such as adapting variants of modern transformer training methods to this crypto trading task.

**Datasets**: We will provide the second-level LOB data and financial news for Bitcoin. Participants are permitted to use additional external datasets.

### Task II: FinGPT-Powered Compliance Agents

This task focuses on developing FinGPT agents for regulatory and compliance scenarios in finance. Participants will build LLM-based agents to handle a range of subtasks, including analyzing SEC filings, financial data retrieval, sentiment analysis, antitrust and copyright reasoning, patent and IP protection, and financial audio transcription. 


**Datasets**: We will provide regulatory datasets covering various compliance scenarios including AML data, regulatory filings, compliance questionnaires, and audit trails, along with evaluation frameworks.

### Task III：FinGPT-Powered Agents for MultiModal Financial Data

This task focuses on developing FinGPT agents to process and analyze multimodal financial data. We use the MultiFinBen [8] datasets as the benchmark datasets. Participants will build LLM-based agents to handle a range of subtasks, involving multimodal data, such as charts, image, and audio.  

**Datasets**: We will provide selected databsets from MultifinBen.


<p style="font-size: 14px;">
[1] Wang, Keyi, et al. "FinRL Contests: Data‐Driven Financial Reinforcement Learning Agents for Stock and Crypto Trading." <em>Artificial Intelligence for Engineering</em> (2025). [<a href="https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/aie2.12004">IET</a>] [<a href="https://arxiv.org/abs/2504.02281">arXiv</a>]
</p>
<p style="font-size: 14px;">
[2] Liu, Xiao-Yang, et al. "Finrl-meta: Market environments and benchmarks for data-driven financial reinforcement learning." <em>Advances in Neural Information Processing Systems</em> 35 (2022): 1835-1849. [<a href="https://papers.neurips.cc/paper_files/paper/2022/file/0bf54b80686d2c4dc0808c2e98d430f7-Paper-Datasets_and_Benchmarks.pdf">NeurIPS</a>]
</p>
<p style="font-size: 14px;">
[3] Liu, Xiao-Yang, et al. "FinRL: A deep reinforcement learning library for automated stock trading in quantitative finance." <em>arXiv preprint</em> arXiv:2011.09607 (2020). [<a href="https://arxiv.org/abs/2011.09607">arXiv</a>] [<a href="https://neurips.cc/virtual/2020/19841">NeurIPS 2020</a>]
</p>
<p style="font-size: 14px;">
[4] Liu, Xiao-Yang, et al. "Fingpt: Democratizing internet-scale data for financial large language models." <em>arXiv preprint</em> arXiv:2307.10485 (2023). [<a href="https://arxiv.org/abs/2307.10485">arXiv</a>]
</p>
<p style="font-size: 14px;">
[5] Tian, Felix, et al. "Customized fingpt search agents using foundation models." <em>Proceedings of the 5th ACM International Conference on AI in Finance</em>. 2024. [<a href="https://dl.acm.org/doi/10.1145/3677052.3698637">ACM</a>]
</p>
<p style="font-size: 14px;">
[6] Yanglet, Xiao-Yang Liu, Yupeng Cao, and Li Deng. "Multimodal financial foundation models (mffms): Progress, prospects, and challenges." <em>arXiv preprint</em> arXiv:2506.01973 (2025). [<a href="https://www.arxiv.org/abs/2506.01973">arXiv</a>]
</p>
<p style="font-size: 14px;">
[7] Han, Shijie, et al. "Xbrl agent: Leveraging large language models for financial report analysis." <em>Proceedings of the 5th ACM International Conference on AI in Finance</em>. 2024. [<a href="https://dl.acm.org/doi/abs/10.1145/3677052.3698614">ACM</a>]
</p>
<p style="font-size: 14px;">
[8] Peng, Xueqing, et al. "MultiFinBen: A Multilingual, Multimodal, and Difficulty-Aware Benchmark for Financial LLM Evaluation." <em>arXiv preprint</em> arXiv:2506.14028 (2025). [<a href="https://arxiv.org/abs/2506.14028">arXiv</a>]
</p>
<p style="font-size: 14px;">
[9] Cao, Yupeng, et al. "FinAudio: A Benchmark for Audio Large Language Models in Financial Applications." <em>arXiv preprint</em> arXiv preprint arXiv:2503.20990 (2025). [<a href="https://arxiv.org/pdf/2503.20990?">arXiv</a>]
</p>


## Contact
Contact email: [finrlcontest@gmail.com](mailto:finrlcontest@gmail.com)

Contestants can communicate any questions on 
* [Discord](https://discord.gg/dJY5cKzmkv).
* WeChat Group:
<div style="text-align: center; display: flex; width: 100%; justify-content: space-evenly; align-items: left; gap: 1em; padding: 2em">
  <img style="width: 20%;" src="https://github.com/Open-Finance-Lab/SecureFinAI_Contest_2025/blob/main/docs/assets/pictures/wechat_group.jpeg?raw=true" alt="wechat group">
</div>




