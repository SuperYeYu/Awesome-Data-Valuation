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

[21/05/2026] [Is Data Shapley Not Better than Random in Data Selection? Ask NASH]([ICML Poster Is Data Shapley Not Better than Random in Data Selection? Ask NASH](https://icml.cc/virtual/2026/poster/60914)) (ICML'26)

## Paper List

### Classification explanation

**🎯Data Granularity:** Dataset, Sample, Element

**🌐Data Modalities:** Tabular, Graph, Text, Time-Series, Multimodal, Synthetic, Streaming

**📊Model Transparency:** White-Box, Gray-Box, Black-Box

**🧩Reference Set Dependency:** Strong, Weak, Self

**⚖️Task:** Discriminative, Generative, Instruction Tuning , Task-Agnostic 

### 1. Cooperative Game-based Valuation

- [**Towards Efficient Data Valuation Based on the Shapley Value**]() (AISTATS'19)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Profit allocation for federated learning**]() (BigData'19)

  🎯Dataset  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Efficient Task-Specific Data Valuation for Nearest Neighbor Algorithms**]() (VLDB'19)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**An empirical and comparative analysis of data valuation with scalable algorithms**]() (OpenReview'19)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data shapley: Equitable valuation of data for machine learning**]() (ICML'19)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**A distributional framework for data valuation**]() (ICML'20)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**A principled approach to data valuation for federated learning**]() (FLPI'20)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Who's responsible? jointly quantifying the contribution of the learning algorithm and data**]() (AAAI'21)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Efficient computation and analysis of distributional shapley values**]() (AISTATS'21)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Graphsvx: Shapley value explanations for graph neural networks**]() (ECML'21)

  🎯Sample  🌐Graph  📊Black-Box  🧩Self  ⚖️Discriminative

- [**If you like shapley then you’ll love the core**]() (AAAI'21)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Energy-Based Learning for Cooperative Games, with Applications to Valuation Problems in Machine Learning**]() (ICLR'21)

  🎯All  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Beta Shapley: a Unified and Noise-reduced Data Valuation Framework for Machine Learning**]() (AISTATS'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Weak  ⚖️Discriminative

- [**Improving fairness for data valuation in horizontal federated learning**]() (ICDE'22)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**CS-Shapley: class-wise Shapley values for data valuation in classification**]() (NeurIPS'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Gtg-shapley: Efficient and accurate participant contribution evaluation in federated learning**]() (TIST'22)

  🎯Dataset  🌐Tabular  📊Gray-Box  🧩Strong  ⚖️Discriminative

- [**Differentially private Shapley values for data evaluation**]() (arXiv'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Robust data valuation via variance reduced data shapley**]() (arXiv'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Weightedshap: analyzing and improving shapley based feature attributions**]() (NeurIPS'22)

  🎯Element  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**2D-shapley: A framework for fragmented data valuation**]() (ICML'23)

  🎯Element  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data banzhaf: A robust data valuation framework for machine learning**]() (AISTATS'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Weak  ⚖️Discriminative

- [**Accelerated shapley value approximation for data evaluation**]() (arXiv'23)

  🎯Sample  🌐Tabular  📊Black-Box 🧩Strong  ⚖️Discriminative

- [**Poster: Verifiable data valuation with strong fairness in horizontal federated learning**]() (CCS'23)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data valuation: The partial ordinal Shapley value for machine learning**]() (arXiv'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Optimizing Data Shapley Interaction Calculation from O (2^ n) to O (tn^ 2) for KNN models**]() (arXiv'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Threshold KNN-Shapley: A Linear-Time and Privacy-Friendly Approach to Data Valuation (Workshop Version)**]() (NeurIPS'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data selection for fine-tuning large language models using transferred shapley values**]() (ACL'23)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Discriminative

- [**CHG Shapley: Efficient Data Valuation and Selection towards Trustworthy Machine Learning**]() (arXiv'24)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**On the inflation of knn-shapley value**]() (arXiv'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data value estimation on private gradients**]() (arXiv'24)

  🎯All  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Du-shapley: A shapley value proxy for efficient dataset valuation**]() (NeurIPS'24)

  🎯Dataset 🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Explaining graph neural networks via structure-aware interaction index**]() (ICML'24)

  🎯Sample  🌐Graph  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**NESTLE: An Efficient and Robust Data Valuation Framework for Large Language Models**]() (OpenReview'24)

  🎯Dataset  🌐Text  📊Black-Box  🧩Strong  ⚖️Generative

- [**P-Shapley: Shapley Values on Probabilistic Classifiers.**]() (VLDB'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Rethinking data shapley for data selection tasks: misleads and merits**]() (ICML'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Efficient data shapley for weighted nearest neighbor algorithms**]() (AISTATS'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Rewarding the Rare: Maverick-Aware Shapley Valuation in Federated Learning**]() (TMLR'25)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Efficient shapley-based data valuation for federated trajectories**]() (Frontiers of Computer Science'25)

  🎯Dataset  🌐Time-Series  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Exact Computation of Any-Order Shapley Interactions for Graph Neural Networks**]() (ICLR'25)

  🎯Sample  🌐Graph  📊Gray-Box  🧩Self  ⚖️Discriminative

- [**Heterogeneous Graph Data Valuation: A Shapley Value-based Approach**]() (YAC'25)

  🎯Sample  🌐Graph  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Efficient data valuation approximation in federated learning: A sampling-based approach**]() (ICDE'25)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data shapley In One Training Run**]() (ICLR'25)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Rethinking Data Value: Asymmetric Data Shapley for Structure-Aware Valuation in Data Markets and Machine Learning Pipelines**]() (arXiv'25)

  🎯Dataset  🌐Text  📊Black-Box  🧩Strong  ⚖️Instruction Tuning

- [**Precedence-Constrained Winter Value for Effective Graph Data Valuation**]() (ICLR'25)

  🎯Sample  🌐Graph  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**ShapG: new feature importance method based on the Shapley value**]() (EAAI'25)

  🎯Element  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**The surprising amount of arbitrariness in shapley-value data valuation**]() (ICLR'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data Pricing for Graph Neural Networks without Pre-purchased Inspection**]() (AAMAS'25)

  🎯Dataset  🌐Graph  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Localized Data Shapley: Accelerating Valuation for Nearest Neighbor Algorithms**]() (NeurIPS'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**TokenShapley: Token Level Context Attribution with Shapley Value**]() (ACL'25)

  🎯Element  🌐Text  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Data Overvaluation Attack and Truthful Data Valuation in Federated Learning**]() (arXiv'25)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**On the Impact of the Utility in Semivalue-based Data Valuation**]() (arXiv'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Shapley-Based Data Valuation for Weighted $ k $-Nearest Neighbors**]() (NeurIPS'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Uncertainty-Aware Multimodal Learning via Conformal Shapley Intervals**]() (arXiv'26)

  🎯Element  🌐Multimodal  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**From points to coalitions: hierarchical contrastive shapley values for prioritizing data samples**]() (AAAI'26)

  🎯Sample  🌐Streaming  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Local Shapley: Model-Induced Locality and Optimal Reuse in Data Valuation**]() (arXiv'26)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**An Odd Estimator for Shapley Values**]() (arXiv'26)

  🎯Other  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Priority-Aware Shapley Value**]() (arXiv'26)

  🎯All  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Challenges in Enabling Private Data Valuation**]() (arXiv'26)

  🎯Sample  🌐Tabular  📊All  🧩Strong  ⚖️Discriminative

- [**Shapley Value on Uncertain Data**]() (arXiv'26)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

### 2. Gradient-based Valuation

- [**Understanding black-box predictions via influence functions**]() (ICML'17)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Finding influential training samples for gradient boosted decision trees**]() (ICML'18)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**On the accuracy of influence functions for measuring group effects**]() (NeurIPS'19)

  🎯Dataset  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Estimating training data influence by tracing gradient descent**]() (NeurIPS'20)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Influence Estimation for Generative Adversarial Networks**]() (ICLR'21)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Generative

- [**Make every example count: On the stability and utility of self-influence for learning from noisy NLP datasets**]() (EMNLP'23)

  🎯Sample  🌐Text  📊White-Box  🧩Self  ⚖️Generative

- [**Gex: A flexible method for approximating influence via geometric ensemble**]() (NeurIPS'23)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Characterizing the influence of graph elements**]() (ICLR'23)

  🎯Element  🌐Graph  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Studying large language model generalization with influence functions**]() (arXiv'23)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Self-influence guided data reweighting for language model pre-training**]() (EMNLP'23)

  🎯Sample  🌐Text  📊White-Box  🧩Self  ⚖️Discriminative

- [**Rge: A repulsive graph rectification for node classification via influence**]() (ICML'23)

  🎯Element  🌐Graph  📊White-Box  🧩Strong  ⚖️Discriminative

- [**TRAK: attributing model behavior at scale**]() (ICML'23)

  🎯Sample  🌐Tabular / Text  📊White-Box  🧩Strong  ⚖️Discriminative

- [**CoAst: Validation-Free Contribution Assessment for Federated Learning based on Cross-Round Valuation**]() (ACM MM'24)

  🎯Dataset  🌐Tabular  📊White-Box  🧩Self  ⚖️Discriminative

- [**Intriguing properties of data attribution on diffusion models**]() (ICLR'24)

  🎯Sample  🌐Multimodal  📊White-Box  🧩Strong  ⚖️Generative

- [**Data attribution for text-to-image models by unlearning synthesized images**]() (NeurIPS'24)

  🎯Sample  🌐Multimodal  📊White-Box  🧩Strong  ⚖️Generative

- [**DataInf: Efficiently Estimating Data Influence in LoRA-tuned LLMs and Diffusion Models**]() (ICLR'24)

  🎯Sample  🌐Text / Multimodal  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Revisit, extend, and enhance hessian-free influence functions**]() (arXiv'24)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**LIA: Privacy-Preserving Data Quality Evaluation in Federated Learning Using a Lazy Influence Approximation**]() (IEEE BigData'24)

  🎯Dataset  🌐Tabular  📊Gray-Box  🧩Strong  ⚖️Discriminative

- [**LESS: Selecting Influential Data for Targeted Instruction Tuning**]() (ICML'24)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Instruction Tuning

- [**Token-wise Influential Training Data Retrieval for Large Language Models**]() (ACL'24)

  🎯Element  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Do Influence Functions Work on Large Language Models?**]() (arXiv'24)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Instruction Tuning

- [**Training Data Attribution via Approximate Unrolling**]() (NeurIPS'24)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Alinfik: Learning to approximate linearized future influence kernel for scalable third-parity LLM data valuation**]() (NAACL'25)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Better training data attribution via better inverse hessian-vector products**]() (NeurIPS'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Bayesian Influence Functions for Hessian-Free Data Attribution**]() (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Distributional Training Data Attribution: What do Influence Functions Sample?**]() (NeurIPS'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Generative

- [**Daunce: Data attribution through uncertainty estimation**]() (arXiv'25)

  🎯Sample  🌐Text  📊Black-Box  🧩Strong  ⚖️Instruction Tuning

- [**Diff-In: data influence estimation with differential approximation**]() (OpenReview'25)

  🎯Sample  🌐Text / Multimodal  📊White-Box  🧩Strong  ⚖️Generative

- [**Influence Functions for Scalable Data Attribution in Diffusion Models**]() (ICLR'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Generative

- [**Adaptive Data Selection for Multi-Layer Perceptron Training: A Sub-linear Value-Driven Method**]() (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Influence Functions for Edge Edits in Non-Convex Graph Neural Networks**]() (NeurIPS'25)

  🎯Element  🌐Graph  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Final-Model-Only Data Attribution with a Unifying View of Gradient-Based Methods**]() (NeurIPS'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**If-guide: Influence function-guided detoxification of llms**]() (NeurIPS'25)

  🎯Element  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Revisiting data attribution for influence functions**]() (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Efficient data selection at scale via influence distillation**]() (NeurIPS'25)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Instruction Tuning

- [**Which Data Attributes Stimulate Math and Code Reasoning? An Investigation via Influence Functions**]() (NeurIPS'25)

  🎯Element  🌐Text  📊White-Box  🧩Strong  ⚖️Instruction Tuning

- [**Influence functions for efficient data selection in reasoning**]() (arXiv'25)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Instruction Tuning

- [**Kernel von Mises Formula of the Influence Function**]() (NeurIPS'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Layer-Aware Influence for Online Data Valuation Estimation**]() (arXiv'25)

  🎯Sample  🌐Tabular / Text  📊White-Box  🧩Self  ⚖️Generative

- [**LayerIF: Estimating Layer Quality for Large Language Models using Influence Functions**]() (NeurIPS'25)

  🎯Element  🌐Text  📊Gray-Box  🧩Strong  ⚖️N / A

- [**LimaCost: Data Valuation for Instruction Tuning of Large Language Models**]() (EMNLP'25)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Instruction Tuning

- [**What is Your Data Worth to GPT? LLM-Scale Data Valuation with Influence Functions**]() (NeurIPS'25)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Towards understanding valuable preference data for large language model alignment**]() (arXiv'25)

  🎯Sample  🌐Text  📊White-Box  🧩Weak  ⚖️Instruction Tuning

- [**Lightweight Time Series Data Valuation on Time Series Foundation Models via In-Context Finetuning**]() (arXiv'25)

  🎯Sample  🌐Time-Series  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Magic: Near-optimal data attribution for deep learning**]() (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**First is Not Really Better Than Last: Evaluating Layer Choice and Aggregation Strategies in Language Model Data Influence Estimation**]() (arXiv'25)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Rescaled Influence Functions: Accurate Data Attribution in High Dimension**]() (NeurIPS'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Scalable Data Attribution via Forward-Only Test-Time Inference**]() (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Capturing the Temporal Dependence of Training Data Influence**]() (ICLR'25)

  🎯Sample  🌐Tabular / Text  📊White-Box  🧩Strong  ⚖️Discriminative

- [**TimeInf: Time Series Data Contribution via Influence Functions**]() (ICLR'25)

  🎯Element  🌐Time-Series  📊White-Box  🧩Weak  ⚖️Discriminative

- [**Z0-Inf: Zeroth Order Approximation for Data Influence**]() (arXiv'25)

  🎯Sample  🌐Text  📊Gray-Box  🧩Self  ⚖️Discriminative

- [**A Versatile Influence Function for Data Attribution with Non-Decomposable Loss**]() (ICML'25)

  🎯Sample  🌐Tabular / Graph  📊White-Box  🧩Strong  ⚖️Discriminative

- [**LoRIF: Low-Rank Influence Functions for Scalable Training Data Attribution**]() (arXiv'26)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Instruction Tuning

### 3. Utility Learning and Bilevel Optimization

- [**Data Valuation using Reinforcement Learning**]() (ICML'20)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Efficient Client Contribution Evaluation for Horizontal Federated Learning**]() (ICASSP'21)

  🎯Dataset  🌐Tabular  📊Gray-Box  🧩Strong  ⚖️Discriminative

- [**Learnability of Learning Performance and Its Application to Data Valuation**]() (arXiv'21)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Measuring the Effect of Training Data on Deep Learning Predictions via Randomized Experiments**]() (ICML'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Datamodels: Predicting Predictions from Training Data**]() (ICML'22)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data-OOB: Out-of-bag Estimate as a Simple and Efficient Data Value**]() (ICML'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Training Data Attribution for Diffusion Models**]() (arXiv'23)

  🎯Sample  🌐Synthetic  📊White-Box  🧩Self  ⚖️Generative

- [**EcoVal: An Efficient Data Valuation Framework for Machine Learning**]() (KDD'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Data Valuation by Leveraging Global and Local Statistical Information**]() (arXiv'24)

  🎯Sample  🌐Streaming  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**LossVal: Efficient Data Valuation for Neural Networks**]() (arXiv'24)

  🎯Sample  🌐Tabular  📊White-Box  🧩Self  ⚖️Discriminative

- [**Is Data Valuation Learnable and Interpretable?**]() (arXiv'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Scaling Laws for the Value of Individual Data Points in Machine Learning**]() (ICML'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Stochastic Amortization: A Unified Approach to Accelerate Feature and Data Attribution**]() (NeurIPS'24)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Region-Level Data Attribution for Text-to-Image Generative Models**]() (ICCV'25)

  🎯Element  🌐Multimodal  📊Black-Box  🧩Strong  ⚖️Generative

- [**Beyond Models Explainable Data Valuation and Metric Adaption for Recommendation**]() (SDM'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Fast Data Attribution for Text-to-Image Models**]() (arXiv'25)

  🎯Sample  🌐Multimodal  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Efficient Forward-Only Data Valuation for Pretrained LLMs and VLMs**]() (arXiv'25)

  🎯Sample  🌐Multimodal  📊Gray-Box  🧩Strong  ⚖️Generative

- [**Data-Efficient Pretraining with Group-Level Data Influence Modeling**]() (arXiv'25)

  🎯Dataset  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Error Estimate and Convergence Analysis for Data Valuation**]() (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Neural Networks for Learnable and Scalable Influence Estimation of Instruction Fine-Tuning Data**]() (arXiv'25)

  🎯Sample  🌐Text  📊Gray-Box  🧩Strong  ⚖️Instruction Tuning

- [**Shapley-Guided Utility Learning for Effective Graph Inference Data Valuation**]() (ICLR'25)

  🎯Element  🌐Graph  📊Black-Box  🧩Self  ⚖️Discriminative

- [**TSRating: Rating Quality of Diverse Time Series Data by Meta-learning from LLM Judgment**]() (arXiv'25)

  🎯Sample  🌐Time-Series  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Fast-DataShapley: Neural Modeling for Training Data Valuation**]() (WSDM'26)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Influence-Preserving Proxies for Gradient-Based Data Selection in LLM Fine-tuning**]() (arXiv'26)

  🎯Sample  🌐Text  📊White-Box  🧩Strong  ⚖️Instruction Tuning

### 4. Model-agnostic Valuation

- [**Validation Free and Replication Robust Volume-based Data Valuation**]() (NeurIPS'21)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Self  ⚖️Task-Agnostic

- [**Incentivizing Collaboration in Machine Learning via Synthetic Data Rewards**]() (AAAI'22)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Generative

- [**DAVINZ: Data Valuation using Deep Neural Networks at Initialization**]() (ICML'22)

  🎯Dataset  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Data Valuation Without Training of a Model**]() (ICLR'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**LAVA: Data Valuation without Pre-Specified Learning Algorithms**]() (ICLR'23)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Task-Agnostic

- [**Fundamentals of Task-Agnostic Data Valuation**]() (AAAI'23)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Self  ⚖️Task-Agnostic

- [**Data Valuation in the Absence of a Reliable Validation Set**]() (TMLR'24)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Data Valuation and Detections in Federated Learning**]() (CVPR'24)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Proper Dataset Valuation by Pointwise Mutual Information**]() (arXiv'24)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Self  ⚖️Task-Agnostic

- [**Data Valuation and Selection in a Federated Model Marketplace**]() (arXiv'25)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Eigen-Value: Efficient Domain-Robust Data Valuation via Eigenvalue-Based Approach**]() (arXiv'25)

  🎯Sample 🌐Tabular 📊Gray-Box 🧩Self ⚖️Discriminative

- [**Data Value in the Age of Scaling: Understanding LLM Scaling Dynamics Under Real-Synthetic Data Mixtures**]() (arXiv'25)

  🎯Dataset  🌐Text  📊White-Box  🧩Strong  ⚖️Generative

- [**Fortifying Federated Learning Towards Trustworthiness via Auditable Data Valuation and Verifiable Client Contribution**]() (CVPR'25)

  🎯Dataset  🌐Tabular  📊Gray-Box  🧩Self  ⚖️Discriminative

- [**Geometric Data Valuation via Leverage Scores**]() (arXiv'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Self  ⚖️Task-Agnostic

- [**GMValuator: Similarity-based Data Valuation for Generative Models**]() (ICLR'25)

  🎯Sample  🌐Synthetic  📊Black-Box  🧩Self  ⚖️Generative

- [**KAIROS: Scalable Model-Agnostic Data Valuation**]() (NeurIPS'25)

  🎯Sample  🌐Streaming  📊Black-Box  🧩Strong  ⚖️Task-Agnostic

- [**SAVA: Scalable Learning-Agnostic Data Valuation**]() (ICLR'25)

  🎯Sample  🌐Tabular  📊Black-Box  🧩Strong  ⚖️Task-Agnostic

- [**Privacy-Preserving Feature Valuation in Vertical Federated Learning Using Shapley-CMI and PSI Permutation**]() (arXiv'25)

  🎯Element  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**Data Valuation for Vertical Federated Learning: A Model-Free and Privacy-Preserving Method**]() (MISQ'26)

  🎯Dataset  🌐Tabular  📊Black-Box  🧩Self  ⚖️Discriminative

- [**TimeLAVA: Learning-Agnostic Valuation for Time Series Data**]() (ICLR'26)

  🎯Element  🌐Time-Series  📊Black-Box  🧩Strong  ⚖️Task-Agnostic

### 5. Other Related Methods

- [**The Value of Out-of-Distribution Data**]() (ICML'23)

  🎯Dataset  🌐Tabular  📊White-Box  🧩Weak  ⚖️Discriminative

- [**In-context probing approximates influence function for data valuation**]() (arXiv'24)

  🎯Sample  🌐Text  📊Black-Box  🧩Strong  ⚖️Instruction Tuning

- [**Diffusion Attribution Score: Evaluating Training Data Influence in Diffusion Models**]() (ICLR'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Generative

- [**Data Valuation for LLM Fine-Tuning: Efficient Shapley Value Approximation via Language Model Arithmetic**]() (arXiv'25)

  🎯Dataset  🌐Text  📊Gray-Box  🧩Strong  ⚖️Instruction Tuning

- [**Beyond Uniform Deletion: A Data Value-Weighted Framework for Certified Machine Unlearning**]() (arXiv'25)

  🎯Sample  🌐Tabular  📊White-Box  🧩Strong  ⚖️Discriminative

- [**Do Data Valuations Make Good Data Prices?**]() (arXiv'25)

  🎯Dataset  🌐Text  📊Black-Box  🧩Strong  ⚖️Generative

- [**Fairshare Data Pricing via Data Valuation for Large Language Models**]() (NeurIPS'25)

  🎯Dataset  🌐Text  📊Black-Box  🧩Strong  ⚖️Instruction Tuning

- [**Mixture-ofscores: Robust image-text data quality score via three lines of code**]() (ICCV'25)

  🎯Sample  🌐Multimodal  📊Black-Box  🧩Self  ⚖️Generative

- [**From Fairness to Truthfulness: Rethinking Data Valuation Design**]() (ICLR'25)

  🎯Dataset  🌐Text  📊Black-Box  🧩Strong  ⚖️Discriminative

- [**Importance-aware data selection for efficient llm instruction tuning**]() (AAAI'26)

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



