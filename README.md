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


## <a id="Robot-Manipulation"> Robot Manipulation <a href="#table-of-contents">🔝</a> </a> 
* [PlaNet] **Learning Latent Dynamics for Planning from Pixels**. [[ICML2019](https://proceedings.mlr.press/v97/hafner19a/hafner19a.pdf)]
* [Dreamer] **Dream to Control: Learning Behaviors by Latent Imagination**. [[ICLR2020](https://arxiv.org/pdf/1912.01603)]
* [DreamerV2] **Mastering Atari with discrete world models**. [[ICLR2021](https://arxiv.org/pdf/2010.02193)]
* [DreamerV3] **Mastering Diverse Domains through World Models**. [[arxiv](https://arxiv.org/pdf/2301.04104v2)]

* [Plan2Explore] **Planning to Explore via Self-Supervised World Models**. [[NeurIPS2019](https://proceedings.mlr.press/v119/sekar20a/sekar20a.pdf)]

* [RoboDreamer] **Learning Compositional World Models for Robot Imagination**. [[arxiv](https://arxiv.org/pdf/2404.12377)]
* [SWIM] **Structured World Models from Human Videos**. [[arxiv](https://arxiv.org/pdf/2308.10901)]
* [FOWM] **Finetuning Offline World Models in the Real World**. [[arxiv](https://arxiv.org/pdf/2310.16029)]
* [STEDIE] **Interaction-based Disentanglement of Entities for Object-centric World Models**. [[ICLR2023](https://openreview.net/pdf?id=JQc2VowqCzz)]

* [MWM] **Masked World Models for Visual Control**. [[CoRL2023](https://proceedings.mlr.press/v205/seo23a/seo23a.pdf)]

* [CEE-US] **Curious Exploration via Structured World Models Yields Zero-Shot Object Manipulation**. [[paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/98ecdc722006c2959babbdbdeb22eb75-Paper-Conference.pdf)]

* [MV-MWM] **Multi-View Masked World Models for Visual Robotic Manipulation**. [[NeurIPS2022](https://proceedings.mlr.press/v202/seo23a/seo23a.pdf)]
* [ContextWM] **Pre-training Contextualized World Models with In-the-wild Videos for Reinforcement Learning**. [[NeurIPS2024](https://proceedings.neurips.cc/paper_files/paper/2023/file/7ce1cbededb4b0d6202847ac1b484ee8-Paper-Conference.pdf)]

* [DayDreamer] **DayDreamer: World Models for Physical Robot Learning**. [[CoRL2023](https://proceedings.mlr.press/v205/wu23c/wu23c.pdf)]






## <a id="Indoor-Navigation"> Indoor Navigation <a href="#table-of-contents">🔝</a> </a> 

* [Pathdreamer] **Pathdreamer: A World Model for Indoor Navigation** [[ICCV2021](https://openaccess.thecvf.com/content/ICCV2021/papers/Koh_Pathdreamer_A_World_Model_for_Indoor_Navigation_ICCV_2021_paper.pdf)]
* [Panogen] **Panogen: Text-conditioned panoramic environment generation for vision-and-language navigation** [[NeurIPS2023](https://proceedings.neurips.cc/paper_files/paper/2023/file/4522de4178bddb36b49aa26efad537cf-Paper-Conference.pdf)]
* [Dreamwalker] **Dreamwalker: Mental planning for continuous vision-language navigation** [[ICCV2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_DREAMWALKER_Mental_Planning_for_Continuous_Vision-Language_Navigation_ICCV_2023_paper.pdf)]


## <a id="World-Model-Safty"> World Model Safty <a href="#table-of-contents">🔝</a> </a> 
### Safety Evaluation

### Safety Benchmark
SPA-VL: A Comprehensive Safety Preference Alignment Dataset for Vision Language Model[[paper](https://arxiv.org/abs/2406.12030)]


SafeBench: A Benchmarking Platform for Safety Evaluation of Autonomous Vehicles[[paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/a48ad12d588c597f4725a8b84af647b5-Paper-Datasets_and_Benchmarks.pdf)]


### Attack
From LLMs to MLLMs: Exploring the Landscape of Multimodal Jailbreaking[[paper](https://arxiv.org/abs/2406.14859)]

Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast[[paper](https://arxiv.org/abs/2402.08567)]

### Safety enhancement
MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance[[paper](https://arxiv.org/abs/2401.02906)]

## <a id="Social-Simulation"> Social Simulation <a href="#table-of-contents">🔝</a> </a> 

## <a id="Multi-Agent"> Multi-Agent World Model <a href="#table-of-contents">🔝</a> </a> 

* [COMBO] **COMBO: Compositional World Models for Embodied Multi-Agent Cooperation.** [[arxiv](https://arxiv.org/abs/2404.10775)]


   

 


## 👏 Acknowledgements

