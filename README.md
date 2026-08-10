# Dava Valuation in Machine Learning



![image-20260306222323495](./image/image2.png)


##  Overview

![Survey](https://img.shields.io/badge/Survey-Paper%20Collection-2ea44f)
![Awesome](https://img.shields.io/badge/Awesome-Data%20Valuation-4C6FFF)

This repository summarizes representative papers from four major methodological families:

-  Cooperative Game-based Valuation
-  Gradient-based Valuation
-  Utility Learning and Bilevel Optimization
-  Model-agnostic Valuation

## Latest Updates

[10/08/2026] [An Asymptotic Analysis of the Shapley Value for Dataset Valuation](https://arxiv.org/pdf/2607.03374) (Arxiv'26)

[LTSV: Layered Type-Constrained Shapley Value forHeterogeneous Graph Data Valuation](https://dl.acm.org/doi/epdf/10.1145/3770855.3817695)

[21/05/2026] [ICML Poster Is Data Shapley Not Better than Random in Data Selection? Ask NASH](https://icml.cc/virtual/2026/poster/60914) (ICML'26)

## Paper List

### Classification explanation

**🎯Data Granularity:** Dataset, Sample, Element

**🌐Data Modalities:** Tabular, Graph, Text, Time-Series, Multimodal, Synthetic, Streaming

**📊Model Transparency:** White-Box, Gray-Box, Black-Box

**🧩Reference Set Dependency:** Strong, Weak, Self

**⚖️Task:** Discriminative, Generative, Instruction Tuning, Task-Agnostic 

### 1. Cooperative Game-based Valuation

- [**Towards Efficient Data Valuation Based on the Shapley Value**](https://arxiv.org/abs/1902.10275) (AISTATS'19)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Profit allocation for federated learning**](https://hufudb.com/static/paper/2019/BigData2019_Profit%20Allocation%20for%20Federated%20Learning.pdf) (BigData'19)

  🎯Dataset  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Efficient Task-Specific Data Valuation for Nearest Neighbor Algorithms**](https://arxiv.org/abs/1908.08619) (VLDB'19)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**An empirical and comparative analysis of data valuation with scalable algorithms**](https://arxiv.org/abs/1911.07128v1) (OpenReview'19)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data shapley: Equitable valuation of data for machine learning**](https://arxiv.org/abs/1904.02868) (ICML'19)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**A distributional framework for data valuation**](https://arxiv.org/abs/2002.12334) (ICML'20)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**A principled approach to data valuation for federated learning**](https://arxiv.org/abs/2009.06192) (FLPI'20)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Who's responsible? jointly quantifying the contribution of the learning algorithm and data**](https://arxiv.org/abs/1910.04214) (AAAI'21)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Efficient computation and analysis of distributional shapley values**](https://arxiv.org/abs/2007.01357) (AISTATS'21)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Graphsvx: Shapley value explanations for graph neural networks**](https://arxiv.org/abs/2104.10482) (ECML'21)

  🎯Sample  🌐Graph  📊Black-Box  🧩Self  ⚖️Discriminative

- [**If you like shapley then you’ll love the core**](https://par.nsf.gov/servlets/purl/10250701) (AAAI'21)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Energy-Based Learning for Cooperative Games, with Applications to Valuation Problems in Machine Learning**](https://arxiv.org/abs/2106.02938) (ICLR'21)

  🎯All  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Beta Shapley: a Unified and Noise-reduced Data Valuation Framework for Machine Learning**](https://proceedings.mlr.press/v151/kwon22a/kwon22a.pdf) (AISTATS'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Weak  ⚖️Discriminative

- [**Improving fairness for data valuation in horizontal federated learning**](https://ieeexplore.ieee.org/abstract/document/9835382) (ICDE'22)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**CS-Shapley: class-wise Shapley values for data valuation in classification**](https://arxiv.org/abs/2211.06800) (NeurIPS'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Gtg-shapley: Efficient and accurate participant contribution evaluation in federated learning**](https://arxiv.org/abs/2109.02053) (TIST'22)

  🎯Dataset  🌐Tabular  📊Gray-Box  🧩Strong  ⚖️Discriminative

- [**Differentially private Shapley values for data evaluation**](https://arxiv.org/abs/2206.00511) (arXiv'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Robust data valuation via variance reduced data shapley**](https://arxiv.org/abs/2210.16835v2) (arXiv'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Weightedshap: analyzing and improving shapley based feature attributions**](https://arxiv.org/abs/2209.13429) (NeurIPS'22)

  🎯Element  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**2D-shapley: A framework for fragmented data valuation**](https://arxiv.org/abs/2306.10473) (ICML'23)

  🎯Element  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data banzhaf: A robust data valuation framework for machine learning**](https://arxiv.org/abs/2205.15466) (AISTATS'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Weak  ⚖️Discriminative

- [**Accelerated shapley value approximation for data evaluation**](https://arxiv.org/abs/2311.05346) (arXiv'23)

  🎯Sample  🌐Tabular  📊Black-Box 🧩Strong  ⚖️Discriminative

- [**Poster: Verifiable data valuation with strong fairness in horizontal federated learning**](https://dl.acm.org/doi/10.1145/3576915.3624402) (CCS'23)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data valuation: The partial ordinal Shapley value for machine learning**](https://arxiv.org/abs/2305.01660) (arXiv'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Optimizing Data Shapley Interaction Calculation from O (2^ n) to O (tn^ 2) for KNN models**](https://arxiv.org/abs/2304.01224) (arXiv'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Threshold KNN-Shapley: A Linear-Time and Privacy-Friendly Approach to Data Valuation (Workshop Version)**](https://arxiv.org/abs/2308.15709) (NeurIPS'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data selection for fine-tuning large language models using transferred shapley values**](https://arxiv.org/abs/2306.10165) (ACL'23)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Discriminative

- [**CHG Shapley: Efficient Data Valuation and Selection towards Trustworthy Machine Learning**](https://arxiv.org/abs/2406.11730) (arXiv'24)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**On the inflation of knn-shapley value**](https://arxiv.org/abs/2405.17489) (arXiv'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data value estimation on private gradients**](https://arxiv.org/abs/2412.17008) (arXiv'24)

  🎯All  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Du-shapley: A shapley value proxy for efficient dataset valuation**](https://arxiv.org/abs/2306.02071) (NeurIPS'24)

  🎯Dataset 🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Explaining graph neural networks via structure-aware interaction index**](https://arxiv.org/abs/2405.14352) (ICML'24)

  🎯Sample  🌐Graph  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**NESTLE: An Efficient and Robust Data Valuation Framework for Large Language Models**](https://openreview.net/pdf?id=qk6AxjhFVR) (OpenReview'24)

  🎯Dataset  🌐Text  📊Black-Box  🧩Strong  ⚖️Generative

- [**P-Shapley: Shapley Values on Probabilistic Classifiers.**](https://www.vldb.org/pvldb/vol17/p1737-liu.pdf) (VLDB'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Rethinking data shapley for data selection tasks: misleads and merits**](https://arxiv.org/abs/2405.03875) (ICML'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Efficient data shapley for weighted nearest neighbor algorithms**](https://arxiv.org/abs/2401.11103) (AISTATS'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Rewarding the Rare: Maverick-Aware Shapley Valuation in Federated Learning**](https://openreview.net/pdf?id=JtybGfTUdq) (TMLR'25)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Efficient shapley-based data valuation for federated trajectories**](https://link.springer.com/article/10.1007/s11704-025-51020-9) (Frontiers of Computer Science'25)

  🎯Dataset  🌐Time-Series  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Exact Computation of Any-Order Shapley Interactions for Graph Neural Networks**](https://arxiv.org/abs/2501.16944) (ICLR'25)

  🎯Sample  🌐Graph  📊Gray-Box  🧩Self  ⚖️Discriminative

- [**Heterogeneous Graph Data Valuation: A Shapley Value-based Approach**](https://ieeexplore.ieee.org/document/11150137) (YAC'25)

  🎯Sample  🌐Graph  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Efficient data valuation approximation in federated learning: A sampling-based approach**](https://ieeexplore.ieee.org/document/11112901) (ICDE'25)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data shapley In One Training Run**](https://arxiv.org/abs/2406.11011) (ICLR'25)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Rethinking Data Value: Asymmetric Data Shapley for Structure-Aware Valuation in Data Markets and Machine Learning Pipelines**](https://arxiv.org/abs/2511.12863) (arXiv'25)

  🎯Dataset  🌐Text  📊Black-Box  🧩Strong  ⚖️Instruction Tuning

- [**Precedence-Constrained Winter Value for Effective Graph Data Valuation**](https://arxiv.org/abs/2402.01943) (ICLR'25)

  🎯Sample  🌐Graph  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**ShapG: new feature importance method based on the Shapley value**](https://arxiv.org/abs/2407.00506) (EAAI'25)

  🎯Element  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**The surprising amount of arbitrariness in shapley-value data valuation**](https://iclr.cc/virtual/2025/34475) (ICLR'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data Pricing for Graph Neural Networks without Pre-purchased Inspection**](https://arxiv.org/abs/2502.08284) (AAMAS'25)

  🎯Dataset  🌐Graph  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Localized Data Shapley: Accelerating Valuation for Nearest Neighbor Algorithms**](https://proceedings.neurips.cc/paper_files/paper/2025/hash/36ad3d922ec61116f2503f5851e07951-Abstract-Conference.html) (NeurIPS'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**TokenShapley: Token Level Context Attribution with Shapley Value**](https://arxiv.org/abs/2507.05261) (ACL'25)

  🎯Element  🌐Text  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Data Overvaluation Attack and Truthful Data Valuation in Federated Learning**](https://www.sciencestack.ai/paper/2502.00494) (arXiv'25)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**On the Impact of the Utility in Semivalue-based Data Valuation**](https://arxiv.org/abs/2502.06574) (arXiv'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Shapley-Based Data Valuation for Weighted $ k $-Nearest Neighbors**](https://papers.neurips.cc/paper_files/paper/2025/hash/4537592f9594a0522da99566b90380cc-Abstract-Conference.html) (NeurIPS'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Uncertainty-Aware Multimodal Learning via Conformal Shapley Intervals**](https://arxiv.org/abs/2602.00171) (arXiv'26)

  🎯Element  🌐Multimodal  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**From points to coalitions: hierarchical contrastive shapley values for prioritizing data samples**](https://arxiv.org/abs/2512.19363) (AAAI'26)

  🎯Sample  🌐Streaming  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Local Shapley: Model-Induced Locality and Optimal Reuse in Data Valuation**](https://arxiv.org/abs/2603.03672) (arXiv'26)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**An Odd Estimator for Shapley Values**](https://arxiv.org/abs/2602.01399) (arXiv'26)

  🎯Other  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Priority-Aware Shapley Value**](https://arxiv.org/abs/2602.09326v1) (arXiv'26)

  🎯All  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Challenges in Enabling Private Data Valuation**](https://arxiv.org/abs/2603.00342) (arXiv'26)

  🎯Sample  🌐Tabular  📊All  🧩Strong  ⚖️Discriminative

- [**Shapley Value on Uncertain Data**](https://arxiv.org/abs/2601.14543) (arXiv'26)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

### 2. Gradient-based Valuation

- [**Understanding black-box predictions via influence functions**](https://arxiv.org/abs/1703.04730) (ICML'17)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Finding influential training samples for gradient boosted decision trees**](https://arxiv.org/abs/1802.06640) (ICML'18)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**On the accuracy of influence functions for measuring group effects**](https://arxiv.org/abs/1905.13289) (NeurIPS'19)

  🎯Dataset  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Estimating training data influence by tracing gradient descent**](https://arxiv.org/abs/2002.08484) (NeurIPS'20)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Influence Estimation for Generative Adversarial Networks**](https://arxiv.org/abs/2101.08367) (ICLR'21)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Generative

- [**Make every example count: On the stability and utility of self-influence for learning from noisy NLP datasets**](https://aclanthology.org/2023.emnlp-main.625/) (EMNLP'23)

  🎯Sample  🌐Text  📊White-Box  🧩Self  ⚖️Generative

- [**Gex: A flexible method for approximating influence via geometric ensemble**](https://papers.nips.cc/paper_files/paper/2023/hash/1297ca5c906f4bada8f5f6f4e80f9dd2-Abstract-Conference.html) (NeurIPS'23)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Characterizing the influence of graph elements**](https://arxiv.org/abs/2210.07441) (ICLR'23)

  🎯Element  🌐Graph  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Studying large language model generalization with influence functions**](https://arxiv.org/abs/2308.03296) (arXiv'23)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Self-influence guided data reweighting for language model pre-training**](https://arxiv.org/abs/2311.00913) (EMNLP'23)

  🎯Sample  🌐Text  📊White-Box  🧩Self  ⚖️Discriminative

- [**Rge: A repulsive graph rectification for node classification via influence**](https://proceedings.mlr.press/v202/song23f.html) (ICML'23)

  🎯Element  🌐Graph  📊White-Box  🧩Strong  ⚖️Discriminative

- [**TRAK: attributing model behavior at scale**](https://arxiv.org/abs/2303.14186) (ICML'23)

  🎯Sample  🌐Tabular / Text  📊White-Box  🧩Strong  ⚖️Discriminative

- [**CoAst: Validation-Free Contribution Assessment for Federated Learning based on Cross-Round Valuation**](https://dl.acm.org/doi/abs/10.1145/3664647.3680867) (ACM MM'24)

  🎯Dataset  🌐Tabular  📊White-Box  🧩Self  ⚖️Discriminative

- [**Intriguing properties of data attribution on diffusion models**](https://arxiv.org/abs/2311.00500) (ICLR'24)

  🎯Sample  🌐Multimodal  📊White-Box  🧩Strong  ⚖️Generative

- [**Data attribution for text-to-image models by unlearning synthesized images**](https://arxiv.org/abs/2406.09408) (NeurIPS'24)

  🎯Sample  🌐Multimodal  📊White-Box  🧩Strong  ⚖️Generative

- [**DataInf: Efficiently Estimating Data Influence in LoRA-tuned LLMs and Diffusion Models**](https://arxiv.org/abs/2310.00902) (ICLR'24)

  🎯Sample  🌐Text / Multimodal  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Revisit, extend, and enhance hessian-free influence functions**](https://arxiv.org/abs/2405.17490) (arXiv'24)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**LIA: Privacy-Preserving Data Quality Evaluation in Federated Learning Using a Lazy Influence Approximation**](https://arxiv.org/abs/2205.11518) (IEEE BigData'24)

  🎯Dataset  🌐Tabular  📊Gray-Box  🧩Strong  ⚖️Discriminative

- [**LESS: Selecting Influential Data for Targeted Instruction Tuning**](https://arxiv.org/abs/2402.04333) (ICML'24)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Instruction Tuning

- [**Token-wise Influential Training Data Retrieval for Large Language Models**](https://arxiv.org/abs/2405.11724) (ACL'24)

  🎯Element  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Do Influence Functions Work on Large Language Models?**](https://arxiv.org/abs/2409.19998) (arXiv'24)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Instruction Tuning

- [**Training Data Attribution via Approximate Unrolling**](https://arxiv.org/abs/2405.12186) (NeurIPS'24)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Alinfik: Learning to approximate linearized future influence kernel for scalable third-parity LLM data valuation**](https://arxiv.org/abs/2503.01052) (NAACL'25)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Better training data attribution via better inverse hessian-vector products**](https://arxiv.org/abs/2507.14740) (NeurIPS'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Bayesian Influence Functions for Hessian-Free Data Attribution**](https://arxiv.org/abs/2509.26544) (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Distributional Training Data Attribution: What do Influence Functions Sample?**](https://arxiv.org/abs/2506.12965) (NeurIPS'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Generative

- [**Daunce: Data attribution through uncertainty estimation**](https://arxiv.org/abs/2505.23223) (arXiv'25)

  🎯Sample  🌐Text  📊Black-Box  🧩Strong  ⚖️Instruction Tuning

- [**Diff-In: data influence estimation with differential approximation**](https://openreview.net/pdf?id=Jds4tiTo2a) (ICLR'25)

  🎯Sample  🌐Text / Multimodal  📊White-Box  🧩Strong  ⚖️Generative

- [**Influence Functions for Scalable Data Attribution in Diffusion Models**](https://proceedings.iclr.cc/paper_files/paper/2025/hash/804dbf8d3b8eee1ef875c6857efc64eb-Abstract-Conference.html) (ICLR'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Generative

- [**Adaptive Data Selection for Multi-Layer Perceptron Training: A Sub-linear Value-Driven Method**](https://arxiv.org/abs/2510.21286) (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Influence Functions for Edge Edits in Non-Convex Graph Neural Networks**](https://arxiv.org/abs/2506.04694) (NeurIPS'25)

  🎯Element  🌐Graph  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Final-Model-Only Data Attribution with a Unifying View of Gradient-Based Methods**](https://arxiv.org/abs/2412.03906) (NeurIPS'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**If-guide: Influence function-guided detoxification of llms**](https://arxiv.org/abs/2506.01790) (NeurIPS'25)

  🎯Element  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Revisiting data attribution for influence functions**](https://arxiv.org/pdf/2508.07297) (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Efficient data selection at scale via influence distillation**](https://arxiv.org/abs/2505.19051) (NeurIPS'25)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Instruction Tuning

- [**Which Data Attributes Stimulate Math and Code Reasoning? An Investigation via Influence Functions**](https://arxiv.org/abs/2505.19949) (NeurIPS'25)

  🎯Element  🌐Text  📊White-Box  🧩Strong  ⚖️Instruction Tuning

- [**Influence functions for efficient data selection in reasoning**](https://arxiv.org/abs/2510.06108) (arXiv'25)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Instruction Tuning

- [**Kernel von Mises Formula of the Influence Function**](https://papers.neurips.cc/paper_files/paper/2025/file/0dde49ec491174a11272c5e1e6013f9f-Paper-Conference.pdf) (NeurIPS'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Layer-Aware Influence for Online Data Valuation Estimation**](https://arxiv.org/abs/2510.16007) (arXiv'25)

  🎯Sample  🌐Tabular / Text  📊White-Box  🧩Self  ⚖️Generative

- [**LayerIF: Estimating Layer Quality for Large Language Models using Influence Functions**](https://arxiv.org/abs/2505.23811) (NeurIPS'25)

  🎯Element  🌐Text  📊Gray-Box  🧩Strong  ⚖️N / A

- [**LimaCost: Data Valuation for Instruction Tuning of Large Language Models**](https://aclanthology.org/2025.findings-emnlp.688/) (EMNLP'25)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Instruction Tuning

- [**What is Your Data Worth to GPT? LLM-Scale Data Valuation with Influence Functions**](https://arxiv.org/abs/2405.13954) (NeurIPS'25)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Towards understanding valuable preference data for large language model alignment**](https://arxiv.org/abs/2510.13212) (arXiv'25)

  🎯Sample  🌐Text  📊White-Box  🧩Weak  ⚖️Instruction Tuning

- [**Lightweight Time Series Data Valuation on Time Series Foundation Models via In-Context Finetuning**](https://arxiv.org/abs/2511.11648) (arXiv'25)

  🎯Sample  🌐Time-Series  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Magic: Near-optimal data attribution for deep learning**](https://arxiv.org/abs/2504.16430) (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**First is Not Really Better Than Last: Evaluating Layer Choice and Aggregation Strategies in Language Model Data Influence Estimation**](https://arxiv.org/abs/2511.04715) (arXiv'25)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Rescaled Influence Functions: Accurate Data Attribution in High Dimension**](https://arxiv.org/abs/2506.06656) (NeurIPS'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Scalable Data Attribution via Forward-Only Test-Time Inference**](https://arxiv.org/abs/2511.19803) (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Capturing the Temporal Dependence of Training Data Influence**](https://openreview.net/pdf?id=uHLgDEgiS5) (ICLR'25)

  🎯Sample  🌐Tabular / Text  📊White-Box  🧩Strong  ⚖️Discriminative

- [**TimeInf: Time Series Data Contribution via Influence Functions**](https://arxiv.org/abs/2407.15247) (ICLR'25)

  🎯Element  🌐Time-Series  📊White-Box  🧩Weak  ⚖️Discriminative

- [**Z0-Inf: Zeroth Order Approximation for Data Influence**](https://arxiv.org/abs/2510.11832) (arXiv'25)

  🎯Sample  🌐Text  📊Gray-Box  🧩Self  ⚖️Discriminative

- [**A Versatile Influence Function for Data Attribution with Non-Decomposable Loss**](https://openreview.net/pdf?id=p85TNN62KD) (ICML'25)

  🎯Sample  🌐Tabular / Graph  📊White-Box  🧩Strong  ⚖️Discriminative

- [**LoRIF: Low-Rank Influence Functions for Scalable Training Data Attribution**](https://arxiv.org/abs/2601.21929) (arXiv'26)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Instruction Tuning

### 3. Utility Learning and Bilevel Optimization

- [**Data Valuation using Reinforcement Learning**](https://arxiv.org/abs/1909.11671) (ICML'20)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Efficient Client Contribution Evaluation for Horizontal Federated Learning**](https://arxiv.org/abs/2102.13314) (ICASSP'21)

  🎯Dataset  🌐Tabular  📊Gray-Box  🧩Strong  ⚖️Discriminative

- [**Learnability of Learning Performance and Its Application to Data Valuation**](https://arxiv.org/abs/2107.06336v1) (arXiv'21)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Measuring the Effect of Training Data on Deep Learning Predictions via Randomized Experiments**](https://arxiv.org/abs/2206.10013) (ICML'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Datamodels: Predicting Predictions from Training Data**](https://arxiv.org/abs/2202.00622) (ICML'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data-OOB: Out-of-bag Estimate as a Simple and Efficient Data Value**](https://arxiv.org/abs/2304.07718) (ICML'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Training Data Attribution for Diffusion Models**](https://arxiv.org/abs/2306.02174) (arXiv'23)

  🎯Sample  🌐Synthetic  📊White-Box  🧩Self  ⚖️Generative

- [**EcoVal: An Efficient Data Valuation Framework for Machine Learning**](https://arxiv.org/abs/2402.09288) (KDD'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data Valuation by Leveraging Global and Local Statistical Information**](https://www.aminer.cn/pub/66568c4501d2a3fbfc27b55a/data-valuation-by-leveraging-global-and-local-statistical-information) (arXiv'24)

  🎯Sample  🌐Streaming  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**LossVal: Efficient Data Valuation for Neural Networks**](https://arxiv.org/abs/2412.04158) (arXiv'24)

  🎯Sample  🌐Tabular  📊White-Box  🧩Self  ⚖️Discriminative

- [**Is Data Valuation Learnable and Interpretable?**](https://arxiv.org/abs/2406.02612) (arXiv'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Scaling Laws for the Value of Individual Data Points in Machine Learning**](https://www.semanticscholar.org/paper/Scaling-Laws-for-the-Value-of-Individual-Data-in-Covert-Ji/da363589a39d5932ac625365c40654e0045fd88b) (ICML'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Stochastic Amortization: A Unified Approach to Accelerate Feature and Data Attribution**](https://arxiv.org/abs/2401.15866) (NeurIPS'24)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Region-Level Data Attribution for Text-to-Image Generative Models**](https://openaccess.thecvf.com/content/ICCV2025/papers/Nguyen_Region-Level_Data_Attribution_for_Text-to-Image_Generative_Models_ICCV_2025_paper.pdf) (ICCV'25)

  🎯Element  🌐Multimodal  📊Black-Box  🧩Strong  ⚖️Generative

- [**Beyond Models Explainable Data Valuation and Metric Adaption for Recommendation**](https://arxiv.org/abs/2502.08685) (SDM'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Fast Data Attribution for Text-to-Image Models**](https://arxiv.org/abs/2511.10721) (arXiv'25)

  🎯Sample  🌐Multimodal  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Efficient Forward-Only Data Valuation for Pretrained LLMs and VLMs**](https://www.semanticscholar.org/paper/Efficient-Forward-Only-Data-Valuation-for-LLMs-and-Deng-Zhang/a1d909eb3c0406dec6574065f11cf274ebc99840) (arXiv'25)

  🎯Sample  🌐Multimodal  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Data-Efficient Pretraining with Group-Level Data Influence Modeling**](https://arxiv.org/html/2502.14709) (arXiv'25)

  🎯Dataset  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Error Estimate and Convergence Analysis for Data Valuation**](https://arxiv.org/abs/2511.06463) (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Neural Networks for Learnable and Scalable Influence Estimation of Instruction Fine-Tuning Data**](https://arxiv.org/abs/2502.09969) (arXiv'25)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Instruction Tuning

- [**Shapley-Guided Utility Learning for Effective Graph Inference Data Valuation**](https://arxiv.org/abs/2503.18195) (ICLR'25)

  🎯Element  🌐Graph  📊Black-Box  🧩Self  ⚖️Discriminative

- [**TSRating: Rating Quality of Diverse Time Series Data by Meta-learning from LLM Judgment**](https://arxiv.org/abs/2506.01290) (arXiv'25)

  🎯Sample  🌐Time-Series  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Fast-DataShapley: Neural Modeling for Training Data Valuation**](https://arxiv.org/abs/2506.05281) (WSDM'26)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Influence-Preserving Proxies for Gradient-Based Data Selection in LLM Fine-tuning**](https://openreview.net/forum?id=PDNpRLxDlI) (arXiv'26)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Instruction Tuning

### 4. Model-agnostic Valuation

- [**Validation Free and Replication Robust Volume-based Data Valuation**](https://proceedings.neurips.cc/paper/2021/hash/59a3adea76fadcb6dd9e54c96fc155d1-Abstract.html) (NeurIPS'21)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Self  ⚖️Task-Agnostic

- [**Incentivizing Collaboration in Machine Learning via Synthetic Data Rewards**](https://arxiv.org/abs/2112.09327) (AAAI'22)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Generative

- [**DAVINZ: Data Valuation using Deep Neural Networks at Initialization**](https://github.com/ZhaoxuanWu/DAVINZ-DataValuation) (ICML'22)

  🎯Dataset  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Data Valuation Without Training of a Model**](https://openreview.net/forum?id=XIzO8zr-WbM) (ICLR'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**LAVA: Data Valuation without Pre-Specified Learning Algorithms**](https://github.com/reds-lab/LAVA) (ICLR'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Task-Agnostic

- [**Fundamentals of Task-Agnostic Data Valuation**](https://arxiv.org/abs/2208.12354) (AAAI'23)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Self  ⚖️Task-Agnostic

- [**Data Valuation in the Absence of a Reliable Validation Set**](https://openreview.net/pdf?id=xBORyL316c) (TMLR'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Data Valuation and Detections in Federated Learning**](https://arxiv.org/abs/2311.05304) (CVPR'24)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Proper Dataset Valuation by Pointwise Mutual Information**](https://arxiv.org/abs/2405.18253) (arXiv'24)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Self  ⚖️Task-Agnostic

- [**Data Valuation and Selection in a Federated Model Marketplace**](https://arxiv.org/abs/2509.18104) (arXiv'25)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Eigen-Value: Efficient Domain-Robust Data Valuation via Eigenvalue-Based Approach**](https://arxiv.org/abs/2510.23409) (arXiv'25)

  🎯Sample 🌐Tabular 📊Gray-Box 🧩Self ⚖️Discriminative

- [**Data Value in the Age of Scaling: Understanding LLM Scaling Dynamics Under Real-Synthetic Data Mixtures**](https://arxiv.org/abs/2511.13640v1) (arXiv'25)

  🎯Dataset  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Fortifying Federated Learning Towards Trustworthiness via Auditable Data Valuation and Verifiable Client Contribution**](https://ieeexplore.ieee.org/document/11093960) (CVPR'25)

  🎯Dataset  🌐Tabular  📊Gray-Box  🧩Self  ⚖️Discriminative

- [**Geometric Data Valuation via Leverage Scores**](https://arxiv.org/abs/2511.02100v1) (arXiv'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Self  ⚖️Task-Agnostic

- [**GMValuator: Similarity-based Data Valuation for Generative Models**](https://arxiv.org/abs/2304.10701) (ICLR'25)

  🎯Sample  🌐Synthetic  📊Black-Box  🧩Self  ⚖️Generative

- [**KAIROS: Scalable Model-Agnostic Data Valuation**](https://arxiv.org/abs/2506.23799) (NeurIPS'25)

  🎯Sample  🌐Streaming  📊Black-Box  🧩Strong  ⚖️Task-Agnostic

- [**SAVA: Scalable Learning-Agnostic Data Valuation**](https://openreview.net/pdf?id=0UCoWxPhQ4) (ICLR'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Task-Agnostic

- [**Privacy-Preserving Feature Valuation in Vertical Federated Learning Using Shapley-CMI and PSI Permutation**](https://arxiv.org/abs/2512.14767) (arXiv'25)

  🎯Element  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Data Valuation for Vertical Federated Learning: A Model-Free and Privacy-Preserving Method**](https://arxiv.org/abs/2112.08364) (MISQ'26)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**TimeLAVA: Learning-Agnostic Valuation for Time Series Data**](https://icml.cc/virtual/2026/poster/62497) (ICML'26)

  🎯Element  🌐Time-Series  📊Black-Box  🧩Strong  ⚖️Task-Agnostic

### 5. Other Related Methods

- [**The Value of Out-of-Distribution Data**](https://arxiv.org/abs/2208.10967) (ICML'23)

  🎯Dataset  🌐Tabular  📊White-Box  🧩Weak  ⚖️Discriminative

- [**In-context probing approximates influence function for data valuation**](https://arxiv.org/html/2407.12259v1) (arXiv'24)

  🎯Sample  🌐Text  📊Black-Box  🧩Strong  ⚖️Instruction Tuning

- [**Diffusion Attribution Score: Evaluating Training Data Influence in Diffusion Models**](https://arxiv.org/abs/2410.18639) (ICLR'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Generative

- [**Data Valuation for LLM Fine-Tuning: Efficient Shapley Value Approximation via Language Model Arithmetic**](https://arxiv.org/abs/2512.15765) (arXiv'25)

  🎯Dataset  🌐Text  📊Gray-Box  🧩Strong  ⚖️Instruction Tuning

- [**Beyond Uniform Deletion: A Data Value-Weighted Framework for Certified Machine Unlearning**](https://arxiv.org/abs/2511.06794) (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Do Data Valuations Make Good Data Prices?**](https://arxiv.org/abs/2511.06794) (arXiv'25)

  🎯Dataset  🌐Text  📊Black-Box  🧩Strong  ⚖️Generative

- [**Fairshare Data Pricing via Data Valuation for Large Language Models**](https://arxiv.org/abs/2502.00198) (NeurIPS'25)

  🎯Dataset  🌐Text  📊Black-Box  🧩Strong  ⚖️Instruction Tuning

- [**Mixture-ofscores: Robust image-text data quality score via three lines of code**](https://openaccess.thecvf.com/content/ICCV2025/papers/Wu_Mixture-of-Scores_Robust_Image-Text_Data_Valuation_via_Three_Lines_of_Code_ICCV_2025_paper.pdf) (ICCV'25)

  🎯Sample  🌐Multimodal  📊Black-Box  🧩Self  ⚖️Generative

- [**From Fairness to Truthfulness: Rethinking Data Valuation Design**](https://arxiv.org/html/2504.05563v1) (ICLR'25)

  🎯Dataset  🌐Text  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Importance-aware data selection for efficient llm instruction tuning**](https://arxiv.org/abs/2511.07074) (AAAI'26)

  🎯Sample  🌐Text  📊Black-Box  🧩Self  ⚖️Instruction Tuning



## Contribution

We welcome contributions to enhance the breadth and depth of this repository. If you have a paper related to data valuation that you believe should be included, please feel free to submit a pull request. Together, we can build a valuable resource for the data valuation community.

```Text
| conference/journal'year | [paper_name](paper_link) | [[code]](code_link) |
```

## Contact

For any inquiries or suggestions regarding this repository, please don't hesitate to contact us by opening an issue on this repository.  

Thank you for your interest in the Data Valuation Papers Repository. We hope you find it valuable for your research and exploration. If you find this repository to be useful, please cite our survey paper.

```Text
@article{XXXXX,
  title={Data Valuation in Machine Learning: Methods, Systems, and Open Challenges},
  author={xxxxxx},
  journal={XXXXXX},
  year={2026},
}
```



