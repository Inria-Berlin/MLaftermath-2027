# NeurIPS 2026 contributions with Berlin-affiliated authors

Candidate list for the next MLaftermath edition, generated 2026-11-11 by the [neurips-berlin](https://github.com/ml-lab-htw/neurips-berlin) scraper: 122 papers and contributions with 165 Berlin-affiliated authors (in bold). A Berlin affiliation is listed when it was matched with high confidence or checked by hand; uncertain matches are left out until reviewed.

Authors at the companies on the organizers' list (Prior Labs, NVIDIA, Aleph Alpha, DeepL, Helsing, Black Forest Labs) are in a separate list, [companies.md](companies.md): 477 people on 325 papers.

Everything here comes from public sources: the NeurIPS 2026 virtual site, OpenReview and the papers' first pages. This folder is not meant for the website: Jekyll skips folders starting with `_`. Being listed here says nothing about invitations.

Files: `papers.csv` (one row per paper, both lists), `berlin_authors.csv` and `company_authors.csv` (one row per person).

## Coverage

| Category | Papers collected | With Berlin authors | With company authors |
|---|---:|---:|---:|
| Workshop | 8209 | 64 | 90 |
| Main Track | 7897 | 45 | 186 |
| Evaluations & Datasets Track | 971 | 10 | 44 |
| Position Paper Track | 137 | 1 | 3 |
| Creative AI | 98 | 0 | 1 |
| Journal Track | 87 | 1 | 1 |
| Education Track | 52 | 0 | 0 |
| Bridging the Future | 36 | 0 | 0 |
| Reproducibility Track (MLRC) | 16 | 1 | 0 |

Known gaps:

- session Affinity Joint Poster Session: no_page: no contribution list published on neurips.cc
- session WiML Poster Session: empty: no contribution list published on neurips.cc
- workshop without listed papers, not scraped: AI for Peace

## Contents

- [Main Track](#main-track) (45)
- [Evaluations & Datasets Track](#evaluations--datasets-track) (10)
- [Position Paper Track](#position-paper-track) (1)
- [Journal Track](#journal-track) (1)
- [Workshops](#workshops) (64)
  - [2026 Workshop on SaTQuML: Secure and Trustworthy Quantum Machine Learning](#2026-workshop-on-satquml-secure-and-trustworthy-quantum-machine-learning) (1)
  - [8th Robot Learning Workshop: Is Physical AI Going Zero-Shot?](#8th-robot-learning-workshop-is-physical-ai-going-zero-shot) (1)
  - [Agentic Systems for Molecular Sciences](#agentic-systems-for-molecular-sciences) (4)
  - [AI Agents for Biomedical Imaging and Multimodal Clinical Data](#ai-agents-for-biomedical-imaging-and-multimodal-clinical-data) (1)
  - [AI for Drug Discovery: Bridging the Translation Gap](#ai-for-drug-discovery-bridging-the-translation-gap) (1)
  - [AI for Meta-Science: Scaling and Organizing Science in the Age of AI Scientists](#ai-for-meta-science-scaling-and-organizing-science-in-the-age-of-ai-scientists) (1)
  - [AI for Science: Verification in the Age of AI Scientists](#ai-for-science-verification-in-the-age-of-ai-scientists) (1)
  - [AI for Stochastic Dynamics: From Theoretical Foundations to Scientific Applications](#ai-for-stochastic-dynamics-from-theoretical-foundations-to-scientific-applications) (1)
  - [AI4Mat-NeurIPS-2026: NeurIPS-2026 Workshop on AI for Accelerated Materials Design](#ai4mat-neurips-2026-neurips-2026-workshop-on-ai-for-accelerated-materials-design) (4)
  - [AIDaR: AI Data Readiness for Scientific Discovery](#aidar-ai-data-readiness-for-scientific-discovery) (2)
  - [ATTRIB: Workshop on Data Attribution and Provenance](#attrib-workshop-on-data-attribution-and-provenance) (3)
  - [AXIOM: Foundations of Efficient Deep Learning](#axiom-foundations-of-efficient-deep-learning) (1)
  - [Beyond Next Token Prediction: Diffusion and Flow Models for Next-Generation Decoding](#beyond-next-token-prediction-diffusion-and-flow-models-for-next-generation-decoding) (1)
  - [Beyond Private Training: The New Landscape of AI Privacy](#beyond-private-training-the-new-landscape-of-ai-privacy) (1)
  - [Bridging Optimal Transport, Learning and Structured Data: Toward Geometric Distributional Learning](#bridging-optimal-transport-learning-and-structured-data-toward-geometric-distributional-learning) (2)
  - [Can We Trust AI Evaluation? Robustness, Causality, and Risk in Modern AI Assessment](#can-we-trust-ai-evaluation-robustness-causality-and-risk-in-modern-ai-assessment) (2)
  - [Continual Learning in the Era of Foundation Models and Embodied Agents](#continual-learning-in-the-era-of-foundation-models-and-embodied-agents) (1)
  - [Foundation Models for the Brain and Body](#foundation-models-for-the-brain-and-body) (1)
  - [Foundations of Agentic Systems Theory (FAST)](#foundations-of-agentic-systems-theory-fast) (3)
  - [Foundations of Language Model Security: Theory, Practice, and Fundamental Limits](#foundations-of-language-model-security-theory-practice-and-fundamental-limits) (1)
  - [Generalization for Time Series in Tight Settings: Latency, Inference, Memory, prIvacy and Sustainability (TS-LIMITS)](#generalization-for-time-series-in-tight-settings-latency-inference-memory-privacy-and-sustainability-ts-limits) (1)
  - [Interpretability as a Science: Toward Rigorous Foundations for Understanding LLMs](#interpretability-as-a-science-toward-rigorous-foundations-for-understanding-llms) (2)
  - [Machine Learning for Simulations in Biology and Chemistry - The 2nd SIMBIOCHEM Workshop](#machine-learning-for-simulations-in-biology-and-chemistry---the-2nd-simbiochem-workshop) (1)
  - [Managing Agents that Manage Agents: Workshop on Responsible Use of Meta-Agents that Build, Optimize, and Supervise Other Agents](#managing-agents-that-manage-agents-workshop-on-responsible-use-of-meta-agents-that-build-optimize-and-supervise-other-agents) (1)
  - [MATH-AI: The 6th Workshop on Mathematical Reasoning and AI](#math-ai-the-6th-workshop-on-mathematical-reasoning-and-ai) (2)
  - [Reinforcement Learning for Experimental Sciences: Bridging the Simulation-to-Reality Gap](#reinforcement-learning-for-experimental-sciences-bridging-the-simulation-to-reality-gap) (1)
  - [Self-Evolving Diversity-Driven Search for Robust AI Systems](#self-evolving-diversity-driven-search-for-robust-ai-systems) (1)
  - [Sim2Science: ML with Imperfect Scientific Models](#sim2science-ml-with-imperfect-scientific-models) (2)
  - [SLM-Agents: 1st Workshop on SLMs for Agentic Systems](#slm-agents-1st-workshop-on-slms-for-agentic-systems) (1)
  - [SocialAgent: Second Workshop on Large Language Models for Social Reasoning and Simulation](#socialagent-second-workshop-on-large-language-models-for-social-reasoning-and-simulation) (1)
  - [Symmetry and Geometry in Neural Representations NeurIPS Workshops 2026](#symmetry-and-geometry-in-neural-representations-neurips-workshops-2026) (2)
  - [The Third Workshop on Agents in the Wild: Safety, Security, and Beyond](#the-third-workshop-on-agents-in-the-wild-safety-security-and-beyond) (2)
  - [Transitioning from Pre-training to Post-training](#transitioning-from-pre-training-to-post-training) (1)
  - [Trustworthy AI for Good (AI4GOOD) Workshop](#trustworthy-ai-for-good-ai4good-workshop) (4)
  - [Who Verifies the Agents? Toward Reliable Agent Development](#who-verifies-the-agents-toward-reliable-agent-development) (2)
  - [Workshop on Evaluation of Interactive Agents](#workshop-on-evaluation-of-interactive-agents) (1)
  - [Workshop on Resource-Aware Agentic AI](#workshop-on-resource-aware-agentic-ai) (1)
  - [Workshop on the Linguistic Principles for Foundation Models](#workshop-on-the-linguistic-principles-for-foundation-models) (1)
  - [Workshop on Towards Test-Time Continual Learning Agents](#workshop-on-towards-test-time-continual-learning-agents) (1)
  - [XAI4science: Knowledge Discovery and Trust through Interpretable Foundation Models](#xai4science-knowledge-discovery-and-trust-through-interpretable-foundation-models) (3)
- [Reproducibility Track (MLRC)](#reproducibility-track-mlrc) (1)

## Main Track

- **[A Free Lunch in LLM Compression: Revisiting Retraining after Pruning](https://openreview.net/forum?id=fXCIZretcP)** (Poster)  
  **Moritz Wagner**, **Christophe Roux**, **Max Zimmer**, **Sebastian Pokutta**  
  Berlin: Moritz Wagner: Zuse Institute Berlin (ZIB); Christophe Roux: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Max Zimmer: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB)
- **[A Trust Region Approach for Learning Schrödinger Bridges](https://openreview.net/forum?id=pXZ4KjVpoE)** (Poster)  
  Takeshi Koshizuka, Denis Blessing, **Max Zimmer**, **Sebastian Pokutta**, **Lorenz Richter**  
  Berlin: Max Zimmer: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Lorenz Richter: Zuse Institute Berlin (ZIB) / dida Datenschmiede
- **[AI-Mediated Communication Can Steer Collective Opinion](https://openreview.net/forum?id=2jvTv6EcKS)** (Poster)  
  Stratis Tsirtsis, Kai Rawal, Chris Russell, **Brent Mittelstadt**, Sandra Wachter  
  Berlin: Brent Mittelstadt: Weizenbaum Institute
- **[Approximation Guarantees for Robust Aggregation in Federated Learning](https://openreview.net/forum?id=4ySjO4QTTH)** (Poster)  
  Mélanie Cambus, **Darya Melnyk**, **Tijana Milentijević**, **Stefan Schmid**  
  Berlin: Darya Melnyk: Technische Universität Berlin; Tijana Milentijević: Technische Universität Berlin; Stefan Schmid: Technische Universität Berlin / Weizenbaum Institute
- **[Argument Graph Uncertainty: Quantifying Uncertainty from the Logical Structure of Reasoning Chains](https://openreview.net/forum?id=sRkn7hto0l)** (Poster)  
  **Simon Baur**, **Sumire Honda**, **Wojciech Samek**, **Jackie Ma**  
  Berlin: Simon Baur: Fraunhofer Heinrich Hertz Institute (HHI); Sumire Honda: Fraunhofer Heinrich Hertz Institute (HHI); Wojciech Samek: Fraunhofer Heinrich Hertz Institute (HHI); Jackie Ma: Fraunhofer Heinrich Hertz Institute (HHI)
- **[Beyond Isolation: Neighbor-Consistent Data Pruning for Multivariate Time Series Forecasting](https://openreview.net/forum?id=B5ACjqvQ2x)** (Poster)  
  **Zi Yang**, Jona Otholt, Weixing Wang, Haojin Yang, **Guillermo Gallego**  
  Berlin: Zi Yang: Technische Universität Berlin; Guillermo Gallego: Technische Universität Berlin
- **[Characterizing Universal Object Representations Across Vision Models](https://openreview.net/forum?id=16SGONh3Vl)** (Poster)  
  **Florian P Mahner**, Johannes Roth, Ka Chun Lam, Mick Bonner, Francisco Pereira, Martin N Hebart  
  Berlin: Florian P Mahner: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin
- **[CoLaX: Context-Aware Local Explanations for Time Series Classification](https://openreview.net/forum?id=4Mn24WBKDZ)** (Poster)  
  Kexuan Zhang, Paolo Frazzetto, Xiaobei Zou, Gustau Camps-Valls, **Yang Tang**  
  Berlin: Yang Tang: Humboldt-Universität zu Berlin
- **[Consistency as a Testable Property: Statistical Methods to Evaluate AI Agent Reliability](https://openreview.net/forum?id=28uXN3BzkF)** (Poster)  
  Harsh Raj, Niranjan Orkat, Suvrorup Mukherjee, Aritra Guha, **Cheryl Flynn**, Subhabrata Majumdar  
  Berlin: Cheryl Flynn: Telekom Innovation Laboratories (T-Labs) Berlin
- **[Contrastive Hypergraph Source-free Domain Adaptive Object Detection in Adverse Weathers](https://openreview.net/forum?id=TAXQQlBzoz)** (Poster)  
  **Jicheng Yuan**, **Duc Manh Nguyen**, Tung Kieu, **Manfred Hauswirth**, Danh Le-Phuoc  
  Berlin: Jicheng Yuan: Technische Universität Berlin; Duc Manh Nguyen: Technische Universität Berlin; Manfred Hauswirth: Technische Universität Berlin
- **[Controlling for Omitted Variable Bias in Deep Neural Networks](https://openreview.net/forum?id=K9sgYlq0Bi)** (Poster)  
  **Manuel Pfeuffer**, **Roshan P Rane**, **Kerstin Ritter**, **Sonja Greven**  
  Berlin: Manuel Pfeuffer: Humboldt-Universität zu Berlin; Roshan P Rane: Humboldt-Universität zu Berlin; Kerstin Ritter: Charité – Universitätsmedizin Berlin; Sonja Greven: Humboldt-Universität zu Berlin
- **[Conveyance: A Versatile Framework for Learning in Structured Class Spaces](https://openreview.net/forum?id=4SAFhHJb63)** (Poster)  
  **Yasser Taha**, **Grégoire Montavon**, **Nils Körber**  
  Berlin: Yasser Taha: Robert Koch Institute; Grégoire Montavon: Charité – Universitätsmedizin Berlin; Nils Körber: Robert Koch Institute
- **[Curvature-Dependent Lower Bounds for Frank-Wolfe](https://openreview.net/forum?id=9QiqOqCKsr)** (Poster)  
  **Jannis Halbey**, **Christophe Roux**, **Sebastian Pokutta**  
  Berlin: Jannis Halbey: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Christophe Roux: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB)
- **[Distribution Shift in Missing Data Imputation: A Risk-Based Perspective and Importance-Weighted Correction under MAR](https://openreview.net/forum?id=3VK2QApcYJ)** (Poster)  
  Luke Shannon, Song Liu, **Katarzyna Reluga**  
  Berlin: Katarzyna Reluga: Humboldt-Universität zu Berlin
- **[Explaining Cross-Modal Model Behavior with Gradient-Estimation-Based Feature Interaction](https://openreview.net/forum?id=k3fR86JLGj)** (Poster)  
  Yi Cai, Xinpeng Li, **Gerhard Wunder**  
  Berlin: Gerhard Wunder: Freie Universität Berlin
- **[Explanation Mechanism Influences Human Reliance on Reinforcement Learning Agents](https://openreview.net/forum?id=099yUmkgyW)** (Poster)  
  Xuying Zhong, Daniel Beechey, Crescent Jicol, Janina A. Hoffmann, **Özgür Şimşek**  
  Berlin: Özgür Şimşek: Max Planck Institute for Human Development
- **[Fingerprinting Inference Systems of Large Language Models](https://openreview.net/forum?id=JfJBHSWafR)** (Poster)  
  **Anna Wimbauer**, **Jonas Möller**, **Erik Imgrund**, **Konrad Rieck**  
  Berlin: Anna Wimbauer: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Jonas Möller: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Erik Imgrund: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Konrad Rieck: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin
- **[Flow Matching with In-Context Priors for Out-of-Distribution Brain Dynamics](https://openreview.net/forum?id=K10eas8GS0)** (Poster)  
  **Sam Gijsen**, **Michał Łukomski**, **Marc-Andre Schulz**, **Kerstin Ritter**  
  Berlin: Sam Gijsen: Charité – Universitätsmedizin Berlin; Michał Łukomski: Charité – Universitätsmedizin Berlin; Marc-Andre Schulz: Charité – Universitätsmedizin Berlin; Kerstin Ritter: Charité – Universitätsmedizin Berlin
- **[Frank-Wolfe Beyond 1/t Convergence](https://openreview.net/forum?id=0Q5L0kJ3W4)** (Poster)  
  **Sebastian Pokutta**  
  Berlin: Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB)
- **[Fusion or Confusion? Multimodal Complexity Is Not All You Need](https://openreview.net/forum?id=RtOPHuqmpj)** (Poster)  
  **Tillmann Rheude**, **Roland Eils**, **Benjamin Wild**  
  Berlin: Tillmann Rheude: Berlin Institute of Health at Charité (BIH) / Charité – Universitätsmedizin Berlin / Freie Universität Berlin; Roland Eils: Berlin Institute of Health at Charité (BIH) / Charité – Universitätsmedizin Berlin / Freie Universität Berlin; Benjamin Wild: Berlin Institute of Health at Charité (BIH) / Charité – Universitätsmedizin Berlin
- **[Generalized Wasserstein Flow Matching: Transport Plans, Everywhere, All at Once](https://openreview.net/forum?id=VRSgjWCWsh)** (Poster)  
  **Moritz Piening**, **Richard Duong**, **Gabriele Steidl**  
  Berlin: Moritz Piening: Technische Universität Berlin; Richard Duong: Technische Universität Berlin; Gabriele Steidl: Technische Universität Berlin
- **[Hodge Laplacian Quasi-Harmonic Flows for Option Discovery](https://openreview.net/forum?id=Ipo5Xh353j)** (Poster)  
  Andreas Theophilou, **Özgür Şimşek**  
  Berlin: Özgür Şimşek: Max Planck Institute for Human Development
- **[How Much of a Model Do We Need? Redundancy and Slimmability in Remote Sensing Foundation Models](https://openreview.net/forum?id=0IXZABr3Tf)** (Poster)  
  **Leonard Hackel**, **Begum Demir**, **Tom Burgert**  
  Berlin: Leonard Hackel: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Begum Demir: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Tom Burgert: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin
- **[Hyper Input Convex Neural Networks for Shape Constrained Learning and Optimal Transport](https://openreview.net/forum?id=G69BisYSHp)** (Poster)  
  Shayan Hundrieser, Insung Kong, **Johannes Schmidt-Hieber**  
  Berlin: Johannes Schmidt-Hieber: Humboldt-Universität zu Berlin / Weierstrass Institute for Applied Analysis and Stochastics (WIAS)
- **[Learning-Augmented Online Scheduling with Parsimonious Preemption](https://openreview.net/forum?id=4DXp81vtxV)** (Poster)  
  Mugen Blue, Sungjin Im, **Alexander Lindermayr**  
  Berlin: Alexander Lindermayr: Technische Universität Berlin
- **[Managing Self-Learning Experts under Per-Round Budget Constraints](https://openreview.net/forum?id=Kl4TknNwAA)** (Poster)  
  Ilgam Latypov, **Alexandra Suvorikova**, **Alexey Kroshnin**, Alexander Gasnikov, Iurii Dorn  
  Berlin: Alexandra Suvorikova: Weierstrass Institute for Applied Analysis and Stochastics (WIAS); Alexey Kroshnin: Weierstrass Institute for Applied Analysis and Stochastics (WIAS)
- **[Manifold Sampling via Entropy Maximization](https://openreview.net/forum?id=mAVz31YJlN)** (Poster)  
  **Cornelius Braun**, **Tilman Burghoff**, **Marc Toussaint**  
  Berlin: Cornelius Braun: Technische Universität Berlin; Tilman Burghoff: Technische Universität Berlin; Marc Toussaint: Technische Universität Berlin
- **[MapPFN: Learning Causal Perturbation Maps in Context](https://openreview.net/forum?id=skdhOj5NkC)** (Poster)  
  **Marvin Sextro**, **Weronika Kłos**, **Gabriel Dernbach**  
  Berlin: Marvin Sextro: Aignostics / BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Weronika Kłos: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Gabriel Dernbach: Aignostics / BIFOLD – Berlin Institute for the Foundations of Learning and Data / Charité – Universitätsmedizin Berlin / Technische Universität Berlin
- **[MultiSTEVE-1s: A Model Zoo and Interpretability Suite for Instruction-Following Vision Agents](https://openreview.net/forum?id=sR3tHXbQxm)** (Poster)  
  Karolis Jucys, George Adamopoulos, **Özgür Şimşek**  
  Berlin: Özgür Şimşek: Max Planck Institute for Human Development
- **[Neural Scaling Laws in Particle Jets](https://openreview.net/forum?id=rMzU4uxIrE)** (Poster)  
  Matthias Vigl, Nikita Pond, Nicole Hartman, Jackson Barr, **Daniel H Guest**, Alexander Froch, Michele D&#x27;Andrea, Dmitrii Kobylianskii, Daniel Murnane, Robert Les, Sébastien Rettie, Diptaparna Biswas, Michael Kagan, Lukas Heinrich  
  Berlin: Daniel H Guest: Humboldt-Universität zu Berlin
- **[Optimal algorithmic complexity of inference in quantum kernel methods](https://openreview.net/forum?id=dMzQUanLcb)** (Poster)  
  **Elies Gil-Fuster**, **Seongwook Shin**, **Sofiene Jerbi**, **Jens Eisert**, **Maximilian J Kramer**  
  Berlin: Elies Gil-Fuster: Fraunhofer Heinrich Hertz Institute (HHI) / Freie Universität Berlin; Seongwook Shin: Freie Universität Berlin; Sofiene Jerbi: Freie Universität Berlin / Helmholtz-Zentrum Berlin; Jens Eisert: Fraunhofer Heinrich Hertz Institute (HHI) / Freie Universität Berlin / Helmholtz-Zentrum Berlin; Maximilian J Kramer: Freie Universität Berlin
- **[Process-conditioned Pretraining with Topographic Spatial Retrieval for Large EEG Models](https://openreview.net/forum?id=wrHWTrf4Uv)** (Poster)  
  Yi Ding, Muyun Jiang, Weibang Jiang, Shuailei Zhang, XINLIANG ZHOU, Chenyu Liu, **Shanglin Li**, Yong Li, Cuntai Guan  
  Berlin: Shanglin Li: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin
- **[Resilient Byzantine Agreement with Predictions](https://openreview.net/forum?id=nnJ8B6FqKC)** (Poster)  
  **Julien Dallot**, **Darya Melnyk**, **Tijana Milentijević**, **Stefan Schmid**, **Patrik Welters**  
  Berlin: Julien Dallot: Technische Universität Berlin; Darya Melnyk: Technische Universität Berlin; Tijana Milentijević: Technische Universität Berlin; Stefan Schmid: Technische Universität Berlin / Weizenbaum Institute; Patrik Welters: Humboldt-Universität zu Berlin
- **[SecureClaw: Clawing Back Control of LLM Agents](https://openreview.net/forum?id=0omFi3ZiBf)** (Poster)  
  **Yuhan Ma**, **Stefan Schmid**  
  Berlin: Yuhan Ma: Technische Universität Berlin; Stefan Schmid: Technische Universität Berlin
- **[Skip the Hessian, Keep the Rates: Globalized Semismooth Newton with Lazy Hessian Updates](https://openreview.net/forum?id=qs8DDaqFC9)** (Poster)  
  **Amal Alphonse**, **Pavel Dvurechenskii**, **Clemens Sirotenko**  
  Berlin: Amal Alphonse: Weierstrass Institute for Applied Analysis and Stochastics (WIAS); Pavel Dvurechenskii: Weierstrass Institute for Applied Analysis and Stochastics (WIAS); Clemens Sirotenko: Weierstrass Institute for Applied Analysis and Stochastics (WIAS)
- **[Spherical Flows for Sampling Categorical Data](https://openreview.net/forum?id=uVMZotQcJ7)** (Spotlight)  
  **Jannis Chemseddine**, **Gregor Kornhardt**, **Gabriele Steidl**  
  Berlin: Jannis Chemseddine: Technische Universität Berlin; Gregor Kornhardt: Technische Universität Berlin; Gabriele Steidl: Technische Universität Berlin
- **[Structural Causal Bottleneck Models](https://openreview.net/forum?id=3KALmCyLoY)** (Poster)  
  **Simon Bing**, Jonas Wahl, Jakob Runge  
  Berlin: Simon Bing: Technische Universität Berlin
- **[Submodular Multi-Agent Reinforcement Learning for Effective Online Distributed Task Allocation](https://openreview.net/forum?id=m1AFEitkDl)** (Poster)  
  Jing Liu, Yangyang YANG, Luca Ballotta, Fangfei Li, **Yang Tang**, Ruggero Carli  
  Berlin: Yang Tang: Humboldt-Universität zu Berlin
- **[Symb-xMIL: Symbolic Explanations for Multiple Instance Learning in Digital Pathology](https://openreview.net/forum?id=OwuMiUXJ26)** (Poster)  
  **Yanqing Luo**, **Julius Hense**, **Niklas Prenißl**, Andreas Mock, **Klaus-Robert Müller**, **Thomas Schnake**, **Mina Jamshidi Idaji**  
  Berlin: Yanqing Luo: BIFOLD – Berlin Institute for the Foundations of Learning and Data; Julius Hense: BIFOLD – Berlin Institute for the Foundations of Learning and Data; Niklas Prenißl: Charité – Universitätsmedizin Berlin; Klaus-Robert Müller: BIFOLD – Berlin Institute for the Foundations of Learning and Data; Thomas Schnake: Technische Universität Berlin; Mina Jamshidi Idaji: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin
- **[The Algorithm Is Not the Behavior: Learned Priors Override Look-Ahead in a Chess-Playing Neural Network](https://openreview.net/forum?id=ULhusDnCQy)** (Oral)  
  **Elias Sandmann**, **Sebastian Lapuschkin**, **Wojciech Samek**  
  Berlin: Elias Sandmann: Fraunhofer Heinrich Hertz Institute (HHI); Sebastian Lapuschkin: Fraunhofer Heinrich Hertz Institute (HHI); Wojciech Samek: Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin
- **[The Alien Space of Science: Sampling Coherent but Cognitively Unavailable Research Directions](https://openreview.net/forum?id=UepmNYnfUe)** (Poster)  
  **Alejandro H. Artiles**, Martin Weiss, **Levin Brinkmann**, **Iyad Rahwan**, Bernhard Schölkopf, Chris Pal, Hugo Larochelle, Anirudh Goyal, Nasim Rahaman  
  Berlin: Alejandro H. Artiles: Max Planck Institute for Human Development; Levin Brinkmann: Max Planck Institute for Human Development; Iyad Rahwan: Max Planck Institute for Human Development
- **[The PFAD Not Taken: Measuring Polysemanticity via Feature Affine Decomposition](https://openreview.net/forum?id=er0tG7a4Fo)** (Poster)  
  Kirill Bykov, Maria A Bravo, **Laura Kopf**, Zeynep Akata  
  Berlin: Laura Kopf: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin
- **[Trustworthy Retrosynthesis: Eliminating Hallucinations with a Diverse Ensemble of Reaction Scorers](https://openreview.net/forum?id=QnViF2joi3)** (Poster)  
  Michał Sadowski, Tadija Radusinović, Maria Wyrzykowska, **Lukasz Sztukiewicz**, Jan Rzymkowski, Piotr Kozakowski, Mikolaj Sacha, Ruard van Workum, Stanislaw Jastrzebski  
  Berlin: Lukasz Sztukiewicz: Technische Universität Berlin
- **[When a Zero-Shooter Cheats: Improving Age Estimation via Activation Steering](https://openreview.net/forum?id=dXc5D0QtbZ)** (Poster)  
  **Erik Imgrund**, **Pia Hanfeld**, **Klim Kireev**, **Konrad Rieck**  
  Berlin: Erik Imgrund: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Pia Hanfeld: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Klim Kireev: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Konrad Rieck: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin
- **[Within-Model vs Between-Prompt Variability in Large Language Models for Creative Tasks](https://openreview.net/forum?id=d535njwZHX)** (Poster)  
  **Jennifer Haase**, **Jana Gonnermann-Müller**, Paul H. P. Hanel, **Nicolas Leins**, **Thomas Kosch**, **Jan Mendling**, **Sebastian Pokutta**  
  Berlin: Jennifer Haase: Humboldt-Universität zu Berlin / Weizenbaum Institute; Jana Gonnermann-Müller: Zuse Institute Berlin (ZIB); Nicolas Leins: Zuse Institute Berlin (ZIB); Thomas Kosch: Humboldt-Universität zu Berlin / Weizenbaum Institute; Jan Mendling: Humboldt-Universität zu Berlin / Weizenbaum Institute; Sebastian Pokutta: Zuse Institute Berlin (ZIB)

## Evaluations & Datasets Track

- **[BIAS-ID: A Framework for Analyzing Transformation Biases in AI-Generated Image Detectors](https://openreview.net/forum?id=GIewosR83I)** (Poster)  
  Jonas Ricker, Asja Fischer, **Erwin Quiring**  
  Berlin: Erwin Quiring: fbeta, Berlin
- **[Chem-PerturBridge: a harmonized compendium of small molecule perturbation transcriptomic effects](https://openreview.net/forum?id=UFv9oyIlVq)** (Poster)  
  Artur Szałata, **Olga Novitskaia**, Maiia Shulman, Matthew Mella, Altynbek Zhubanchaliyev, Fabian Theis  
  Berlin: Olga Novitskaia: Freie Universität Berlin
- **[CryptanalysisBench: Can LLMs do cryptanalysis?](https://openreview.net/forum?id=DWsZrINgjG)** (Poster)  
  Lukas Fluri, Avital Shafran, Nicholas Carlini, Matthew Jagielski, Milad Nasr, **Orr Dunkelman**, Eyal Ronen, Florian Tramer  
  Berlin: Orr Dunkelman: Technische Universität Berlin
- **[EVALUATION CARDS: An Interpretive Layer for AI Evaluation Reporting](https://openreview.net/forum?id=jGvGY7wh7Q)** (Spotlight)  
  Avijit Ghosh, Anka Reuel-Lamparth, Wm. Matthew Kennedy, Jenny Chim, Yilin Huang, Srishti Yadav, Anastassia Kornilova, Damian Stachura, Kevin Klyman, Jennifer Mickel, Felix Friedrich, Max Lamparth, **Jan Batzner**, Anoop Mishra, Jeba Sania, Eliya Habba, Nathan Heath, Shalaleh Rismani, Usman Gohar, Andrea Loehr, David Manheim, Ruchira Dhar, **Sree Harsha Nelaturu**, Aarush Sinha, Leshem Choshen, Yixiong Hao, Yanan Long, Andrew Tran, Drishti Sharma, Ishan Khire, Amit Saha, Subramanyam Sahoo, Michael Hardy, Michael A. Riegler, Kabir Manghnani, Michelle Lin, Nancy Jiang, Asaf Yehudai, Nuno Moniz, Yacine Jernite, Zeerak Talat, Stella Biderman, Mubashara Akhtar, Jessica Ji, Aris Hofmann, Mykel J Kochenderfer, Sanmi Koyejo, Irene Solaiman  
  Berlin: Jan Batzner: Weizenbaum Institute; Sree Harsha Nelaturu: Zuse Institute Berlin (ZIB)
- **[M4Bench: Evaluating Procedural Specification for Clinical EHR Derivation Agents](https://openreview.net/forum?id=EgGGRnoyTG)** (Poster)  
  Hannes Ill, Rafi Al Attrach, Rajna Fani, Ahram Han, Ryohei Yamamoto, **Marlene L Moerig**, Dukyong Yoon, Leo Anthony Celi  
  Berlin: Marlene L Moerig: Charité – Universitätsmedizin Berlin
- **[OpenMHC: Accelerating the Science of Wearable Foundation Models](https://openreview.net/forum?id=UOTXGszV0L)** (Poster)  
  Narayan Schuetz, Yuze Bai, Lianggang Pan, **Edgar Eggert**, Favour Nerrise, Juan Delgado-SanMartin, Max Rosenblattl, Milana Gurbanova, Mohammad Asadi, Anders Johnson, Paul Schmiedmayer, Dennis Wang, Allan Lawrie, Daniel S Kim, Xin Liu, Akshay Paruchuri, Ehsan Adeli, Euan Ashley, Kelly W Zhang  
  Berlin: Edgar Eggert: Charité – Universitätsmedizin Berlin
- **[quanda: An Interpretability Toolkit for Training Data Attribution Evaluation](https://openreview.net/forum?id=V3wscK9rvx)** (Poster)  
  **Dilyara Bareeva**, **Galip Ümit Yolcu**, **Anna Hedström**, **Niklas Schmolenski**, **Thomas Wiegand**, **Wojciech Samek**, **Sebastian Lapuschkin**  
  Berlin: Dilyara Bareeva: Fraunhofer Heinrich Hertz Institute (HHI); Galip Ümit Yolcu: Fraunhofer Heinrich Hertz Institute (HHI); Anna Hedström: Fraunhofer Heinrich Hertz Institute (HHI); Niklas Schmolenski: Fraunhofer Heinrich Hertz Institute (HHI); Thomas Wiegand: Fraunhofer Heinrich Hertz Institute (HHI); Wojciech Samek: Fraunhofer Heinrich Hertz Institute (HHI); Sebastian Lapuschkin: Fraunhofer Heinrich Hertz Institute (HHI)
- **[RamanBench: A Large-Scale Benchmark for Machine Learning on Raman Spectroscopy](https://openreview.net/forum?id=7sQ3RroZKg)** (Poster)  
  **Mario Koddenbrock**, **Christoph Lange**, Robin Legner, Martin Jaeger, Martin Kögler, **Mariano N Bournazou**, **Peter Neubauer**, **Felix Bießmann**, **Erik Rodner**  
  Berlin: Mario Koddenbrock: HTW Berlin – University of Applied Sciences; Christoph Lange: Technische Universität Berlin; Mariano N Bournazou: Technische Universität Berlin; Peter Neubauer: Technische Universität Berlin; Felix Bießmann: Berliner Hochschule für Technik (BHT); Erik Rodner: HTW Berlin – University of Applied Sciences
- **[Redefining Instance Matching: A Unified Framework for Part-Aware Matching in Panoptic Segmentation Evaluation](https://openreview.net/forum?id=pf5FQox6pD)** (Poster)  
  Erik Großkopf, Soumya Snigdha Kundu, Hendrik Möller, Nicolas Münster, Mehdi Astaraki, Paula T Buzduga, **Kerstin Ritter**, Benedikt Wiestler, Jan Kirschke, Jonathan Shapey, Tom Vercauteren, Florian Kofler  
  Berlin: Kerstin Ritter: Charité – Universitätsmedizin Berlin
- **[TSB-SEG: A Systematic Time-Series Segmentation Benchmark](https://openreview.net/forum?id=8o41Tc7xo4)** (Poster)  
  Félix Chavelli, **Arik Ermshaus**, **Patrick Schäfer**, Fan Yang, John Paparrizos, Paul Boniol  
  Berlin: Arik Ermshaus: Humboldt-Universität zu Berlin; Patrick Schäfer: Humboldt-Universität zu Berlin

## Position Paper Track

- **[Looking Under the Streetlight: Evaluation in Generative Molecular Dynamics](https://openreview.net/forum?id=6iB0w2UeaM)** (Poster)  
  Simon Olsson, **Frank Noe**, Grant Rotskoff, Kresten Lindorff-Larsen  
  Berlin: Frank Noe: Microsoft Research Berlin

## Journal Track

- **[Online Bernstein-von Mises theorem](http://arxiv.org/abs/2504.05661v2)** (Journal of Machine Learning Research (JMLR), Poster)  
  **Jeyong Lee**, Junhyeok Choi, Minwoo Chae  
  Berlin: Jeyong Lee: Weierstrass Institute for Applied Analysis and Stochastics (WIAS)

## Workshops

### 2026 Workshop on SaTQuML: Secure and Trustworthy Quantum Machine Learning

- **[CryptHarness: A Harness for Agent-Assisted Cryptanalytic Research](https://openreview.net/forum?id=1Va7bcbAUJ)** (Oral)  
  **Nico Pelleriti**, Nicolai Kraus, Alexander May, **Sebastian Pokutta**  
  Berlin: Nico Pelleriti: Zuse Institute Berlin (ZIB); Sebastian Pokutta: Zuse Institute Berlin (ZIB)

### 8th Robot Learning Workshop: Is Physical AI Going Zero-Shot?

- **[Count Generalization Is Easy, Actually: Warp a Frozen Skill Instead of Retraining It](https://openreview.net/forum?id=bULQOnaFFh)**  
  Paul Mattes, **Wojciech Samek**, **Marc Toussaint**  
  Berlin: Wojciech Samek: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin; Marc Toussaint: Technische Universität Berlin

### Agentic Systems for Molecular Sciences

- **[Can a Transformer Run Hartree-Fock? Compiling Self-Consistent Field Theory into Recurrent Transformer Weights](https://openreview.net/forum?id=nrlnxG5IOq)**  
  **Rostislav Fedorov**  
  Berlin: Rostislav Fedorov: Helmholtz-Zentrum Berlin
- **[Openclatura: Agentically Constructed, Verifiable Rules for Molecular Nomenclature](https://openreview.net/forum?id=CUMpjSfR6K)**  
  **Adrian Mirza**, Kevin Maik Jablonka, **Rostislav Fedorov**  
  Berlin: Adrian Mirza: Helmholtz-Zentrum Berlin; Rostislav Fedorov: Helmholtz-Zentrum Berlin
- **[ReSolved-Flow: Synthesis-Informed GFlowNets for Solvent-Conditioned Redox Molecular Design](https://openreview.net/forum?id=iWGADDwDcw)**  
  Izaac Roberts, **Rostislav Fedorov**, Gregor J Lauter, Ganna Gryn'ova  
  Berlin: Rostislav Fedorov: Helmholtz-Zentrum Berlin
- **[scXplain: Dissecting single-cell foundation models beyond predictive performance](https://openreview.net/forum?id=6VZCFj5zaS)**  
  **Farnoush Rezaei Jafari**, Stephanie Hyland, Kenza Bouzid, Lorin Crawford, Daniel C. Castro  
  Berlin: Farnoush Rezaei Jafari: Technische Universität Berlin

### AI Agents for Biomedical Imaging and Multimodal Clinical Data

- **[Ground Before You Decide: An Agentic, Clinical-Workflow-Inspired Pipeline for Verifiable Vision–Language Reasoning on Chest Radiographs](https://openreview.net/forum?id=byhPKAtTDL)** (Poster)  
  **Anirudh Narayanan Balaraman**, Xiufeng Yang, Cosmin Bercea, Lisa C Adams, Keno Bressem  
  Berlin: Anirudh Narayanan Balaraman: Charité – Universitätsmedizin Berlin

### AI for Drug Discovery: Bridging the Translation Gap

- **[MapPFN: Learning Causal Perturbation Maps in Context](http://arxiv.org/abs/2601.21092v4)**  
  **Marvin Sextro**, **Weronika Kłos**, **Gabriel Dernbach**  
  Berlin: Marvin Sextro: Aignostics / BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Weronika Kłos: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Gabriel Dernbach: Aignostics / BIFOLD – Berlin Institute for the Foundations of Learning and Data / Charité – Universitätsmedizin Berlin / Technische Universität Berlin

### AI for Meta-Science: Scaling and Organizing Science in the Age of AI Scientists

- **[Modelpedia: A Catalog of Model Findings for the Meta-Science of AI](https://openreview.net/forum?id=YgsGHxvaCn)** (Poster)  
  Franciszek Bernat, Dawid Płudowski, Michał J Włodarczyk, Luca Longo, Jianlong Zhou, Andreas Holzinger, Riccardo Guidotti, **Wojciech Samek**, Przemyslaw Prem Biecek  
  Berlin: Wojciech Samek: Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin

### AI for Science: Verification in the Age of AI Scientists

- **[Openclatura: Verification-Guided Agentic Construction of Molecular Nomenclature Rules](https://openreview.net/forum?id=vqLHroANUw)**  
  **Adrian Mirza**, Kevin Maik Jablonka, **Rostislav Fedorov**  
  Berlin: Adrian Mirza: Helmholtz-Zentrum Berlin; Rostislav Fedorov: Helmholtz-Zentrum Berlin

### AI for Stochastic Dynamics: From Theoretical Foundations to Scientific Applications

- **[Generative Modeling With Learnable Noise Memory](https://openreview.net/forum?id=vMHyqgTJPn)** (Poster)  
  **Gabriel Nobis**, Tim Korjakow, **Luca Schmidt**, **Maximilian Springenberg**, Thomas Demeester, **Wojciech Samek**, Manfred Opper, Tolga Birdal, Rembert Daems  
  Berlin: Gabriel Nobis: Fraunhofer Heinrich Hertz Institute (HHI); Luca Schmidt: Fraunhofer Heinrich Hertz Institute (HHI); Maximilian Springenberg: Fraunhofer Heinrich Hertz Institute (HHI); Wojciech Samek: Technische Universität Berlin

### AI4Mat-NeurIPS-2026: NeurIPS-2026 Workshop on AI for Accelerated Materials Design

- **[Openclatura: An Open and Inspectable IUPAC Naming Tool for Molecular Discovery Workflows](https://openreview.net/forum?id=BEbIrIUEWh)**  
  **Adrian Mirza**, Kevin Maik Jablonka, **Rostislav Fedorov**  
  Berlin: Adrian Mirza: Helmholtz-Zentrum Berlin; Rostislav Fedorov: Helmholtz-Zentrum Berlin
- **[Out-of-the-Box Tabular Foundation Models for Bayesian Optimization in Materials Discovery](https://openreview.net/forum?id=y7ZFsfh2Uy)**  
  Klemens Flöge, **Simon Bing**, Leo Grinsztajn, Eliott Kalfon, Lennart Purucker, Noah Hollmann, Frank Hutter  
  Berlin: Simon Bing: Technische Universität Berlin
- **[Reducing cross-sample prediction churn in scientific machine learning](https://openreview.net/forum?id=kPNui2SFvE)**  
  **Gordan Prastalo**, Kevin Maik Jablonka  
  Berlin: Gordan Prastalo: Helmholtz-Zentrum Berlin
- **[TAME: Element-wise Mixture-of-Experts Fusion for Reliable and Interpretable Molecular Property Prediction](https://openreview.net/forum?id=HzYKHTkXbj)**  
  Robert Schiller, Christoph Weisser, **Klaus-Robert Müller**, Parastoo Semnani  
  Berlin: Klaus-Robert Müller: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin

### AIDaR: AI Data Readiness for Scientific Discovery

- **[Evaluating and Improving Concept Prediction Models for Histopathological Discovery](https://openreview.net/forum?id=IkO8VFimH2)**  
  **Julius Hense**, Daniel C. Castro, Shruthi Bannur, **Farnoush Rezaei Jafari**, Daniel Shao, Eric Zimmermann, Kristen Severson, Drew Williamson, Stephanie Hyland, Tristan Lazard, Kenza Bouzid  
  Berlin: Julius Hense: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Farnoush Rezaei Jafari: Technische Universität Berlin
- **[Predicting Unseen Scientific Interactions: Conditional Flow Models Hallucinate Non-Additive Effects](https://openreview.net/forum?id=vWJFqW41fl)**  
  **Sam Gijsen**, **Moritz Seiler**, **Kerstin Ritter**  
  Berlin: Sam Gijsen: Charité – Universitätsmedizin Berlin; Moritz Seiler: Charité – Universitätsmedizin Berlin; Kerstin Ritter: Charité – Universitätsmedizin Berlin

### ATTRIB: Workshop on Data Attribution and Provenance

- **[Attributing Cohen's d: Training Data Attribution for Disease-Related Effects in Normative Age Biomarkers](https://openreview.net/forum?id=F9aVOS1bwB)**  
  Jakob Snel, **Marc-Andre Schulz**  
  Berlin: Marc-Andre Schulz: Charité – Universitätsmedizin Berlin
- **[Can Data Attribution Filter Out Subliminal Learning? Not Reliably.](https://openreview.net/forum?id=7zqk1FawhC)**  
  **Moritz Weckbecker**, Sweta Jena, **Jonas Müller**, Ponnurangam Kumaraguru, **Sebastian Lapuschkin**, **Wojciech Samek**, Louis Jaburi, Gonçalo Paulo  
  Berlin: Moritz Weckbecker: Fraunhofer Heinrich Hertz Institute (HHI); Jonas Müller: Technische Universität Berlin; Sebastian Lapuschkin: Fraunhofer Heinrich Hertz Institute (HHI); Wojciech Samek: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin
- **[MathaMAGICal: Validating Data Attribution during Arithmetic Acquisition](https://openreview.net/forum?id=yNVlOsu0Bz)**  
  Dikshanta Pokhrel, Jason Lee, Phonn N Khant, Victor Lee, **Moritz Weckbecker**, **Sebastian Lapuschkin**, **Wojciech Samek**, Mark Riedl, Glenn Matlin  
  Berlin: Moritz Weckbecker: Fraunhofer Heinrich Hertz Institute (HHI); Sebastian Lapuschkin: Fraunhofer Heinrich Hertz Institute (HHI); Wojciech Samek: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin

### AXIOM: Foundations of Efficient Deep Learning

- **[Back to Basics: Testing Hessian-Based Sensitivity Scores for PoT Weight-Quantization Damage](https://openreview.net/forum?id=8bNb5kFnya)** (Poster)  
  **Dominic Tarnowski**  
  Berlin: Dominic Tarnowski: HTW Berlin – University of Applied Sciences

### Beyond Next Token Prediction: Diffusion and Flow Models for Next-Generation Decoding

- **[SOL: Measuring Gaps between Text Distributions by Double Sliced Wasserstein Metrics](https://openreview.net/forum?id=f4hjd20QfW)**  
  **Gregor Kornhardt**, **Moritz Piening**, **Jannis Chemseddine**, **Gabriele Steidl**  
  Berlin: Gregor Kornhardt: Technische Universität Berlin; Moritz Piening: Technische Universität Berlin; Jannis Chemseddine: Technische Universität Berlin; Gabriele Steidl: Technische Universität Berlin

### Beyond Private Training: The New Landscape of AI Privacy

- **[Differentially Private Term Statistics for Efficient Synthetic Text Generation](https://openreview.net/forum?id=xSZLgxFLgV)**  
  Maximilian Höfler, Sebastian Hoefler, Karsten Mueller, **Wojciech Samek**  
  Berlin: Wojciech Samek: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin

### Bridging Optimal Transport, Learning and Structured Data: Toward Geometric Distributional Learning

- **[FlowCF: Sparse Counterfactual Explanations for Mixed-Type Tabular Data using Flow Matching](https://openreview.net/forum?id=0DfpRlIMBm)**  
  **Emmanouil Panagiotou**, Eirini Ntoutsi  
  Berlin: Emmanouil Panagiotou: Freie Universität Berlin
- **[Gromov–Monge Flow Matching for Equivariant Graph Generation](https://openreview.net/forum?id=cEdoVRFAzG)**  
  **Moritz Piening**, Christian Wald  
  Berlin: Moritz Piening: Technische Universität Berlin

### Can We Trust AI Evaluation? Robustness, Causality, and Risk in Modern AI Assessment

- **[Benchmarking Exploration Hacking Propensity in Frontier LLMs](https://openreview.net/forum?id=zAejOPjT6L)** (Poster)  
  **Eduard Hübner**, Nina Żukowska, Alexander Panfilov, Joschka Braun  
  Berlin: Eduard Hübner: Technische Universität Berlin
- **[Stress-Testing RL-based Capability Elicitation with Randomized Underperformance](https://openreview.net/forum?id=0Pp9w0tIqQ)** (Poster)  
  Nina Żukowska, **Eduard Hübner**, Alexander Panfilov, Joschka Braun  
  Berlin: Eduard Hübner: Technische Universität Berlin

### Continual Learning in the Era of Foundation Models and Embodied Agents

- **[More Than Enough for the Present: Predictive Semantic Diversity for Continual Learning](https://openreview.net/forum?id=3iTYkj7O9p)**  
  **Jiawen Xu**, Margret Keuper, **Odej Kao**  
  Berlin: Jiawen Xu: Technische Universität Berlin; Odej Kao: Technische Universität Berlin

### Foundation Models for the Brain and Body

- **[Representational and Functional Robustness to Electrode Montages in EEG Foundation Models](https://openreview.net/forum?id=v74034fvRr)**  
  Jakob Steglich, Justus Meyer zu Bexten, **Shakiba Moradi**, **Laure Ciernik**, Simon M. Hofmann, **Mina Jamshidi Idaji**  
  Berlin: Shakiba Moradi: BIFOLD – Berlin Institute for the Foundations of Learning and Data; Laure Ciernik: Technische Universität Berlin; Mina Jamshidi Idaji: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin

### Foundations of Agentic Systems Theory (FAST)

- **[Cooperative Words, Selfish Actions: How Strategic Optimization Shapes LLMs' Interaction With Humans](https://openreview.net/forum?id=gB6cKQkoa4)** (Talk + poster)  
  **Yaomin Jiang**, Yannik Keller, **Levin Brinkmann**, Tobias Werner, Seyed Ali Alhosseini, Michiel Bakker, Jean-François Bonnefon, **Iyad Rahwan**  
  Berlin: Yaomin Jiang: Max Planck Institute for Human Development; Levin Brinkmann: Max Planck Institute for Human Development; Iyad Rahwan: Max Planck Institute for Human Development
- **[Group selection to evolve cooperative prompts in populations of LLM agents](https://openreview.net/forum?id=CWWabnG53R)** (Talk + poster)  
  Luis Celiktemel, Edward Eichhorn, **Levin Brinkmann**, Robin Schimmelpfennig, Aron Vallinder, **Yaomin Jiang**, Edward Hughes, **Iyad Rahwan**  
  Berlin: Levin Brinkmann: Max Planck Institute for Human Development; Yaomin Jiang: Max Planck Institute for Human Development; Iyad Rahwan: Max Planck Institute for Human Development
- **[Model Heterogeneity Attenuates Escalation Dynamics among Large Language Models in War Games](https://openreview.net/forum?id=XU9Ltqd4Nc)** (Talk + poster)  
  Jihyeon Hyeong, Hiromu Yakura, **Iyad Rahwan**  
  Berlin: Iyad Rahwan: Max Planck Institute for Human Development

### Foundations of Language Model Security: Theory, Practice, and Fundamental Limits

- **[Uncovering Hidden Objectives via Transcoder Circuits](https://openreview.net/forum?id=UGXjdtMQKB)**  
  **Elena Golimblevskaia**, **Ammar Ibrahim**, **Wojciech Samek**, **Sebastian Lapuschkin**  
  Berlin: Elena Golimblevskaia: Fraunhofer Heinrich Hertz Institute (HHI); Ammar Ibrahim: Fraunhofer Heinrich Hertz Institute (HHI); Wojciech Samek: Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin; Sebastian Lapuschkin: Fraunhofer Heinrich Hertz Institute (HHI)

### Generalization for Time Series in Tight Settings: Latency, Inference, Memory, prIvacy and Sustainability (TS-LIMITS)

- **[Learning the Coefficients of the Standard Volatility Forecaster](https://openreview.net/forum?id=O2TmO3wH22)**  
  Ulysse Petit-Tichanné, **Nico Pelleriti**, **Max Zimmer**, **Sebastian Pokutta**  
  Berlin: Nico Pelleriti: Zuse Institute Berlin (ZIB); Max Zimmer: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB)

### Interpretability as a Science: Toward Rigorous Foundations for Understanding LLMs

- **[Degeneration Detection Is Not Early Warning: False-Alarm Evaluation with ONWARD](https://openreview.net/forum?id=D9PCb9C2nJ)**  
  Marco De Negri, Luca Sartori, Lorenzo Baggi, Moritz Reihs, Eduard F Ďurech, Mennatallah El-Assady, Valentina Pyatkin, **Anna Hedström**  
  Berlin: Anna Hedström: Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin
- **[KV-Cache Patching: Tracing How and Where Fine-Tuned Behaviors Arise](http://arxiv.org/abs/2610.41480v1)**  
  **Jonas Loos**, **Oliver Eberle**  
  Berlin: Jonas Loos: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Oliver Eberle: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin

### Machine Learning for Simulations in Biology and Chemistry - The 2nd SIMBIOCHEM Workshop

- **[TAME: Element-wise Mixture-of-Experts Fusion for Reliable and Interpretable Molecular Property Prediction](https://openreview.net/forum?id=P7gw7ZVb4i)**  
  Robert Schiller, Christoph Weisser, **Klaus-Robert Müller**, Parastoo Semnani  
  Berlin: Klaus-Robert Müller: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin

### Managing Agents that Manage Agents: Workshop on Responsible Use of Meta-Agents that Build, Optimize, and Supervise Other Agents

- **[Zero: A Meta-Agent for Mathematical Research](https://openreview.net/forum?id=xeNBqew8Jl)**  
  **Nico Pelleriti**, Konrad Plato, **Max Zimmer**, **Sebastian Pokutta**  
  Berlin: Nico Pelleriti: Zuse Institute Berlin (ZIB); Max Zimmer: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB)

### MATH-AI: The 6th Workshop on Mathematical Reasoning and AI

- **[AlphaDiana: A System for Evaluating Reasoning Agents](https://openreview.net/forum?id=YJFEscNgMe)** (Poster)  
  Zhanke Zhou, Zongze Li, Weikai Huang, Xuan Li, Chentao Cao, Xiao Feng, Xiangyu Lu, Jinbo Hu, Menghan Lu, Yi Xie, **Nico Pelleriti**, Shiyang Liu, **Max Zimmer**, Brando Miranda, Jiangchao Yao, Bo Liu, Sanmi Koyejo, **Sebastian Pokutta**, Bo Han  
  Berlin: Nico Pelleriti: Zuse Institute Berlin (ZIB); Max Zimmer: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB)
- **[Zero: A Meta-Agent for Mathematical Research](https://openreview.net/forum?id=yhKgvPCc2w)** (Poster)  
  **Nico Pelleriti**, Konrad Plato, **Max Zimmer**, **Sebastian Pokutta**  
  Berlin: Nico Pelleriti: Zuse Institute Berlin (ZIB); Max Zimmer: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB)

### Reinforcement Learning for Experimental Sciences: Bridging the Simulation-to-Reality Gap

- **[Reducing cross-sample prediction churn in scientific machine learning](https://openreview.net/forum?id=lSwOKOQDux)** (Poster)  
  **Gordan Prastalo**, Kevin Maik Jablonka  
  Berlin: Gordan Prastalo: Helmholtz-Zentrum Berlin

### Self-Evolving Diversity-Driven Search for Robust AI Systems

- **[What do evolutionary coding agents evolve?](https://openreview.net/forum?id=Sg9o6r4JBU)**  
  **Nico Pelleriti**, **Sree Harsha Nelaturu**, Zhanke Zhou, Zongze Li, **Max Zimmer**, Bo Han, **Sebastian Pokutta**  
  Berlin: Nico Pelleriti: Zuse Institute Berlin (ZIB); Sree Harsha Nelaturu: Zuse Institute Berlin (ZIB); Max Zimmer: Zuse Institute Berlin (ZIB); Sebastian Pokutta: Zuse Institute Berlin (ZIB)

### Sim2Science: ML with Imperfect Scientific Models

- **[Differentiability Is Not Enough: Inference Near a Dynamical Transition in a Whole-Brain Model](https://openreview.net/forum?id=cCLoQlY7df)**  
  **Marius Pille**, **Michael Schirner**  
  Berlin: Marius Pille: Berlin Institute of Health at Charité (BIH) / Charité – Universitätsmedizin Berlin; Michael Schirner: Berlin Institute of Health at Charité (BIH) / Charité – Universitätsmedizin Berlin
- **[Truncated automatic sparse differentiation for machine learning interatomic potentials](https://openreview.net/forum?id=Ec1UuQEzG6)**  
  Marcel F Langer, **Adrian Hill**, Michele Ceriotti  
  Berlin: Adrian Hill: Technische Universität Berlin

### SLM-Agents: 1st Workshop on SLMs for Agentic Systems

- **[E8 Lattice Key Quantization for Low-Bit KV-Cache Compression](https://openreview.net/forum?id=2QPitX2aBz)** (Poster)  
  **Sasho Nedelkoski**, **Alexander Acker**, **Soeren Becker**, **Dominik Scheinert**, **Odej Kao**  
  Berlin: Sasho Nedelkoski: Technische Universität Berlin; Alexander Acker: logsight.ai, Berlin; Soeren Becker: logsight.ai, Berlin; Dominik Scheinert: Technische Universität Berlin; Odej Kao: Technische Universität Berlin

### SocialAgent: Second Workshop on Large Language Models for Social Reasoning and Simulation

- **[Measuring Model-Specific Alignment Drift in LLM-Based Opinion Dynamics](https://openreview.net/forum?id=cXGU9jM24P)** (Poster)  
  **Natasa Djurdjevac Conrad**, **Sebastian Pokutta**, **Christof Schuette**  
  Berlin: Natasa Djurdjevac Conrad: Zuse Institute Berlin (ZIB); Sebastian Pokutta: Zuse Institute Berlin (ZIB); Christof Schuette: Freie Universität Berlin

### Symmetry and Geometry in Neural Representations NeurIPS Workshops 2026

- **[Cup and Cap Topological Neural Network](http://arxiv.org/abs/2610.03169v2)**  
  Marta Niedostatek, Ferran Hernandez Caralt, Runyue Wang, Federica Baccini, **Lorenzo Giambagli**, Pietro Lió, Ginestra Bianconi  
  Berlin: Lorenzo Giambagli: Freie Universität Berlin
- **[Curvature Under Attack in hZACH-ViT: Gauge Symmetry, Boundary Saturation, and Adversarial Failure](http://arxiv.org/abs/2610.00680v1)**  
  **Athanasios Angelakis**, **Marta Gomez-Barrero**  
  Berlin: Athanasios Angelakis: CODE University of Applied Sciences; Marta Gomez-Barrero: CODE University of Applied Sciences

### The Third Workshop on Agents in the Wild: Safety, Security, and Beyond

- **[Benchmarking Exploration Hacking Propensity in Frontier LLMs](https://openreview.net/forum?id=pB2J4VT5np)**  
  **Eduard Hübner**, Nina Żukowska, Alexander Panfilov, Joschka Braun  
  Berlin: Eduard Hübner: Technische Universität Berlin
- **[CryptHarness: A Harness for Agent-Assisted Cryptanalytic Research](https://openreview.net/forum?id=veg4aAUG1o)**  
  **Nico Pelleriti**, Nicolai Kraus, Alexander May, **Sebastian Pokutta**  
  Berlin: Nico Pelleriti: Zuse Institute Berlin (ZIB); Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB)

### Transitioning from Pre-training to Post-training

- **[Stress-Testing RL-based Capability Elicitation with Randomized Underperformance](https://openreview.net/forum?id=i1t40MtDWJ)**  
  Nina Żukowska, **Eduard Hübner**, Alexander Panfilov, Joschka Braun  
  Berlin: Eduard Hübner: Technische Universität Berlin

### Trustworthy AI for Good (AI4GOOD) Workshop

- **[Benchmarking Exploration Hacking Propensity in Frontier LLMs](https://openreview.net/forum?id=2Uuwb3EjHC)** (Oral)  
  **Eduard Hübner**, Nina Żukowska, Alexander Panfilov, Joschka Braun  
  Berlin: Eduard Hübner: Technische Universität Berlin
- **[Cooperative Words, Selfish Actions: How Strategic Optimization Shapes LLMs' Interaction With Humans](https://openreview.net/forum?id=8ALoaV3h8Y)** (Poster)  
  **Yaomin Jiang**, Yannik Keller, **Levin Brinkmann**, Tobias Werner, Seyed Ali Alhosseini, Michiel Bakker, Jean-François Bonnefon, **Iyad Rahwan**  
  Berlin: Yaomin Jiang: Max Planck Institute for Human Development; Levin Brinkmann: Max Planck Institute for Human Development; Iyad Rahwan: Max Planck Institute for Human Development
- **[Helpful Allies, Better Liars: RL-Trained Agents Meet Human Social Deduction Experts](https://openreview.net/forum?id=b6qr4xLrOh)** (Oral)  
  Yannik Keller, **Levin Brinkmann**, **Thomas F Eisenmann**, **Iyad Rahwan**  
  Berlin: Levin Brinkmann: Max Planck Institute for Human Development; Thomas F Eisenmann: Max Planck Institute for Human Development; Iyad Rahwan: Max Planck Institute for Human Development
- **[Stress-Testing RL-based Capability Elicitation with Randomized Underperformance](https://openreview.net/forum?id=BX4DQc8Ge2)** (Poster)  
  Nina Żukowska, **Eduard Hübner**, Alexander Panfilov, Joschka Braun  
  Berlin: Eduard Hübner: Technische Universität Berlin

### Who Verifies the Agents? Toward Reliable Agent Development

- **[Safety Signals to Verify NetOps Agents with Action-Level Granularity](https://openreview.net/forum?id=jsKXBu5m95)**  
  **Tobias Labarta**, **Frederik Pahde**, Novak Boskov, **Maximilian Dreyer**, David Birkenberger, Manzoor A Khan, **Sebastian Lapuschkin**, **Wojciech Samek**  
  Berlin: Tobias Labarta: Fraunhofer Heinrich Hertz Institute (HHI); Frederik Pahde: Fraunhofer Heinrich Hertz Institute (HHI); Maximilian Dreyer: Fraunhofer Heinrich Hertz Institute (HHI); Sebastian Lapuschkin: Fraunhofer Heinrich Hertz Institute (HHI); Wojciech Samek: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin
- **[When Tool Calls Succeed but Workflows Fail: Anomalies at the Agent-Tool Boundary](https://openreview.net/forum?id=5oH0v1T8k9)**  
  **Artem Trofimov**, Boris Novikov  
  Berlin: Artem Trofimov: AVIV Group, Berlin

### Workshop on Evaluation of Interactive Agents

- **[Benchmarking Exploration Hacking Propensity in Frontier LLMs](https://openreview.net/forum?id=QFmltUNNgv)**  
  **Eduard Hübner**, Nina Żukowska, Alexander Panfilov, Joschka Braun  
  Berlin: Eduard Hübner: Technische Universität Berlin

### Workshop on Resource-Aware Agentic AI

- **[When Does LLM Orchestration Pay Off? A Controlled Evaluation of Accuracy, Resources, and Task Difficulty](https://openreview.net/forum?id=uYMdB2Jzk1)**  
  **Nicolas Leins**, **Nico Pelleriti**, **Jana Gonnermann-Müller**, **Sebastian Pokutta**  
  Berlin: Nicolas Leins: Zuse Institute Berlin (ZIB); Nico Pelleriti: Zuse Institute Berlin (ZIB); Jana Gonnermann-Müller: Zuse Institute Berlin (ZIB); Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB)

### Workshop on the Linguistic Principles for Foundation Models

- **[What Makes a Good Function Vector?](https://openreview.net/forum?id=AV5BgHyVdw)** (Spotlight)  
  **Minh An Pham**, **Anton Segeler**, **Thomas Wiegand**, **Wojciech Samek**, **Sebastian Lapuschkin**, **Patrick Kahardipraja**, **Reduan Achtibat**  
  Berlin: Minh An Pham: Fraunhofer Heinrich Hertz Institute (HHI); Anton Segeler: Fraunhofer Heinrich Hertz Institute (HHI); Thomas Wiegand: Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin; Wojciech Samek: Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin; Sebastian Lapuschkin: Fraunhofer Heinrich Hertz Institute (HHI); Patrick Kahardipraja: Fraunhofer Heinrich Hertz Institute (HHI); Reduan Achtibat: Fraunhofer Heinrich Hertz Institute (HHI)

### Workshop on Towards Test-Time Continual Learning Agents

- **[AlphaDiana: A System for Evaluating Reasoning Agents](https://openreview.net/forum?id=0ip2veRcDa)** (Poster)  
  Zhanke Zhou, Zongze Li, Weikai Huang, Xuan Li, Chentao Cao, Xiao Feng, Xiangyu Lu, Jinbo Hu, Menghan Lu, Yi Xie, **Nico Pelleriti**, Shiyang Liu, **Max Zimmer**, Brando Miranda, Jiangchao Yao, Bo Liu, Sanmi Koyejo, **Sebastian Pokutta**, Bo Han  
  Berlin: Nico Pelleriti: Zuse Institute Berlin (ZIB); Max Zimmer: Technische Universität Berlin / Zuse Institute Berlin (ZIB); Sebastian Pokutta: Technische Universität Berlin / Zuse Institute Berlin (ZIB)

### XAI4science: Knowledge Discovery and Trust through Interpretable Foundation Models

- **[Beyond Post-Hoc Saliency: Assessing Mechanistic Representation Interventions in a Deep Learning Weather Model](https://openreview.net/forum?id=uae6iYb1hw)**  
  Philine L Bommer, Marlene Kretschmer, Emma Kasteleyn, **Anna Hedström**, Ana Lucic, Fanny Lehmann, Marina Höhne  
  Berlin: Anna Hedström: Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin
- **[Evaluating and Improving Concept Prediction Models for Histopathological Discovery](https://openreview.net/forum?id=4I17sCFvjq)**  
  **Julius Hense**, Daniel C. Castro, Shruthi Bannur, **Farnoush Rezaei Jafari**, Daniel Shao, Eric Zimmermann, Kristen Severson, Drew Williamson, Stephanie Hyland, Tristan Lazard, Kenza Bouzid  
  Berlin: Julius Hense: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Technische Universität Berlin; Farnoush Rezaei Jafari: Technische Universität Berlin
- **[Value or Attention: Investigating Layer-wise Relevance Propagation for Graph Attention Networks](https://openreview.net/forum?id=baqw0BWzmX)**  
  **Ken Schreiber**, **René P. Klausen**, **Sebastian Lapuschkin**, **Wojciech Samek**, **Jonas Naujoks**  
  Berlin: Ken Schreiber: Fraunhofer Heinrich Hertz Institute (HHI); René P. Klausen: Fraunhofer Heinrich Hertz Institute (HHI); Sebastian Lapuschkin: Fraunhofer Heinrich Hertz Institute (HHI); Wojciech Samek: BIFOLD – Berlin Institute for the Foundations of Learning and Data / Fraunhofer Heinrich Hertz Institute (HHI) / Technische Universität Berlin; Jonas Naujoks: Fraunhofer Heinrich Hertz Institute (HHI)

## Reproducibility Track (MLRC)

- **[Evaluating the evidence trace of NeurIPS 2025 contributions with agentic code auditing](https://neurips.cc/virtual/2026/session/137650)** (Poster)  
  **Pascal Iversen**, Ferdous Nasri, Bernhard Y. Renard, Katharina Baum  
  Berlin: Pascal Iversen: Freie Universität Berlin
