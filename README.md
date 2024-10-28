<br>
<p align="center">
<h1 align="center"><strong>Paper list for World Model</strong></h1>
</p>

<p align="center">
<img src="./fig/World_Model_Illustration.png" width="250">
</p>


#### We appreciate any useful suggestions for improvement of this paper list or survey from peers. Please raise issues or send an email to **yiranqin@link.cuhk.edu.cn**. Thanks for your cooperation! We also welcome your pull requests for this project!


<p align="center">
<img src="./fig/motivation.png" width="800">
</p>  

## 🏠 About

Before taking action, humans make predictions based on their objectives and observations of the current environment. These predictions manifest in various forms, \eg, textual planning, visual imagination of future scene changes, or even subconscious planning at the action level. Each of these predictive capabilities is critical to the successful completion of tasks. With the development of generative models, agents driven by these models are exhibiting predictive capabilities that enable them to complete embodied tasks by making human-like predictions, high-level planning, image-based guidance, or future video prediction to drive actions. We refer to these models as World Models. Recently, these models have been widely applied across various domains spanning from developing agents to solve inference tasks to leveraging predictions for driving robots to perform specific actions.

## :collision: Update Log 

* [2024.12.10] We release the first version of the paper list for Embodied AI. This page is continually updating!



## <a id="table-of-contents">📚 Table of Contents </a>

- [Books & Surveys](#books-surveys)
- [Foundation Model](#Foundation-Model)
- [General World Model](#General-World-Model)
- [Autonomous Driving](#Autonomous-Driving)
- [Robot Manipulation](#Robot-Manipulation)
- [Indoor Navigation](#Indoor-Navigation)
- [World Model Safty](#World-Model-Safty)
- [Social Simulation](#Social-Simulation)
- [Multi-Agent World Model](#Multi-Agent)

## <a id="books-surveys"> Books & Surveys <a href="#table-of-contents">🔝</a> </a> 

* **Multimodal Large Models: The New Paradigm of Artificial General Intelligence**, Publishing House of Electronics Industry (PHE), 2024       
Yang Liu, Liang Lin             
[[Page](https://hcplab-sysu.github.io/Book-of-MLM/)]      


## <a id="Foundation-Model"> Foundation Model <a href="#table-of-contents">🔝</a> </a>
The construction of world models often relies on various fundamental models.

### Text Generation
* [LLaMA] **LLaMA: Open and Efficient Foundation Language Models** [[arxiv](https://arxiv.org/abs/2302.13971)]
* [PaLM] **PaLM: Scaling Language Modeling with Pathways** [[arxiv](https://arxiv.org/pdf/2204.02311)]
* [PaLM-E] **PaLM-E: An Embodied Multimodal Language Model** [[arxiv](https://palm-e.github.io/)]
* [LLaVA] **Visual Instruction Tuning** [[NIPS2023](https://palm-e.github.io/)]
### Image Generation
* [SDXL] **Sdxl: Improving latent diffusion models for high-resolution image synthesis** [[arxiv](https://arxiv.org/pdf/2307.01952)]
* [PixArt-α] **PixArt-α: Fast Training of Diffusion Transformer for Photorealistic Text-to-Image Synthesis** [[ICLR2024](https://arxiv.org/pdf/2310.00426)]
* [Show-o] **Show-o: One single transformer to unify multimodal understanding and generation** [[arxiv](https://arxiv.org/pdf/2408.12528)]
### Video Generation
* [ModelScope] **ModelScope Text-to-Video Technical Report** [[arxiv](https://arxiv.org/pdf/2308.06571)]
* [VideoCrafter] **VideoCrafter1: Open Diffusion Models for High-Quality Video Generation** [[arxiv](https://arxiv.org/pdf/2310.19512)]
* [DynamiCrafter] **DynamiCrafter: Animating Open-domain Images with Video Diffusion Priors** [[ECCV2024](https://arxiv.org/abs/2310.12190)]
* [CogVideoX] **CogVideoX: Text-to-Video Diffusion Models with An Expert Transformer** [[arxiv](https://arxiv.org/abs/2408.06072)]
* [Open-Sora Plan] [[project](https://github.com/PKU-YuanGroup/Open-Sora-Plan)]
## <a id="General-World-Model"> General World Model <a href="#table-of-contents">🔝</a> </a> 

General World Model aims at representing and simulating wide range of situations and interactions, especically those encountered in the real world.

* [Gen-2] **Gen-2: Generate novel videos with text, images or video clips**. [[project](https://runwayml.com/research/gen-2)]
* [Gen-3-Alpha] **Gen-3 Alpha: A New Frontier for Video Generation**. [[project](https://runwayml.com/research/introducing-gen-3-alpha)]
* [Pandora] **Pandora: Towards General World Model with Natural Language Actions and Video States** [[arxiv](https://arxiv.org/pdf/2406.09455)]
* [DreamerV3] **Mastering Diverse Domains through World Models** [[arxiv](https://arxiv.org/pdf/2301.04104)]
* [TD-MPC2] **TD-MPC2: Scalable, Robust World Models for Continuous Control** [[ICLR2024](https://arxiv.org/pdf/2310.16828)]
* [UniSim] **Learning Interactive Real-World Simulators** [[ICLR2024](https://ai-data-base.com/wp-content/uploads/2023/10/2310.06114_compressed.pdf)]
* [General-World-Models-Survey] **Is Sora a World Simulator? A Comprehensive Survey on General World Models and Beyond** [[project](https://arxiv.org/pdf/2405.03520)]
* [3D-VLA] **3D-VLA: A 3D Vision-Language-Action Generative World Model** [[ICML2024](https://arxiv.org/pdf/2403.09631)]

## <a id="Autonomous-Driving"> Autonomous Driving <a href="#table-of-contents">🔝</a> </a> 

### Action Generation
* **Driving with LLMs: Fusing Object-Level Vector Modality for Explainable Autonomous Driving.** [[ICRA](https://arxiv.org/pdf/2310.01957)]
* [LanguageMPC] **LanguageMPC: Large Language Models as Decision Makers for Autonomous Driving.** [[arxiv](https://arxiv.org/abs/2310.03026)]
* [DriveMLM] **DriveMLM: Aligning Multi-Modal Large Language Models with Behavioral Planning States for Autonomous Driving.** [[arxiv](https://arxiv.org/abs/2312.09245)]
* [DriveLM] **DriveLM: Driving with Graph Visual Question Answering.** [[ECCV2024](https://github.com/OpenDriveLab/DriveLM)]
* [LMDrive] **LMDrive: Closed-Loop End-to-End Driving with Large Language Models.** [[CVPR2024](https://github.com/opendilab/LMDrive)]
* [DiLu] **DiLu: A Knowledge-Driven Approach to Autonomous Driving with Large Language Models.** [[ICLR2024](https://arxiv.org/abs/2309.16292)]
* [DriveVLM] **DriveVLM: The Convergence of Autonomous Driving and Large Vision-Language Models.** [[CoRL2024](https://tsinghua-mars-lab.github.io/DriveVLM/)]
* [LeapAD] **Continuously Learning, Adapting, and Improving: A Dual-Process Approach to Autonomous Driving.** [[NIPS2024](https://arxiv.org/abs/2405.15324)]
* [AD-H] **AD-H: Autonomous Driving with Hierarchical Agents.** [[arxiv](https://arxiv.org/abs/2406.03474)]
* [Think2Drive] **Think2Drive: Efficient Reinforcement Learning by Thinking in Latent World Model for Quasi-Realistic Autonomous Driving (in CARLA-v2).** [[ECCV2024](https://arxiv.org/abs/2402.16720)]





### Future Generation
* [GAIA-1] **GAIA-1: A generative world model for autonomous driving.** [[arxiv](https://arxiv.org/abs/2309.17080)]
* [MagicDrive] **MagicDrive: Street View Generation with Diverse 3D Geometry Control.** [[ICLR2024](https://github.com/cure-lab/MagicDrive)]
* [DriveDiffusion] **DrivingDiffusion: Layout-Guided multi-view driving scene video generation with latent diffusion model.** [[ECCV2024](https://arxiv.org/abs/2310.07771)]
* [OCCWorld] **OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving.** [[ECCV2024](https://arxiv.org/abs/2311.16038)]
* [Vista] **Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability.** [[NIPS2024]]


### Future Generation for Action
* [ADriver-I] **ADriver-I: A General World Model for Autonomous Driving** [[arxiv](https://arxiv.org/abs/2311.13549)]
* [GenAD] **GenAD: Generative End-to-End Autonomous Driving.** [[ECCV2024](https://arxiv.org/abs/2402.11502)]
* [DriveDreamer] **DriveDreamer: Towards Real-world-driven World Models for Autonomous Driving.** [[ECCV2024](https://arxiv.org/abs/2309.09777)]
* [DriveDreamer-2] **DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation.** [[arxiv](https://drivedreamer2.github.io)]
* [NeMo] **Neural Volumetric World Models for Autonomous Driving.** [[ECCV2024](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02571.pdf)]
* [ViDAR] **Visual Point Cloud Forecasting enables Scalable Autonomous Driving.** [[CVPR2024](https://github.com/OpenDriveLab/ViDAR)]
* [Drive-WM] **Driving into the Future: Multiview Visual Forecasting and Planning with World Model for Autonomous Driving.** [[CVPR2024](https://github.com/BraveGroup/Drive-WM)]
* [DriveWorld] **DriveWorld: 4D Pre-trained Scene Understanding via World Models for Autonomous Driving.** [[CVPR2024](https://arxiv.org/abs/2405.04390)]




## <a id="Robot-Manipulation"> Robot Manipulation <a href="#table-of-contents">🔝</a> </a> 
* [PlaNet] **Learning Latent Dynamics for Planning from Pixels**. [[ICML2019](https://proceedings.mlr.press/v97/hafner19a/hafner19a.pdf)]
* [Dreamer] **Dream to Control: Learning Behaviors by Latent Imagination**. [[ICLR2020](https://arxiv.org/pdf/1912.01603)]
* [DreamerV2] **Mastering Atari with discrete world models**. [[ICLR2021](https://arxiv.org/pdf/2010.02193)]
* [DreamerV3] **Mastering Diverse Domains through World Models**. [[arxiv](https://arxiv.org/pdf/2301.04104v2)]

* [Plan2Explore] **Planning to Explore via Self-Supervised World Models**. [[ICML2020](https://proceedings.mlr.press/v119/sekar20a/sekar20a.pdf)]

* [RoboDreamer] **Learning Compositional World Models for Robot Imagination**. [[ICML2024](https://arxiv.org/pdf/2404.12377)]
* [SWIM] **Structured World Models from Human Videos**. [[RSS2023](https://arxiv.org/pdf/2308.10901)]
* [FOWM] **Finetuning Offline World Models in the Real World**. [[CoRL2023](https://arxiv.org/pdf/2310.16029)]
* [STEDIE] **Interaction-based Disentanglement of Entities for Object-centric World Models**. [[ICLR2023](https://openreview.net/pdf?id=JQc2VowqCzz)]

* [MWM] **Masked World Models for Visual Control**. [[CoRL2022](https://proceedings.mlr.press/v205/seo23a/seo23a.pdf)]

* [CEE-US] **Curious Exploration via Structured World Models Yields Zero-Shot Object Manipulation**. [[NeurIPS2022](https://proceedings.neurips.cc/paper_files/paper/2022/file/98ecdc722006c2959babbdbdeb22eb75-Paper-Conference.pdf)]

* [MV-MWM] **Multi-View Masked World Models for Visual Robotic Manipulation**. [[ICML2023](https://proceedings.mlr.press/v202/seo23a/seo23a.pdf)]
* [ContextWM] **Pre-training Contextualized World Models with In-the-wild Videos for Reinforcement Learning**. [[NeurIPS2023](https://proceedings.neurips.cc/paper_files/paper/2023/file/7ce1cbededb4b0d6202847ac1b484ee8-Paper-Conference.pdf)]

* [DayDreamer] **DayDreamer: World Models for Physical Robot Learning**. [[CoRL2022](https://proceedings.mlr.press/v205/wu23c/wu23c.pdf)]






## <a id="Indoor-Navigation"> Indoor Navigation <a href="#table-of-contents">🔝</a> </a> 

* [Pathdreamer] **Pathdreamer: A World Model for Indoor Navigation** [[ICCV2021](https://openaccess.thecvf.com/content/ICCV2021/papers/Koh_Pathdreamer_A_World_Model_for_Indoor_Navigation_ICCV_2021_paper.pdf)]
* [Panogen] **Panogen: Text-conditioned panoramic environment generation for vision-and-language navigation** [[NeurIPS2023](https://proceedings.neurips.cc/paper_files/paper/2023/file/4522de4178bddb36b49aa26efad537cf-Paper-Conference.pdf)]
* [Dreamwalker] **Dreamwalker: Mental planning for continuous vision-language navigation** [[ICCV2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_DREAMWALKER_Mental_Planning_for_Continuous_Vision-Language_Navigation_ICCV_2023_paper.pdf)]


## <a id="World-Model-Safty"> World Model Safety <a href="#table-of-contents">🔝</a> </a> 
### Definition
* [GSAI] **Towards Guaranteed Safe AI: A Framework for Ensuring Robust and Reliable AI Systems** [[arxiv](https://arxiv.org/pdf/2405.06624)]

### Safety Evaluation
* [LlamaGuard] **Llama guard: Llm-based input-output safeguard for human-ai conversations** [[arxiv](https://arxiv.org/pdf/2312.06674)]
* [Llama Guard 3 Vision] **Meta Llama Guard 3 Vision** [[huggingface](https://github.com/meta-llama/PurpleLlama/blob/main/Llama-Guard3/11B-vision/MODEL_CARD.md)]

### Safety Benchmark
* [SPA-VL] **SPA-VL: A Comprehensive Safety Preference Alignment Dataset for Vision Language Model** [[arxiv](https://arxiv.org/pdf/2406.12030)]

* [SafeBench] **SafeBench: A Benchmarking Platform for Safety Evaluation of Autonomous Vehicles** [[NIPS2022](https://proceedings.neurips.cc/paper_files/paper/2022/file/a48ad12d588c597f4725a8b84af647b5-Paper-Datasets_and_Benchmarks.pdf)]

* [Beavertails] **Beavertails: Towards improved safety alignment of llm via a human-preference dataset** [[NIPS2023](https://proceedings.neurips.cc/paper_files/paper/2023/file/4dbb61cb68671edc4ca3712d70083b9f-Paper-Datasets_and_Benchmarks.pdf)]

* [Salad-bench] **Salad-bench: A hierarchical and comprehensive safety benchmark for large language models** [[ACL2024 Findings](https://arxiv.org/pdf/2402.05044)]


### Attack
* [GCG] **Universal and transferable adversarial attacks on aligned language models** [[arxiv](https://arxiv.org/pdf/2307.15043)]

* [COLD-Attack] **COLD-Attack: Jailbreaking LLMs with Stealthiness and Controllability** [[arxiv](https://arxiv.org/pdf/2402.08679)]

* [-] **From LLMs to MLLMs: Exploring the Landscape of Multimodal Jailbreaking** [[arxiv](https://arxiv.org/pdf/2406.14859)]

* [Agent Smith] **Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast** [[arxiv](https://arxiv.org/pdf/2402.08567)]

### Safety enhancement
* [MLLM-Protector] **MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance** [[paper](https://arxiv.org/pdf/2401.02906)]

* [Adversarial Tuning] **Adversarial Tuning: Defending Against Jailbreak Attacks for LLMs** [[arxiv](https://arxiv.org/pdf/2406.06622)]


## <a id="Social-Simulation"> Social Simulation <a href="#table-of-contents">🔝</a> </a> 

- Generative Agents: Interactive Simulacra of Human Behavior[[paper](https://arxiv.org/abs/2304.03442)]

- $S^3$: Social-network Simulation System with Large Language Model-Empowered Agents[[paper](https://arxiv.org/abs/2307.14984)]

- Multi-Agent Consensus Seeking via Large Language Models[[paper](https://arxiv.org/abs/2310.20151)]
- Lyfe Agents: Generative agents for low-cost real-time social interactions[[paper](https://arxiv.org/abs/2310.02172)]
- Quantifying the Impact of Large Language Models on Collective Opinion Dynamics[[paper](https://arxiv.org/abs/2308.03313)]
- CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society[[NIPS2023]](https://arxiv.org/abs/2303.17760)
- Theory of Mind for Multi-Agent Collaboration via Large Language Models[[EMNLP2023](https://arxiv.org/abs/2310.10701)]
- Can Large Language Models Transform Computational Social Science?[[paper](https://arxiv.org/abs/2305.03514)]

## <a id="Multi-Agent"> Multi-Agent World Model <a href="#table-of-contents">🔝</a> </a> 

* [COMBO] **COMBO: Compositional World Models for Embodied Multi-Agent Cooperation.** [[arxiv](https://arxiv.org/abs/2404.10775)]







## 👏 Acknowledgements

