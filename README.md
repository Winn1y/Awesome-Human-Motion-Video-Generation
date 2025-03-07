<h1 align="center">🎉 Awesome-Human-Motion-Video-Generation 🔥</h1>

---

<p align="center">
     <a href="assets/Human Motion Video Generation A Survey.pdf">
<img width="768px" alt="image" src="assets/logoGithub.png">
</p>
    
<p align="center">
<a href='assets/Human Motion Video Generation A Survey.pdf'>
<img src='https://img.shields.io/badge/TechRxiv-PDF-green?style=flat&logo=TechRxiv&logoColor=green' alt='TechRxiv PDF'>
</a>
<img src='https://img.shields.io/badge/Awesome Survey-8A2BE2' alt='Survey'>
<img src='https://img.shields.io/badge/Related Work-262+ Papers and 64+ Datasets-blue' alt='MorePapers'>
<br>
<img src='https://img.shields.io/badge/Under Review-4BC88C' alt='under'>
<img src='https://img.shields.io/badge/Update 🔥-2025.03.07-red' alt='MorePapers'>
<a href='https://zhuanlan.zhihu.com/p/2672965087'>
<img src='https://img.shields.io/badge/知乎-论文笔记-0084ff?style=flat&logo=zhihu&logoColor=yellow' alt='知乎文章'>
</a>
<br>
<br>
You can click on <b><img width="16" src="https://img.icons8.com/emoji/48/FFD700/eyes-emoji.png" alt="Watch Icon"/> Watch</b> and <b><img width="16" src="https://img.icons8.com/emoji/48/FFD700/star-emoji.png" alt="Star Icon"/> Star</b> to get the latest updates at any time.
<br>
<br>
<b><img width="16" src="https://img.icons8.com/emoji/48/FFD700/eyes-emoji.png" alt="Watch Icon"/> Watch</b> Me ! <b><img width="16" src="https://img.icons8.com/emoji/48/FFD700/eyes-emoji.png" alt="Watch Icon"/> Watch</b> Me ! <b><img width="16" src="https://img.icons8.com/emoji/48/FFD700/eyes-emoji.png" alt="Watch Icon"/> Watch</b> Me ! 
<br>
<b><img width="16" src="https://img.icons8.com/emoji/48/FFD700/star-emoji.png" alt="Star Icon"/> Star</b> Me ! <b><img width="16" src="https://img.icons8.com/emoji/48/FFD700/star-emoji.png" alt="Star Icon"/> Star</b> Me ! <b><img width="16" src="https://img.icons8.com/emoji/48/FFD700/star-emoji.png" alt="Star Icon"/> Star</b> Me !

---

<details><summary>🎁 >>>>>>>> [English Introduction] <<<<<<<<<< </summary>


> This project provides a thorough summary of the latest advancements in the field of 2D digital human motion video generation, covering papers, datasets, and code repositories.
> 
> The repository is organized into three main conditions: Vision-driven, Text-driven, and Audio-driven, while also considering LLM Planning Papers.
>
> Unlike previous summaries, this project clearly outlines the five key stages in the field of digital human video generation:
> 
> 🌑 Stage 1: Input Phase. Clarifying the driving source (Vision, Text, Audio) and driving region (Part, Holistic), where "Part" mainly refers to the face;
> 
> 🌒 Stage 2: Motion planning Phase. Most work involves feature mapping to learn motion mappings, while a few works use large language models (LLMs) for motion planning;
> 
> 🌓 Stage 3: Motion Video Generation Phase;
> 
> 🌔 Stage 4: Video Refinement Phase, focusing on optimizing specific parts such as the face, lips, teeth, and hands;
> 
> 🌕 Stage 5: Acceleration Phase, aiming to speed up training and deployment inference as much as possible, with the goal of achieving real-time output.
> 
> 🎉 We welcome everyone to contribute your research and submit PRs to collectively advance the technology of human motion video generation. 
> 
> If you have any questions, feel free to contact us at (**WinniyGD@outlook.com**), and we will respond as soon as possible. Additionally, we warmly welcome new members from related fields to join us, learn together, and make endless progress!

</details>



<details><summary>🏆 >>>>>>>> [🧡中文简要介绍💜] <<<<<<<<<< </summary>

<br>

> 
> 
> 本项目认真总结了👍2D数字人动作视频生成👏相关领域的最新进展，包括论文、数据集和代码库。
> 
> Repo以 Vision-driven、Text-driven、Audio-driven 三大方向作以总结，同时考虑 LLM Planning 前沿论文。
> 
> 分类时，我们定义Audio>Text>Vision优先级，当出现文本不出现音频时，归纳为Text-Driven方法，当文本音频同时出现时，归纳为Audio-Driven方法，以此类推。
> 
> 区别于以往的总结，项目明确总结了数字人视频生成领域的五大阶段：
> 
> 🌑 第1阶段 明确驱动源（Vision、Text、Audio）与驱动区域（Part、Holistic），其中Part主要以脸部为主；
> 
> 🌒 第2阶段 动作规划阶段，大多数工作以特征Mapping学习动作映射，少部分工作以大语言模型LLMs进行动作规划；
> 
> 🌓 第3阶段 人体视频生成，大部分工作以Diffusion Models为基础，少部分工作以Transformer为基础；
> 
> 🌔 第4阶段 视频优化阶段，针对脸部、嘴唇、牙齿、手部单独做Refinement优化；
> 
> 🌕 第5阶段 加速输出阶段，尽可能地加速训练与部署推理，目标Real-Time实时输出。

> 🔑本项目由六位核心成员全力推进：
> 
>     - 薛海威（清华大学，负责人）
>     - 罗向阳（清华大学）
>     - 胡璋昊（爱丁堡大学）
>     - 张鑫（西安交通大学）
>     - 向迅之（中国科学院大学）
>     - 戴语琴（南京理工大学）
> 
> 💖核心综述由以下老师全力支持并悉心指导：
> 
>     - 刘健庄老师（中国科学院深圳先进技术研究院）
>     - 张镇嵩博士（华为诺亚2012实验室）
>     - 李明磊博士（零一万物）
>     - 马飞博士（光明实验室）
>     - 吴志勇老师（清华大学/香港中文大学）


> 另外，非常感谢常恒师兄 ( https://github.com/SwiftieH )、余伟江师兄的支持！


> 🎉 欢迎大家贡献自己的研究成果并PR，共同推动人体运动视频生成技术的发展。
> 
> 如有任何问题，可以随时联系邮件（**WinniyGD@outlook.com**），我们会尽快回复。
> 
> 另外，我们非常欢迎有新的相关领域的同学一同加入我们，一起学习，无限进步！

</details>

---

<p align="center">
🍦 Exploring the latest papers in human motion video generation. 🍦
<br>
<br>
<br>
<img src="assets/pipeline.png" width="768px"/>
</p>

<br>



---


## Introduction

This work delves into Human Motion Video Generation, covering areas such as Portrait Animation, Dance Video Generation, Text2Face, Text2MotionVideo, and Talking Head. We believe this will be the most comprehensive survey to date on human motion video generation technologies. Please stay tuned! 😘😁😀

It's important to note that for the sake of clarity, we have excluded 3DGS and NeRF technologies (2D-3D-2D) from the scope of this paper.

### ✨You are welcome to provide us your work with a topic related to human motion video generation.✨

If you discover any missing work or have any suggestions, 

please feel free to submit a pull request or contact us ( WinniyGD@outlook.com ). 

We will promptly add the missing papers to this repository.

###  🍔 Highlight 

[1] We decompose human motion video generation into five key phases, covering all subtasks across various driving sources and body regions. To the best of our knowledge, this is the first survey to offer such a comprehensive framework for human motion video generation.

[2] We provide an in-depth analysis of human motion video generation from both motion planning and motion generation perspectives, a
dimension that has been underexplored in existing reviews.

[3] We clearly delineate established baselines and evaluation metrics, offering detailed insights into the key challenges shaping this field.

[4] We present a set of potential future research directions, aimed at inspiring and guiding researchers in the field of human motion video generation.

###  🕑 Timeline

![Timeline](assets/time.png)






## 💙 News




**[2025/03/07] [V7.6 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/): Update Methods.**

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.04067) FREAK: Frequency-modulated High-fidelity and Real-time Audio-driven Talking Portrait Synthesis (Audio, Head Pose Driving)

----




[2025/03/05] [V7.5 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/7.5): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.00740) FaceShot: Bring Any Character into Life (Visual, Portrait Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.01715) KeyFace: Expressive Audio-Driven Facial Animation for Long Sequences via KeyFrame Interpolation (Audio, Head Pose Driving)

----


[2025/02/28] [V7.4 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/7.4): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.19894) High-Fidelity Relightable Monocular Portrait Animation with Lighting-Controllable Video Diffusion Model (Visual, Portrait Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.20387) InsTaG: Learning Personalized 3D Talking Head from Few-Second Video (Audio, Head Pose Driving)

----

[2025/02/26] [V7.3 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/7.3): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.13995) FantasyID: Face Knowledge Enhanced ID-Preserving Video Generation (Text, Text2MotionVideo)



----


[2025/02/25] [V7.2 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/7.2): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.17414) X-Dancer: Expressive Music to Human Dance Video Generation (Audio, Audio-Driven Holistic Body Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.17198) Dimitra: Audio-driven Diffusion model for Expressive Talking Head Generation (Audio, Head Pose Driving)



----


[2025/02/21] [V7.1 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/7.1): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.14178) NeRF-3DTalker: Neural Radiance Field with 3D Prior Aided Audio Disentanglement for Talking Head Synthesis (Audio, Head Pose Driving)




----


[2025/02/18] [V7.0 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/7.0): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.12080) HumanGif: Single-View Human Diffusion with Generative Prior (Visual, Pose-Guided Dance Video Generation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.11515) SayAnything: Audio-Driven Lip Synchronization with Conditional Video Diffusion (Audio, Head Pose Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.10841) SkyReels-A1: Expressive Portrait Animation in Video Diffusion Transformers (Audio, Head Pose Driving)



----


[2025/02/16] [V6.9 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6.9): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.09533) Long-Term TalkingFace Generation via Motion-Prior Conditional Diffusion Model (Audio, Head Pose Driving)





----



[2025/02/13] [V6.8 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6.8): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08189) AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance (Visual, Pose-Guided Dance Video Generation)





----



[2025/02/12] [V6.7 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6.7): Update Methods. Happy 2025 !!🍟

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07239) Contextual Gesture: Co-Speech Gesture Video Generation through Context-aware Gesture Representation (Audio, Audio-Driven Holistic Body Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07203) Playmate: Flexible Control of Portrait Animation via 3D-Implicit Space Guided Diffusion (Audio, Fine-Grained Style and Emotion-Driven Animation)


----



[2025/02/11] [V6.6 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6.6): Update Methods. Happy 2025 !!🍟

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.06145) Animate Anyone 2: High-Fidelity Character Image Animation with Environment Affordance (Visal, Pose-Guided Dance Video Generation)


----

[2025/02/10] [V6.5 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6.5): Update Methods. Happy 2025 !!🍟

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.04847) HumanDiT: Pose-Guided Diffusion Transformer for Long-form Human Motion Video Generation (Visal, Pose2Video)




----

[2025/02/04] [V6.4 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6.4): Update Methods. Happy 2025 !!🍟

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.00654) EmoTalkingGaussian: Continuous Emotion-conditioned Talking Head Synthesis (Audio, Head Pose Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01061) OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models (Audio, Audio-Driven Holistic Body Driving)



----

[2025/02/03] [V6.3 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6.3): Update Methods. Happy 2025 !!🍟

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.18801) Every Image Listens, Every Image Dances: Music-Driven Image Animation (Audio, Audio-Driven Holistic Body Driving)



----



[2025/01/30] [V6.2 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6.2): Update Methods. Happy 2025 !!🍟

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.17718) Learning Semantic Facial Descriptors for Accurate Face Animation (Visual, Portrait Animation)



----


[2025/01/28] [V6.1 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6.1): Update Methods. Happy 2025 !!🍟

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.14646) SyncAnimation: A Real-Time End-to-End Framework for Audio-Driven Human Pose and Talking Head Animation (Audio, Head Pose Driving)



----


[2025/01/24] [V6.0 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6.0): Update Methods. Happy New Year🍟

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.13452) EchoVideo: Identity-Preserving Human Video Generation by Multimodal Feature Fusion (Text, Text2MotionVideo)



----

[2025/01/22] [V5.9 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5.9): Update Methods. Happy New Year🎀

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.11325) CatV2TON: Taming Diffusion Transformers for Vision-Based Virtual Try-On with Temporal Concatenation (Visual, Try-On Video Generation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.10687) EMO2: End-Effector Guided Audio-Driven Avatar Video Generation (Audio, Audio-Driven Holistic Body Driving)


----

[2025/01/20] [V5.8 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5.8): Update Methods. Happy New Year🎀

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.10021) X-Dyna: Expressive Dynamic Human Image Animation (Visual, Pose-Guided Dance Video Generation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.10020) Textoon: Generating Vivid 2D Cartoon Characters from Text Descriptions (Text, Text2Motion)


----

[2025/01/18] [V5.7 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5.7): Update Methods. Happy New Year🎀

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08682) RealVVT: Towards Photorealistic Video Virtual Try-on via Spatio-Temporal Consistency (Visual, Try-On Video Generation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08553) DynamicFace: High-Quality and Consistent Video Face Swapping using Composable 3D Facial Priors (Visual, Portrait Animation)



----

[2025/01/16] [V5.6 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5.6): Update Methods. Happy New Year🎀


[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.06438) Qffusion: Controllable Portrait Video Editing via Quadrant-Grid Attention Learning (Visual, Portrait Animation)


----


[2025/01/14] [V5.5 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5.5): Update Methods. Happy New Year🎀

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.04586) Identity-Preserving Video Dubbing Using Motion Warping (Audio, Lip Synchronization)

----

[2025/01/13] [V5.4 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5.4): Update Methods. Happy New Year🎀

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.01790) Ingredients: Blending Custom Photos with Video Diffusion Transformers (Text, Text2MotionVideo)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03931) Magic Mirror: ID-Preserved Video Generation in Video Diffusion Transformers (Text, Text2MotionVideo)


----

[2025/01/12] [V5.3 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5.3): Update Methods. Happy New Year🎀


[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.01808) MoEE: Mixture of Emotion Experts for Audio-Driven Portrait Animation (Audio, Head Pose Driving)


----

[2025/01/11] [V5.2 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5.2): Update Methods. Happy New Year🎀

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.19860) UniAvatar: Taming Lifelike Audio-Driven Talking Head Generation with Comprehensive Motion and Lighting Control (Audio, Head Pose Driving)

----

[2025/01/10] [V5.1 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5.1): Update Methods. Happy New Year🎀

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.19489) RAIN: Real-time Animation of Infinite Video Stream (Visual, Portrait Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.19645) VideoMaker: Zero-shot Customized Video Generation with the Inherent Force of Video Diffusion Models (Text, Text2Face)

----

[2025/01/06] [V5.0 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5.0): Update Methods. Happy New Year🎀

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.17290) Free-viewpoint Human Animation with Pose-correlated Reference Selection (Visual, Pose-Guided Dance Video Generation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.16212) ManiVideo: Generating Hand-Object Manipulation Video with Dexterous and Generalizable Grasping (Visual, Pose2Video)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.16495) Follow-Your-MultiPose: Tuning-Free Multi-Character Text-to-Video Generation via Pose Guidance (Text, Text2MotionVideo)

----

[2025/01/04] [V4.9 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/4.9): Update Methods. Happy New Year🎀

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14531) Consistent Human Image and Video Generation with Spatially Conditioned Diffusion (Visual, Pose-Guided Dance Video Generation)

----

[2024/12/17] [V4.8 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/4.8): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.11279) VividFace: A Diffusion-Based Hybrid Framework for High-Fidelity Video Face Swapping (Visual, Portrait Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09892) VQTalker: Towards Multilingual Talking Avatars through Facial Motion Tokenization (Audio, Fine-Grained Style and Emotion-Driven Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09822) Dynamic Try-On: Taming Video Virtual Try-on with Dynamic Attention Mechanism (Visual, Try-On Video Generation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.10178) SwiftTry: Fast and Consistent Video Virtual Try-On with Diffusion Models (Visual, Try-On Video Generation)


----

[2024/12/15] [V4.7 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/4.7): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09262) LatentSync: Audio Conditioned Latent Diffusion Models for Lip Sync (Audio, Lip Synchronization)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09296) GoHD: Gaze-oriented and Highly Disentangled Portrait Animation with Rhythmic Poses and Realistic Expression (Audio, Head Pose Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07754) PortraitTalk: Towards Customizable One-Shot Audio-to-Talking Face Generation (Audio, Head Pose Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04000) IF-MDM: Implicit Face Motion Diffusion Model for High-Fidelity Realtime Talking Head Generation (Audio, Head Pose Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04037) INFP: Audio-Driven Interactive Head Generation in Dyadic Conversations (Audio, Head Pose Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04448) MEMO: Memory-Guided Diffusion for Expressive Talking Video Generation (Audio, Head Pose Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09349) DisPose: Disentangling Pose Guidance for Controllable Human Image Animation (Visual, Pose-Guided Dance Video Generation)




----

[2024/12/11] [V4.6 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/4.6): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.03021) PEMF-VVTO: Point-Enhanced Video Virtual Try-on via Mask-free Paradigm (Visual, Try-On Video Generation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.03430) SINGER: Vivid Audio-driven Singing Video Generation with Multi-scale Spectral Diffusion Model (Audio, Head Pose Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01254) EmojiDiff: Advanced Facial Expression Control with High Identity Preservation in Portrait Generation (Visual, Portrait Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00733) Hallo3: Highly Dynamic and Realistic Portrait Image Animation with Diffusion Transformer Networks (Visual, Portrait Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01064) FLOAT: Generative Motion Latent Flow Matching for Audio-driven Talking Portrait (Visual, Portrait Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00397) DreamDance: Animating Human Images by Enriching 3D Geometry Cues from 2D Poses (Visual, Pose-Guided Dance Video Generation)



----

[2024/12/02] [V4.5 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/4.5): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.19525) LokiTalk: Learning Fine-Grained and Generalizable Correspondences to Enhance NeRF-based Talking Head Synthesis (Audio, Head Pose Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.19509) Ditto: Motion-Space Diffusion for Controllable Realtime Talking Head Synthesis (Audio, Head Pose Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.19459) Fleximo: Towards Flexible Text-to-Human Motion Video Generation (Text, Text2MotionVideo)


----

[2024/11/28] [V4.4 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/4.4): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18293) HiFiVFS: High Fidelity Video Face Swapping (Visual, Portrait Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18281) MotionCharacter: Identity-Preserving and Motion Controllable Human Video Generation (Text, Text2Face)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17440) Identity-Preserving Text-to-Video Generation by Frequency Decomposition (Text, Text2Face)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17383) AnchorCrafter: Animate CyberAnchors Saling Your Products via Human-Object Interacting Video Generation (Visual, Pose2Video)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17048) PersonalVideo: High ID-Fidelity Video Customization without Dynamic and Semantic Degradation (Text, Text2Face)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16748) LetsTalk: Latent Diffusion Transformer for Talking Video Synthesis (Audio, Fine-Grained Style and Emotion-Driven Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16726) EmotiveTalk: Expressive Talking Head Generation through Audio Information Decoupling and Emotional Video Diffusion (Audio, Fine-Grained Style and Emotion-Driven Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16331) Sonic: Shifting Focus to Global Audio Perception in Portrait Animation (Audio, Fine-Grained Style and Emotion-Driven Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17697) StableAnimator: High-Quality Identity-Preserving Human Image Animation (Visual, Pose-Guided Dance Video Generation)

----

[2024/11/25] [V4.3 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/4.3): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.15028) FloAt: Flow Warping of Self-Attention for Clothing Animation Generation (Visual, Try-On Video Generation)

----

[2024/11/18] [V4.2 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/4.2): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10061) EchoMimicV2: Towards Striking, Simplified, and Semi-Body Human Animation (Audio, Audio-Driven Holistic Body Driving)

----

[2024/11/15 !WoW! More Star 100 🌟🌟🌟] [V4.1 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/4.1): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.09209) JoyVASA: Portrait and Animal Image Animation with Diffusion-Based Audio-Driven Facial Dynamics and Head Motion Generation (Audio, Fine-Grained Style and Emotion-Driven Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.09268) LES-Talker: Fine-Grained Emotion Editing for Talking Head Generation in Linear Emotion Space (Audio, Fine-Grained Style and Emotion-Driven Animation)


----


[2024/11/14][V4.0 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/4.0): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.08656) MikuDance: Animating Character Art with Mixed Motion Dynamics (Visual, Pose-Guided Dance Video Generation)


----

[2024/11/04][V3.9 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/3.9): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.00225) Fashion-VDM (Visual, Try-On Video Generation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.00652) Towards High-fidelity Head Blending with Chroma Keying for Industrial Applications (Visual, Portrait Animation)

----


[2024/11/01][V3.8 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/3.8): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.23836) Stereo-Talker (Audio, Audio-Driven Holistic Body Driving)


----

[2024/10/29][V3.7 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/3.7): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.20974) MovieCharacter (Visual, Pose2Video)

----

[2024/10/24 Happy Coding Day!][V3.6 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/3.6): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.17262) EmoGene (Audio, Fine-Grained Style and Emotion-Driven Animation)

<a href='https://zhuanlan.zhihu.com/p/2672965087'>
<img src='https://img.shields.io/badge/知乎-论文笔记-0084ff?style=flat&logo=zhihu&logoColor=yellow' alt='知乎文章'>
</a>
Find the Chinese version notes of the survey, welcome to pay attention.

----


[2024/10/21][V3.5 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/3.5): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.14283) Takin-ADA: Emotion Controllable Audio-Driven Animation with Canonical and Landmark Loss Optimization (Audio, Fine-Grained Style and Emotion-Driven Animation)


----

[2024/10/18][V3.4 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/3.4): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13726) DAWN: Dynamic Frame Avatar with Non-autoregressive Diffusion Framework for Talking Head Video Generation (Audio, Head Pose Driving)



----

[2024/10/15][V3.3 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/3.3): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10821) Tex4D (Text, Text2MotionVideo)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10696) TALK-Act: Enhance Textural-Awareness for 2D Speaking Avatar Reenactment with Diffusion Model (Audio, Audio-Driven Holistic Body Driving)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10306) Animate-X: Universal Character Image Animation with Enhanced Motion Representation (Visual, Pose-Guided Dance Video Generation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10122) MuseTalk: Real-Time High Quality Lip Synchronization with Latent Space Inpainting (Audio, Lip Synchronization)



----

[2024/10/11][V3.2 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/3.2): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.07718) Hallo2: Long-Duration and High-Resolution Audio-Driven Portrait Image Animation (Audio, Fine-Grained Style and Emotion-Driven Animation)

----

[2024/10/10][V3.1 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/3.1): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.06734) MimicTalk: Mimicking a personalized and expressive 3D talking face in minutes (Audio, Fine-Grained Style and Emotion-Driven Animation)



----

[2024/10/08][V3.0 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6945e3940e301a095027f4170fead4162c74a2cf): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.04221) TANGO (Audio, Audio-Driven Holistic Body Driving)


----

[2024/10/04]🎉🎉🎉[V2.9 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6945e3940e301a095027f4170fead4162c74a2cf) I'm glad that our article is publicly available on [TechRxiv](https://www.techrxiv.org/users/836049/articles/1228135-human-motion-video-generation-a-survey). We welcome your attention and citations. The version on arXiv is still on hold, and we will update it when it becomes available.

```text
@article{xue2024human,
  title={Human Motion Video Generation: A survey},
  author={Xue, Haiwei and Luo, Xiangyang and Hu, Zhanghao and Zhang, Xin and Xiang, Xunzhi and Dai, Yuqin and Liu, Jianzhuang and Zhang, Zhensong and Li, Minglei and Yang, Jian and others},
  journal={Authorea Preprints},
  year={2024},
  publisher={Authorea}
  doi={10.36227/techrxiv.172793202.22697340/v1}
}
```


----



[2024/10/03][V2.8 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/8032833cda3433cd611df9482405755277fc9843): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.00990) LaDTalk: Latent Denoising for Synthesizing Talking Head Videos with High Frequency Details (Audio, Head Pose Driving)




----

[2024/10/02][V2.7 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/7145d2c803c87db4eae4157b73128e36e854f306): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.19911) Replace Anyone in Videos (Visual, Video-Guided Dance Video Generation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.19580) High Quality Human Image Animation using Regional Supervision and Motion Blur Condition (Visual, Pose-Guided Dance Video Generation)


----


[2024/09/27][V2.6 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/2f4d88b7cfe0b2374895a62a85425fc4c74eeb73): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.18083) SVP (Visual, Portrait Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.17674) Self-Supervised Learning of Deviation in Latent Representation for Co-speech Gesture Video Generation (Audio, Audio-Driven Holistic Body Driving)



----


[2024/09/25][V2.5 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/6fc21a485fe89ddf6f19eb9babf16c2d5cd1d8d4): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.16160) MIMO (Visual, Pose-Guided Dance Video Generation)




-----

[2024/09/24][V2.4 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/23ab99584b094c07376c6ba10ba1a95810924f78): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.15179) MIMAFace (Audio, Fine-Grained Style and Emotion-Driven Animation)

----


[2024/09/23][V2.3 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/95f8ece322ccd016095b67a06d281b63c6edc811): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.13268) JoyHallo (Audio, Fine-Grained Style and Emotion-Driven Animation)

----

[2024/09/19] [V2.2 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/9426f769250fe1c67fdfa976da737ca8932578f8): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.12156) JEAN (Audio, Head Pose Driving)


----

[2024/09/17] [V2.1 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/ef620143ea96facd46db5b1308d2046d4e1e1729): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.09326) LawDNet (Audio, Lip Synchronization)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.09292) StyleTalk++ (Audio, Fine-Grained Style and Emotion-Driven Animation)


----

[2024/09/13] [V2.0 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/2639c3c503d453983a986d0d935ac68f72a644b7): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.07649) DiffTED (Audio, Audio-Driven Holistic Body Driving)


----

[2024/09/12] [V1.9 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/8bbe098242b96558a29eda76f5c7f334491e879b): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.07255) EMOdiffhead (Audio, Fine-Grained Animation)

----

[2024/09/11] [V1.8 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/d519044e825da261475e9fb4bcbda8073dd6f97f): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.06202) RealisDance (Visual, Pose-Guided Dance Video Generation)

----

[2024/09/10] [V1.7 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/81c993d26fa2e3fa67763a1ad1aafd5943a5005c): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05089) Leveraging WaveNet for Dynamic Listening Head Modeling from Speech (Audio, Lip Synchronization)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05330) KAN-Based Fusion of Dual-Domain for Audio-Driven Facial Landmarks Generation (Audio, Lip Synchronization)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05379) PersonaTalk (Audio, Lip Synchronization)

----

[2024/09/06] [V1.6 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/efe3d0e4321817e53f25c0ed01a7a701201f6859): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.03270) SVP (Audio, Fine-Grained Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.03605) SegTalker (Audio, Lip Synchronization)

----

[2024/09/05] [V1.5 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/48a6be9665c56a2cee63d95413cfb1641bd86881): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.02634) Loopy (Audio, Fine-Grained Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.02657) PoseTalk (Audio, Fine-Grained Animation)


----

[2024/09/04] [V1.4 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/db000f0d47f495281ce76952fd29a354e5bbdecc): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.01876) CyberHost (Audio, Holistic Human Driving)

----

[2024/08/28] [V1.3 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5155e40204b06cc14f2c6ed48f482bcd1101b2cc): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.14975) MegActor-Σ (Audio, Fine-Grained Animation)

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.15159) Rafael Azevedo et al. (Text, Text2Face)

----

[2024/08/27] [V1.2 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/5165410301c52c2313efc5a006cc3429660b49bb): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13674) GenCA (Text, Text2Face)

----

[2024/08/26] [V1.1 Vision](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation/tree/f804350c23fa9e3d8f77334fd0e33e193d2ea351): Update Methods.

[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13049)  G3FA (Vision, Portrait Animation)

----

[2024/08/21] V1.0 Vision: Initialize the repository. If you find it helpful to you, welcome to star and share our work.





## Vision Guidance

<details open><summary>Part (Face) || Portrait Animation</summary>








|  **Date**  	|                                                **Title**                                                	|                                        **arXiv Link**                                       	| **Motion  Representation** 	|   **Backbone**  	|                  **Venue**                 	|
|:----------:	|:-------------------------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------:	|:--------------------------:	|:---------------:	|:------------------------------------------:	|
| 2024 06 04 	|             Follow-Your-Emoji: Fine-Controllable and Expressive Freestyle Portrait Animation            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01900) 	|          KeyPoint          	| Diffusion Model 	|              SIGGRAPH ASIA2024             	|
| 2024 07 05 	|            LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.03168) 	|          KeyPoint          	| Encoder-Decoder 	|                    arXiv                   	|
| 2024 07 09 	|                 MobilePortrait: Real-Time One-Shot Neural Head Avatars on Mobile Devices                	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.05712) 	|          KeyPoint          	| Diffusion Model 	|                    arXiv                   	|
| 2023 10 16 	|                 Expression Domain Translation Network for Cross-domain Head Reenactment                 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.10073) 	|     3D Parameterization    	| Encoder-Decoder 	|                 ICASSP 2024                	|
| 2023 03 26 	|              OTAvatar : One-shot Talking Face Avatar with Controllable Tri-plane Rendering              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14662) 	|     3D Parameterization    	| Encoder-Decoder 	|                  CVPR 2023                 	|
| 2023 03 27 	|                        OmniAvatar: Geometry-Guided Controllable 3D Head Synthesis                       	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.15539) 	|           Latent           	|       GAN       	|                  CVPR 2023                 	|
| 2023 12 04 	|                   Unsupervised High-Resolution Portrait Gaze Correction and Animation                   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2207.00256) 	|           Latent           	|       GAN       	| IEEE Transactions on Image Processing 2022 	|
| 2024 06 08 	|                  MegActor: Harness the Power of Raw Video for Vivid Portrait Animation                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20851) 	|           Latent           	| Diffusion Model 	|                    arXiv                   	|
| 2024 05 31 	|               X-Portrait: Expressive Portrait Animation with Hierarchical Motion Attention              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.15931) 	|           Latent           	| Diffusion Model 	|              ACM SIGGRAPH 2024             	|
| 2024 08 26 	|                               G3FA: Geometry-guided GAN for Face Animation                              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13049) 	|           Latent           	|       GAN       	|                    arXiv                   	|
| 2024 09 27 	|                                          Stable Video Portraits                                         	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.18083) 	|     3D Parameterization    	| Diffusion Model 	|                  ECCV 2024                 	|
| 2024 11 04 	|            Towards High-fidelity Head Blending with Chroma Keying for Industrial Applications           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.00652) 	|           Region           	| Encoder-Decoder 	|                  WACV 2024                 	|
| 2024 11 28 	|                                HiFiVFS: High Fidelity Video Face Swapping                               	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18293) 	|           Latent           	| Encoder-Decoder 	|                    arXiv                   	|
| 2024 12 02 	|   EmojiDiff: Advanced Facial Expression Control with High Identity Preservation in Portrait Generation  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01254) 	|           Latent           	| Diffusion Model 	|                    arXiv                   	|
| 2024 12 15 	|           VividFace: A Diffusion-Based Hybrid Framework for High-Fidelity Video Face Swapping           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.11279) 	|           Latent           	| Diffusion Model 	|                    arXiv                   	|
| 2024 12 27 	|                            RAIN: Real-time Animation of Infinite Video Stream                           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.19489) 	|           Latent           	| Diffusion Model 	|                    arXiv                   	|
| 2025 01 11 	|            Qffusion: Controllable Portrait Video Editing via Quadrant-Grid Attention Learning           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.06438) 	|           Latent           	| Diffusion Model 	|                    arXiv                   	|
| 2025 01 15 	|      DynamicFace: High-Quality and Consistent Video Face Swapping using Composable 3D Facial Priors     	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08553) 	|           Latent           	| Diffusion Model 	|                    arXiv                   	|
| 2025 01 29 	|                     Learning Semantic Facial Descriptors for Accurate Face Animation                    	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.17718) 	|           Latent           	| Diffusion Model 	|                    arxiv                   	|
| 2025 02 27 	| High-Fidelity Relightable Monocular Portrait Animation with Lighting-Controllable Video Diffusion Model 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.19894) 	|           Latent           	| Diffusion Model 	|                    arxiv                   	|
| 2025 03 02 	|                                 FaceShot: Bring Any Character into Life                                 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.00740) 	|           Latent           	| Diffusion Model 	|                    arxiv                   	|
| 2024 03 23 	|                              FaceOff: A Video-to-Video Face Swapping System                             	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2208.09788) 	|           Latent           	| Encoder-Decoder 	|                  WACV 2023                 	|





</details>









<details><summary>Holistic Human || Video-Guided Dance Video Generation </summary>

|  **Date**  	|                                     **Title**                                    	|                                        **arXiv Link**                                       	| **Motion  Representation** 	|   **Backbone**  	|                       **Venue**                      	|
|:----------:	|:--------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------:	|:--------------------------:	|:---------------:	|:----------------------------------------------------:	|
| 2018 08 22 	|                                Everybody dance now                               	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1808.07371) 	|          KeyPoint          	|       GAN       	|                       ICCV 2019                      	|
| 2023 07 02 	| Bidirectional Temporal Diffusion Model for Temporally Consistent Human Animation 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.00574) 	|           Region           	| Diffusion Model 	|                         arXiv                        	|
| 2023 02 22 	|      Human MotionFormer: Transferring Human Motions with Vision Transformers     	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.11306) 	|          KeyPoint          	| Encoder-Decoder 	|                         arXiv                        	|
| 2024 10 02 	|                             Replace Anyone in Videos                             	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.19911) 	|          KeyPoint          	| Diffusion Model 	|                         arXiv                        	|
| 2024 06 24 	|                     Do As I Do: Pose Guided Human Motion Copy                    	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16601) 	|          KeyPoint          	|       GAN       	| IEEE Transactions on Dependable and Secure Computing 	|



</details>
  











<details><summary>Holistic Human || Pose-Guided Dance Video Generation </summary>



|   **Date**  	|                                             **Title**                                            	|                                        **arXiv Link**                                       	| **Motion  Representation** 	|   **Backbone**  	|   **Venue**  	|
|:-----------:	|:------------------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------:	|:--------------------------:	|:---------------:	|:------------:	|
|  2023 06 30 	|                                               DisCo                                              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.00040) 	|          KeyPoint          	| Diffusion Model 	|   CVPR2024   	|
|  2023 10 20 	|                                        Dance Your Latents                                        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.14780) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2023 11 18 	|                                             MagicPose                                            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12052) 	|          KeyPoint          	| Diffusion Model 	|   ICML2024   	|
|  2023 11 27 	|                                           MagicAnimate                                           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16498) 	|           Region           	| Diffusion Model 	|   CVPR2024   	|
|  2023 11 28 	|                                          Animate Anyone                                          	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17117) 	|          KeyPoint          	| Diffusion Model 	|   CVPR2024   	|
|  2023 12 08 	|                                            DreaMoving                                            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05107) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2023 12 27 	|                                            I2V-Adapter                                           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.16693) 	|          KeyPoint          	| Diffusion Model 	| SIGGRAPH2024 	|
|  2024 05 26 	|   Disentangling Foreground and Background Motion for Enhanced Realism in Human Video Generation  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16393) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 05 28 	|          VividPose: Advancing Stable Video Diffusion for Realistic Human Image Animation         	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18156) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
| 2024 05 30  	|            MotionFollower: Editing Video Motion via Lightweight Score-Guided Diffusion           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20325) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 06 03 	|      UniAnimate: Taming Unified Video Diffusion Models for Consistent Human Image animation      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01188) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 06 05 	| Follow-Your-Pose v2: Multiple-Condition Guided Character Image Animation for Stable Pose Control 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.03035) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 05 27 	|             Human4DiT: Free-view Human Video Generation with 4D Diffusion Transformer            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17405) 	|     3D Parameterization    	|   Transformer   	|     arxiv    	|
|  2024 01 19 	|                            Synthesizing Moving People with 3D Control                            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.10889) 	|     3D Parameterization    	| Diffusion Model 	|     arxiv    	|
|  2024 03 21 	|       Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance       	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781) 	|     3D Parameterization    	| Diffusion Model 	|   ECCV 2024  	|
|  2024 07 01 	|    MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19680) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 07 15 	|   TCAN: Animating Human Images with Temporally Consistent Pose Guidance using Diffusion Models   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.09012) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 09 11 	|             RealisDance: Equip controllable character animation with realistic hands             	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.06202) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 09 25 	|           MIMO: Controllable Character Video Synthesis with Spatial Decomposed Modeling          	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.16160) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 10 02 	|      High Quality Human Image Animation using Regional Supervision and Motion Blur Condition     	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.19580) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 10 15 	|        Animate-X: Universal Character Image Animation with Enhanced Motion Representation        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10306) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 11 14 	|                   MikuDance: Animating Character Art with Mixed Motion Dynamics                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.08656) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 11 26 	|              StableAnimator: High-Quality Identity-Preserving Human Image Animation              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17697) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 11 30 	|          DreamDance: Animating Human Images by Enriching 3D Geometry Cues from 2D Poses          	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00397) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 12 12 	|            DisPose: Disentangling Pose Guidance for Controllable Human Image Animation           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09349) 	|       KeyPoint,Region      	| Diffusion Model 	|     arxiv    	|
|  2024 12 19 	|         Consistent Human Image and Video Generation with Spatially Conditioned Diffusion         	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14531) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 12 23 	|              Free-viewpoint Human Animation with Pose-correlated Reference Selection             	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.17290) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2025 01 17 	|                         X-Dyna: Expressive Dynamic Human Image Animation                         	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.10021) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2025 02 10 	|       Animate Anyone 2: High-Fidelity Character Image Animation with Environment Affordance      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.06145) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2025 02 12 	|     AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance     	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08189) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2025 02 17 	|                    HumanGif: Single-View Human Diffusion with Generative Prior                   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.12080) 	|          KeyPoint          	| Diffusion Model 	|     arxiv    	|
|  2024 07 16 	|     IDOL: Unified Dual-Modal Latent Diffusion for Human-Centric Joint Video-Depth Generation     	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.10937) 	|           Region           	| Diffusion Model 	|     arxiv    	|










</details>













<details><summary>Holistic Human || Try-On Video Generation </summary>

|  **Date**  	|                                              **Title**                                              	|                                        **arXiv Link**                                       	| **Motion  Representation** 	|   **Backbone**  	|      **Venue**     	|
|:----------:	|:---------------------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------:	|:--------------------------:	|:---------------:	|:------------------:	|
| 2024 04 26 	|     Tunnel Try-on: Excavating Spatial-temporal Tunnels for High-quality Virtual Try-on in Videos    	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.17571) 	|          KeyPoint          	| Diffusion Model 	|        arxiv       	|
| 2024 05 20 	|                          ViViD: Video Virtual Try-on using Diffusion Models                         	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.11794) 	|           Region           	| Diffusion Model 	|        arxiv       	|
| 2024 11 04 	|                        Fashion-VDM: Video Diffusion Model for Virtual Try-On                        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.00225) 	|           Latent           	| Diffusion Model 	| SIGGRAPH Asia 2025 	|
| 2024 11 25 	|               FloAt: Flow Warping of Self-Attention for Clothing Animation Generation               	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.15028) 	|           Latent           	| Diffusion Model 	|        arxiv       	|
| 2024 12 04 	|                PEMF-VVTO: Point-Enhanced Video Virtual Try-on via Mask-free Paradigm                	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.03021) 	|           Latent           	| Diffusion Model 	|        arxiv       	|
| 2024 12 13 	|             Dynamic Try-On: Taming Video Virtual Try-on with Dynamic Attention Mechanism            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09822) 	|           Latent           	| Diffusion Model 	|        arxiv       	|
| 2024 12 13 	|               SwiftTry: Fast and Consistent Video Virtual Try-On with Diffusion Models              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.10178) 	|           Latent           	| Diffusion Model 	|        arxiv       	|
| 2025 01 15 	|         RealVVT: Towards Photorealistic Video Virtual Try-on via Spatio-Temporal Consistency        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08682) 	|           Latent           	| Diffusion Model 	|        arxiv       	|
| 2025 01 20 	| CatV2TON: Taming Diffusion Transformers for Vision-Based Virtual Try-On with Temporal Concatenation 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.11325) 	|           Latent           	| Diffusion Model 	|        arxiv       	|
| 2024 07 16 	|       WildVidFit: Video Virtual Try-On in the Wild via Image-Based Controlled Diffusion Models      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.10625) 	|          KeyPoint          	| Diffusion Model 	|        arxiv       	|


</details>








<details><summary>Holistic Human || Pose2Video </summary>






|  **Date**  |                                                **Title**                                               |                                        **arXiv Link**                                       | **Motion  Representation** |   **Backbone**  | **Venue** |
|:----------:|:------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------:|:--------------------------:|:---------------:|:---------:|
| 2023 04 12 |                                                DreamPose                                               | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06025) |           Region           | Diffusion Model | ICCV 2023 |
| 2024 03 25 |                   Make-Your-Anchor: A Diffusion-based 2D Avatar Generation Framework                   | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.16510) |     3D Parameterization    | Diffusion Model | CVPR 2024 |
| 2024 04 21 |               PoseAnimate: Zero-shot high fidelity pose controllable character animation               | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.13680) |          KeyPoint          | Diffusion Model |   arxiv   |
| 2024 12 18 |     ManiVideo: Generating Hand-Object Manipulation Video with Dexterous and Generalizable Grasping     | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.16212) |          KeyPoint          | Diffusion Model |   arxiv   |
| 2025 02 07 |         HumanDiT: Pose-Guided Diffusion Transformer for Long-form Human Motion Video Generation        | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.04847) |          KeyPoint          | Diffusion Model |   arxiv   |
| 2024 11 26 | AnchorCrafter: Animate CyberAnchors Saling Your Products via Human-Object Interacting Video Generation | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17383) |          KeyPoint          | Diffusion Model |   arxiv   |
| 2024 10 29 |           MovieCharacter: A Tuning-Free Framework for Controllable Character Video Synthesis           | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.20974) |           Region           | Diffusion Model |   arxiv   |






</details>















## Text Guidance

<details open><summary>Part (Face) || Text2Face</summary>




|  **Date**  	|                                                        **Title**                                                        	|                                        **arXiv Link**                                       	| **Motion  Representation** 	|   **Backbone**  	|   **Venue**  	|
|:----------:	|:-----------------------------------------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------:	|:--------------------------:	|:---------------:	|:------------:	|
| 2021 05 07 	|                       Write-a-speaker: Text-based Emotional and Rhythmic Talking-head Generation                        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2104.07995) 	|          KeyPoint          	|       GAN       	|   AAAI 2021  	|
| 2023 12 11 	| Neural Text to Articulate Talk: Deep Text to Audiovisual Speech Synthesis<br>achieving both Auditory and Photo-realism  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06613) 	|     3D Parameterization    	|       GAN       	|     arXiv    	|
| 2023 06 03 	|                        VideoComposer: Compositional Video Synthesis with Motion Controllability                         	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.02018) 	|           Region           	| Diffusion Model 	| NeurIPS 2024 	|
| 2024 04 23 	|                            ID-Animator: Zero-Shot Identity-Preserving Human Video Generation                            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15275) 	|           Latent           	| Diffusion Model 	|     arXiv    	|
| 2023 12 09 	|                              FT2TF: First-Person Statement Text-To-Talking Face Generation                              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05430) 	|           Latent           	| Encoder-Decoder 	|     arXiv    	|
| 2024 05 16 	|                         Faces that Speak: Jointly Synthesising Talking Face and Speech from Text                        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.10272) 	|           Latent           	|       GAN       	|   CVPR 2024  	|
| 2024 08 27 	|                   GenCA: A Text-conditioned Generative Model for Realistic and Drivable Codec Avatars                   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13674) 	|     3D Parameterization    	| Encoder-Decoder 	|     arXiv    	|
| 2024 08 28 	|       Empowering Sign Language Communication: Integrating Sentiment and Semantics for Facial Expression Synthesis       	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.15159) 	|          KeyPoint          	| Diffusion Model 	|     arXiv    	|
| 2024 11 28 	|                   MotionCharacter: Identity-Preserving and Motion Controllable Human Video Generation                   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18281) 	|           Region           	| Diffusion Model 	|     arXiv    	|
| 2024 11 26 	|                         Identity-Preserving Text-to-Video Generation by Frequency Decomposition                         	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17440) 	|           Region           	| Diffusion Model 	|     arXiv    	|
| 2024 11 26 	|               PersonalVideo: High ID-Fidelity Video Customization without Dynamic and Semantic Degradation              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17048) 	|           Latent           	| Diffusion Model 	|     arXiv    	|
| 2024 12 27 	|           VideoMaker: Zero-shot Customized Video Generation with the Inherent Force of Video Diffusion Models           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.19645) 	|           Latent           	| Diffusion Model 	|     arXiv    	|
| 2020 03 01 	|                                        Towards Automatic Face-to-Face Translation                                       	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2003.00418) 	|           Latent           	| Encoder-Decoder 	|  ACM MM 2019 	|




</details>

<details><summary>Holistic Human || Text2MotionVideo</summary>








|   **Date**  	|                                                       **Title**                                                      	|                                        **arXiv Link**                                       	| **Motion  Representation** 	|   **Backbone**  	| **Venue** 	|
|:-----------:	|:--------------------------------------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------:	|:--------------------------:	|:---------------:	|:---------:	|
|  2024 05 08 	|                                                   Edit-Your-Motion                                                   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.04496) 	|          KeyPoint          	| Diffusion Model 	|   arXiv   	|
|  2023 08 15 	|             Dancing Avatar: Pose and Text-Guided Human Motion Videos Synthesis with Image Diffusion Model            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.07749) 	|          KeyPoint          	| Diffusion Model 	|   arXiv   	|
|  2023 04 03 	|                                                   Follow Your Pose                                                   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186) 	|          KeyPoint          	| Diffusion Model 	| AAAI 2024 	|
|  2024 12 21 	|             Follow-Your-MultiPose: Tuning-Free Multi-Character Text-to-Video Generation via Pose Guidance            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.16495) 	|          KeyPoint          	| Diffusion Model 	|   arxiv   	|
|  2023 08 28 	|                                MagicAvatar: Multimodal Avatar Generation and Animation                               	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14748) 	|          KeyPoint          	| Diffusion Model 	|   arXiv   	|
|  2024 02 14 	|                                Magic-Me: Identity-Specific Video Customized Diffusion                                	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09368) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2024 04 07 	|            Towards a Simultaneous and Granular Identity-Expression Control in Personalized Face Generation           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01207) 	|           Latent           	| Diffusion Model 	| CVPR 2024 	|
|  2023 04 17 	|                                  Text2Performer: Text-Driven Human Video Generation                                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08483) 	|           Latent           	| Encoder-Decoder 	| ICCV 2023 	|
| 2024 04 14  	|                                                     LoopAnimate                                                      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.09172	) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2023 07 10 	|             AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.04725) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2023 12 06 	|                           AnimateZero: Video Diffusion Models are Zero-Shot Image Animators                          	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03793) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2023 10 30 	|                        VideoCrafter1: Open Diffusion Models for High-Quality Video Generation                        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.19512) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2023 07 19 	|                         TokenFlow: Consistent Diffusion Features for Consistent Video Editing                        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.10373) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2023 03 23 	|                    Text2Video-Zero: Text-to-Image Diffusion Models are Zero-Shot Video Generators                    	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13439) 	|           Latent           	| Diffusion Model 	| ICCV 2023 	|
|  2023 02 02 	|                               Dreamix: Video Diffusion Models are General Video Editors                              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.01329) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2023 12 05 	| BIVDiff: A Training-Free Framework for General-Purpose Video Synthesis via Bridging Image and Video Diffusion Models 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02813) 	|           Latent           	| Diffusion Model 	| CVPR 2024 	|
|  2024 11 29 	|                            Fleximo: Towards Flexible Text-to-Human Motion Video Generation                           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.19459) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2023 12 30 	|                                Dual-Stream Diffusion Net for Text-to-Video Generation                                	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08316) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2025 01 07 	|                      Magic Mirror: ID-Preserved Video Generation in Video Diffusion Transformers                     	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03931) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2025 01 23 	|                  EchoVideo: Identity-Preserving Human Video Generation by Multimodal Feature Fusion                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.13452) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2025 01 17 	|                        Textoon: Generating Vivid 2D Cartoon Characters from Text Descriptions                        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.10020) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2025 02 19 	|                           FantasyID: Face Knowledge Enhanced ID-Preserving Video Generation                          	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.13995) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2025 01 03 	|                         Ingredients: Blending Custom Photos with Video Diffusion Transformers                        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.01790) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2024 02 22 	|                                                   Customize-A-Video                                                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14780) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2023 12 12 	|                   LatentMan: Generating Consistent Animated Characters using Image Diffusion Models                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.07133) 	|     3D Parameterization    	| Diffusion Model 	|   arXiv   	|
|  2024 08 15 	|                    DeCo: Decoupled Human-Centered Diffusion Video Editing with Motion Consistency                    	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.07481) 	|     3D Parameterization    	| Diffusion Model 	|   arXiv   	|
|  2024 10 15 	|                            Tex4D: Zero-shot 4D Scene Texturing with Video Diffusion Models                           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10821) 	|           Latent           	| Diffusion Model 	|   arXiv   	|
|  2024 01 17 	|                  VideoCrafter2: Overcoming Data Limitations for High-Quality Video Diffusion Models                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09047) 	|           Latent           	| Diffusion Model 	| CVPR 2024 	|









</details>
























## Audio Guidance

<details open><summary>Part (Face) || Lip Synchronization</summary>


|  **Date**  	|                                       **Title**                                      	|                                              **arXiv Link**                                             	| **Motion  Representation** 	|   **Backbone**  	| **Venue** 	|
|:----------:	|:------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------------------:	|:--------------------------:	|:---------------:	|:---------:	|
| 2020 09 17 	|                      Photorealistic Audio-driven Video Portraits                     	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ieeexplore.ieee.org/document/9199560) 	|           Region           	| Encoder-Decoder 	|  TVCG2020 	|
| 2019 05 09 	|     Hierarchical cross-modal talking face generation with dynamic pixel-wise loss    	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1905.03820)       	|          KeyPoint          	|  Autoregressive 	|  CVPR2019 	|
| 2019 05 08 	|                Capture, Learning, and Synthesis of 3D Speaking Styles                	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1905.03079)       	|           Latent           	| Encoder-Decoder 	|  CVPR2019 	|
| 2024 08 13 	|               Style-Preserving Lip Sync via Audio-Aware Style Reference              	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.05412)       	|           Latent           	| Diffusion Model 	|   arxiv   	|
| 2024 09 06 	| SegTalker: Segmentation-based Talking Face Generation with Mask-guided Local Editing 	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.03605)       	|           Latent           	|       GAN       	|   arxiv   	|
| 2024 09 10 	|          Leveraging WaveNet for Dynamic Listening Head Modeling from Speech          	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05089)       	|           Latent           	|  Autoregressive 	|   arxiv   	|
| 2024 09 10 	|     KAN-Based Fusion of Dual-Domain for Audio-Driven Facial Landmarks Generation     	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05330)       	|          KeyPoint          	| Encoder-Decoder 	|   arxiv   	|
| 2024 09 10 	|            PersonaTalk: Bring Attention to Your Persona in Visual Dubbing            	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05379)       	|     3D Parameterization    	| Encoder-Decoder 	|   arxiv   	|
| 2024 09 17 	|   LawDNet: Enhanced Audio-Driven Lip Synthesis via Local Affine Warping Deformation  	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.09326)       	|           Latent           	| Encoder-Decoder 	|   arxiv   	|
| 2024 10 15 	|   MuseTalk: Real-Time High Quality Lip Synchronization with Latent Space Inpainting  	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10122)       	|           Latent           	| Diffusion Model 	|   arxiv   	|
| 2024 12 12 	|          LatentSync: Audio Conditioned Latent Diffusion Models for Lip Sync          	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09262)       	|           Latent           	| Diffusion Model 	|   arxiv   	|
| 2025 01 08 	|                Identity-Preserving Video Dubbing Using Motion Warping                	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.04586)       	|           Latent           	| Encoder-Decoder 	|   arxiv   	|
| 2023 01 10 	|         Speech driven video editing via an audio-conditioned diffusion model         	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.04474)       	|           Latent           	| Diffusion Model 	|  IVC2024  	|





</details>















<details open><summary>Part (Face) || Head Pose Driving</summary>




|  **Date**  	|                                                            **Title**                                                            	|                                                            **arXiv Link**                                                           	|  **Motion  Representation**  	|   **Backbone**  	|                              **Venue**                              	|
|:----------:	|:-------------------------------------------------------------------------------------------------------------------------------:	|:-----------------------------------------------------------------------------------------------------------------------------------:	|:----------------------------:	|:---------------:	|:-------------------------------------------------------------------:	|
| 2017 08 20 	|                           Predicting head pose from speech with a conditional variational autoencoder                           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ueaeprints.uea.ac.uk/id/eprint/64846/1/greenwood_Interspeech.pdf) 	|            Latent            	|  Autoregressive 	|                               ISCA2017                              	|
| 2020 04 27 	|                                         MakeItTalk: Speaker-Aware Talking-Head Animation                                        	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2004.12992)                     	|           KeyPoint           	|  Autoregressive 	|                               TOG2020                               	|
| 2021 09 22 	|                              Live Speech Portraits: Real-Time Photorealistic Talking-Head Animation                             	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2109.10595)                     	|           KeyPoint           	|  Autoregressive 	|                               TOG2021                               	|
| 2022 01 03 	|                 DFA-NeRF: Personalized Talking Head Generation via Disentangled Face Attributes Neural Rendering                	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2201.00791)                     	|           KeyPoint           	| Encoder-Decoder 	|                                arxiv                                	|
| 2023 01 10 	|                       DiffTalk: Crafting Diffusion Models for Generalized Audio-Driven Portraits Animation                      	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.03786)                     	|           KeyPoint           	| Diffusion Model 	|                               CVPR2023                              	|
| 2023 05 15 	|                         Identity-Preserving Talking Face Generation with Landmark and Appearance Priors                         	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.08293)                     	|       Muliti-Conditions      	|   Transformer   	|                               CVPR2023                              	|
| 2023 05 01 	|                       GeneFace++: Generalized and Stable Real-Time Audio-Driven 3D Talking Face Generation                      	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.00787)                     	|           KeyPoint           	| Encoder-Decoder 	|                                arxiv                                	|
| 2022 03 16 	|                  StyleHEAT: One-Shot High-Resolution Editable Talking Face Generation via Pre-trained StyleGAN                  	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.04036)                     	|            Region            	|       GAN       	|                               ECCV2022                              	|
| 2023 02 20 	|                    SD-NeRF: Towards Lifelike Talking Head Animation via Spatially-Adaptive Dual-Driven NeRFs                    	|               [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ieeexplore.ieee.org/document/10229247)              	|      3D Parameterization     	| Encoder-Decoder 	|                               TMM2023                               	|
| 2024 03 26 	|                                                           AniPortrait                                                           	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.17694)                     	| KeyPoint,3D Parameterization 	| Diffusion Model 	|                                arxiv                                	|
| 2024 06 17 	|                                                       Make Your Actor Talk                                                      	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.08096)                     	|           KeyPoint           	| Diffusion Model 	|                                arxiv                                	|
| 2024 06 12 	|               Emotional Conversation: Empowering Talking Faces with Cohesive Expression, Gaze and Pose Generation               	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.07895)                     	| KeyPoint,3D Parameterization 	| Diffusion Model 	|                                arxiv                                	|
| 2024 06 27 	|      RealTalk: Real-time and Realistic Audio-driven Face Generation with 3D Facial Prior-guided Identity Alignment Network      	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.18284)                     	|      3D Parameterization     	|   Transformer   	|                                arxiv                                	|
| 2021 03 20 	|                             AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis                             	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2103.11078)                     	|            Latent            	| Encoder-Decoder 	|                               ICCV2021                              	|
| 2022 01 19 	|                              Semantic-Aware Implicit Neural Audio-Driven Video Portrait Generation                              	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2201.07786)                     	|            Latent            	| Encoder-Decoder 	|                               ECCV2022                              	|
| 2021 04 22 	|                 Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation                 	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2104.11116)                     	|            Latent            	|       GAN       	|                               CVPR2021                              	|
| 2023 01 06 	|                              Diffused Heads: Diffusion Models Beat GANs on Talking-Face Generation                              	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.03396)                     	|            Latent            	| Diffusion Model 	|                                CVPR24                               	|
| 2023 03 30 	|                    DAE-Talker: High Fidelity Speech-Driven Talking Face Generation with Diffusion Autoencoder                   	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17550)                     	|            Latent            	| Diffusion Model 	|                               ACM MM23                              	|
| 2023 11 26 	|                                            GAIA: Zero-shot Talking Avatar Generation                                            	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15230)                     	|            Latent            	| Diffusion Model 	|                              ICLR 2024                              	|
| 2023 12 09 	| R2-Talker: Realistic Real-Time Talking Head Synthesis with Hash Grid Landmarks Encoding and Progressive Multilayer Conditioning 	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05572)                     	|           KeyPoint           	| Encoder-Decoder 	|                                arxiv                                	|
| 2024 05 06 	|                                                            AniTalker                                                            	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.03121)                     	|            Latent            	| Encoder-Decoder 	|                                arxiv                                	|
| 2024 07 12 	|                    EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions                    	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08136)                     	|           KeyPoint           	| Diffusion Model 	|                                arxiv                                	|
| 2024 07 29 	|                     LinguaLinker: Audio-Driven Portraits Animation with Implicit Facial Control Enhancement                     	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.18595)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2024 08 03 	|                Landmark-guided Diffusion Model for High-fidelity and Temporally Coherent Talking Head Generation                	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.01732)                     	|           KeyPoint           	| Diffusion Model 	|                                arxiv                                	|
| 2024 08 13 	|                      High-fidelity and Lip-synced Talking Face Synthesis via Landmark-based Diffusion Model                     	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.05416)                     	|           KeyPoint           	| Diffusion Model 	|                                arxiv                                	|
| 2022 11 22 	|                       Real-time Neural Radiance Talking Portrait Synthesis via Audio-spatial Decomposition                      	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.12368)                     	|            Latent            	| Encoder-Decoder 	|                                arxiv                                	|
| 2023 05 04 	|               High-fidelity Generalized Emotional Talking Face Generation with Multi-modal Emotion Space Learning               	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.02572)                     	|            Latent            	|   Transformer   	|                               CVPR2023                              	|
| 2024 04 02 	|                              EDTalk: Efficient Disentanglement for Emotional Talking Head Synthesis                             	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.01647)                     	|            Latent            	|       GAN       	|                               ECCV2024                              	|
| 2023 11 29 	|                                                             SyncTalk                                                            	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17590)                     	|      3D Parameterization     	| Encoder-Decoder 	|                                CVPR24                               	|
| 2024 04 23 	|                                                         TalkingGaussian                                                         	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15264)                     	|      3D Parameterization     	| Encoder-Decoder 	|                               ECCV2024                              	|
| 2024 09 19 	|                            JEAN: Joint Expression and Audio-guided NeRF-based Talking Face Generation                           	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.12156)                     	|            Latent            	| Encoder-Decoder 	|                                arxiv                                	|
| 2024 10 03 	|                    LaDTalk: Latent Denoising for Synthesizing Talking Head Videos with High Frequency Details                   	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.00990)                     	|            Latent            	| Encoder-Decoder 	|                                arxiv                                	|
| 2024 10 18 	|             DAWN: Dynamic Frame Avatar with Non-autoregressive Diffusion Framework for Talking Head Video Generation            	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13726)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2024 11 29 	|          LokiTalk: Learning Fine-Grained and Generalizable Correspondences to Enhance NeRF-based Talking Head Synthesis         	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.19525)                     	|            Latent            	| Encoder-Decoder 	|                                arxiv                                	|
| 2024 11 29 	|                          Ditto: Motion-Space Diffusion for Controllable Realtime Talking Head Synthesis                         	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.19509)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2024 12 15 	|           GoHD: Gaze-oriented and Highly Disentangled Portrait Animation with Rhythmic Poses and Realistic Expression           	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09296)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2024 12 10 	|                           PortraitTalk: Towards Customizable One-Shot Audio-to-Talking Face Generation                          	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07754)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2024 12 05 	|                 IF-MDM: Implicit Face Motion Diffusion Model for High-Fidelity Realtime Talking Head Generation                 	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04000)                     	|            Latent            	| Encoder-Decoder 	|                                arxiv                                	|
| 2024 12 05 	|                              INFP: Audio-Driven Interactive Head Generation in Dyadic Conversations                             	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04037)                     	|            Latent            	| Encoder-Decoder 	|                                arxiv                                	|
| 2024 12 05 	|                              MEMO: Memory-Guided Diffusion for Expressive Talking Video Generation                              	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.04448)                     	|            Latent            	| Encoder-Decoder 	|                                arxiv                                	|
| 2024 12 26 	|          UniAvatar: Taming Lifelike Audio-Driven Talking Head Generation with Comprehensive Motion and Lighting Control         	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.19860)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2025 01 24 	|              SyncAnimation: A Real-Time End-to-End Framework for Audio-Driven Human Pose and Talking Head Animation             	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.14646)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2025 02 02 	|                            EmoTalkingGaussian: Continuous Emotion-conditioned Talking Head Synthesis                            	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.00654)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2025 02 13 	|                          Long-Term TalkingFace Generation via Motion-Prior Conditional Diffusion Model                          	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.09533)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2025 02 17 	|                          SayAnything: Audio-Driven Lip Synchronization with Conditional Video Diffusion                         	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.11515)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2025 02 15 	|                            SkyReels-A1: Expressive Portrait Animation in Video Diffusion Transformers                           	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.10841)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2025 02 20 	|            NeRF-3DTalker: Neural Radiance Field with 3D Prior Aided Audio Disentanglement for Talking Head Synthesis            	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.14178)                     	|            Latent            	| Encoder-Decoder 	|                                arxiv                                	|
| 2025 02 24 	|                           Dimitra: Audio-driven Diffusion model for Expressive Talking Head Generation                          	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.17198)                     	|            Latent            	| Diffusion Model 	|                                arxiv                                	|
| 2025 02 27 	|                               InsTaG: Learning Personalized 3D Talking Head from Few-Second Video                               	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.20387)                     	|      3D Parameterization     	| Encoder-Decoder 	|                                arxiv                                	|
| 2025 03 06 	|                  FREAK: Frequency-modulated High-fidelity and Real-time Audio-driven Talking Portrait Synthesis                 	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.04067)                     	|      3D Parameterization     	| Encoder-Decoder 	|                                arxiv                                	|
| 2025 03 03 	|                 KeyFace: Expressive Audio-Driven Facial Animation for Long Sequences via KeyFrame Interpolation                 	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.01715)                     	|      3D Parameterization     	| Encoder-Decoder 	|                                arxiv                                	|
| 2024 04 28 	|                                                          GaussianTalker                                                         	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.14037)                     	|      3D Parameterization     	| Encoder-Decoder 	|                              ACM MM2024                             	|
| 2021 12 10 	|                                 FaceFormer: Speech-Driven 3D Facial Animation with Transformers                                 	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.05329)                     	|            Latent            	|   Transformer   	|                                CVPR22                               	|
| 2023 09 15 	|           Towards the generation of synchronized and believable non-verbal facial behaviors of a talking virtual agent          	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12804)                     	|            Latent            	|       GAN       	|                              ICMI 2023                              	|
| 2023 10 17 	|                 CorrTalk: Correlation Between Hierarchical Speech and Facial Activity Variances for 3D Animation                	|                     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.11295)                     	|            Latent            	| Encoder-Decoder 	| IEEE Transactions on Circuits and Systems for Video Technology 2024 	|


















</details>






<details><summary>Holistic Human || Audio-Driven Holistic Body Driving</summary>






|  **Date**  	|                                                    **Title**                                                    	|                                        **arXiv Link**                                       	| **Motion  Representation** 	|   **Backbone**  	|   **Venue**  	|
|:----------:	|:---------------------------------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------:	|:--------------------------:	|:---------------:	|:------------:	|
| 2024 03 13 	|                                                     VLOGGER                                                     	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.08764) 	|     3D Parameterization    	| Diffusion Model 	|     arXiv    	|
| 2022 12 05 	|                                 Audio-Driven Co-Speech Gesture Video Generation                                 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.02350) 	|           Latent           	| Encoder-Decoder 	| NeurIPS 2022 	|
| 2024 09 04 	|               CyberHost: Taming Audio-driven Avatar Diffusion Model with Region Codebook Attention              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.01876) 	|           Latent           	| Diffusion Model 	|     arXiv    	|
| 2024 09 13 	|         DiffTED: One-shot Audio-driven TED Talk Video Generation with Diffusion-based Co-speech Gestures        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.07649) 	|          KeyPoint          	| Diffusion Model 	|     arXiv    	|
| 2024 09 27 	|      Self-Supervised Learning of Deviation in Latent Representation for Co-speech Gesture Video Generation      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.17674) 	|           Region           	| Diffusion Model 	|     arXiv    	|
| 2024 10 08 	| TANGO: Co-Speech Gesture Video Reenactment with Hierarchical Audio Motion Embedding and Diffusion Interpolation 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.04221) 	|           Latent           	| Encoder-Decoder 	|     arXiv    	|
| 2024 10 15 	|           TALK-Act: Enhance Textural-Awareness for 2D Speaking Avatar Reenactment with Diffusion Model          	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10696) 	|           Latent           	| Diffusion Model 	|     arXiv    	|
| 2024 11 01 	|               Stereo-Talker: Audio-driven 3D Human Synthesis with Prior-Guided Mixture-of-Experts               	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.23836) 	|           Latent           	| Encoder-Decoder 	|     arXiv    	|
| 2024 11 18 	|                     EchoMimicV2: Towards Striking, Simplified, and Semi-Body Human Animation                    	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10061) 	|           Latent           	| Diffusion Model 	|     arXiv    	|
| 2025 01 18 	|                          EMO2: End-Effector Guided Audio-Driven Avatar Video Generation                         	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.10687) 	|           Latent           	| Diffusion Model 	|     arXiv    	|
| 2025 02 03 	|              OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models             	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01061) 	|           Latent           	| Diffusion Model 	|     arxiv    	|
| 2025 02 11 	|       Contextual Gesture: Co-Speech Gesture Video Generation through Context-aware Gesture Representation       	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07239) 	|           Latent           	| Diffusion Model 	|     arxiv    	|
| 2024 05 15 	|                      Dance Any Beat: Blending Beats with Visuals in Dance Video Generation                      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.09266) 	|           Region           	| Diffusion Model 	|     arXiv    	|
| 2025 02 24 	|                            X-Dancer: Expressive Music to Human Dance Video Generation                           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.17414) 	|          KeyPoint          	| Diffusion Model 	|     arXiv    	|
| 2025 01 30 	|                      Every Image Listens, Every Image Dances: Music-Driven Image Animation                      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.18801) 	|           Region           	| Diffusion Model 	|     arXiv    	|









</details>


<details><summary>Part (Face) || Fine-Grained Style and Emotion-Driven Animation</summary>










|  **Date**  	|                                                         **Title**                                                         	|                                        **arXiv Link**                                       	| **Motion  Representation** 	|          **Backbone**          	|               **Venue**              	|
|:----------:	|:-------------------------------------------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------:	|:--------------------------:	|:------------------------------:	|:------------------------------------:	|
| 2021 05 19 	|                                           Audio-Driven Emotional Video Portraits                                          	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2104.07452) 	|          KeyPoint          	|         Encoder-Decoder        	|               CVPR 2021              	|
| 2023 06 10 	|                       StyleTalk: One-shot Talking Head Generation with Controllable Speaking Styles                       	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.01081) 	|     3D Parameterization    	|         Encoder-Decoder        	|               AAAI 2023              	|
| 2024 01 16 	|                             Real3D-Portrait: One-shot Realistic 3D Talking Portrait Synthesis                             	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.08503) 	|     3D Parameterization    	|         Encoder-Decoder        	|               ICLR 2024              	|
| 2023 12 15 	|                  DreamTalk: When Expressive Talking Head Generation Meets Diffusion Probabilistic Models                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09767) 	|     3D Parameterization    	|         Diffusion Model        	|                 arXiv                	|
| 2024 06 04 	|                    V-Express: Conditional Dropout for Progressive Training of Portrait Video Generation                   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.02511) 	|          KeyPoint          	|         Diffusion Model        	|                 arXiv                	|
| 2021 07 21 	|                     Speech Driven Talking Face Generation from a Single Image and an Emotion Condition                    	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2008.03592) 	|           Latent           	|               GAN              	| IEEE Transactions on Multimedia 2021 	|
| 2022 11 22 	|                                                         SadTalker                                                         	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.12194) 	|           Latent           	|         Diffusion Model        	|               CVPR 2023              	|
| 2022 11 28 	|                 High-fidelity Facial Avatar Reconstruction from Monocular Video with<br>Generative Priors                 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.15064) 	|     3D Parameterization    	|               GAN              	|               CVPR 2023              	|
| 2023 05 09 	|                  StyleSync: High-Fidelity Generalized and Personalized Lip Sync in Style-based Generator                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05445) 	|           Latent           	|               GAN              	|               CVPR 2023              	|
| 2024 02 27 	|                                                            EMO                                                            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.17485) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 03 04 	|              FaceChain-ImagineID: Freely Crafting High-Fidelity Diverse Talking Faces from Disentangled Audio             	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.01901) 	|           Latent           	|         Diffusion Model        	|               CVPR 2024              	|
| 2024 04 29 	|                                                        EMOPortraits                                                       	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.19110) 	|           Latent           	|               GAN              	|               CVPR 2024              	|
| 2024 05 12 	|                    Listen, Disentangle, and Control: Controllable Speech-Driven Talking Head Generation                   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.07257) 	|           Latent           	|               GAN              	|                 arXiv                	|
| 2024 06 16 	|                       Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation                      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.08801) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 10 11 	|                      Hallo2: Long-Duration and High-Resolution Audio-Driven Portrait Image Animation                      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.07718) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 04 16 	|                                                           VASA-1                                                          	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10667) 	|           Latent           	| Diffusion Model By Transformer 	|                 arXiv                	|
| 2024 08 20 	|            S^3D-NeRF: Single-Shot Speech-Driven Neural Radiance Field for High Fidelity Talking Head Synthesis            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09347) 	|           Latent           	|         Encoder-Decoder        	|                 arXiv                	|
| 2024 08 20 	|                 FD2Talk: Towards Generalized Talking Head Generation with Facial Decoupled Diffusion Model                	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09384) 	|     3D Parameterization    	|         Diffusion Model        	|              ACMMM 2024              	|
| 2024 08 28 	|            MegActor-Σ: Unlocking Flexible Mixed-Modal Control in Portrait Animation with Diffusion Transformer            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.14975) 	|           Latent           	| Diffusion Model By Transformer 	|                 arXiv                	|
| 2024 09 05 	|                        Loopy: Taming Audio-Driven Portrait Avatar with Long-Term Motion Dependency                        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.02634) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 09 05 	|           PoseTalk: Text-and-Audio-based Pose Control and Motion Refinement for One-Shot Talking Head Generation          	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.02657) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 09 06 	|                              SVP: Style-Enhanced Vivid Portrait Talking Head Diffusion Model                              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.03270) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 09 12 	|                    EMOdiffhead: Continuously Emotional Control in Talking Head Generation via Diffusion                   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.07255) 	|     3D Parameterization    	|         Diffusion Model        	|                 arXiv                	|
| 2024 09 17 	|                   StyleTalk++: A Unified Framework for Controlling the Speaking Styles of Talking Heads                   	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.09292) 	|     3D Parameterization    	|         Encoder-Decoder        	|                 arXiv                	|
| 2024 09 23 	|                                         JoyHallo: Digital human model for Mandarin                                        	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.13268) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 09 24 	|                     MIMAFace: Face Animation via Motion-Identity Modulated Appearance Feature Learning                    	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.15179) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 10 10 	|                       MimicTalk: Mimicking a personalized and expressive 3D talking face in minutes                       	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.06734) 	|     3D Parameterization    	|         Encoder-Decoder        	|               Nips 2024              	|
| 2024 10 21 	|            Takin-ADA: Emotion Controllable Audio-Driven Animation with Canonical and Landmark Loss Optimization           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.14283) 	|           Latent           	|         Encoder-Decoder        	|                 arXiv                	|
| 2024 10 24 	|                                     Audio-Driven Emotional 3D Talking-Head Generation                                     	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.17262) 	|           Latent           	|         Encoder-Decoder        	|                 arXiv                	|
| 2024 11 15 	| JoyVASA: Portrait and Animal Image Animation with Diffusion-Based Audio-Driven Facial Dynamics and Head Motion Generation 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.09209) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 11 15 	|                LES-Talker: Fine-Grained Emotion Editing for Talking Head Generation in Linear Emotion Space               	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.09268) 	|           Latent           	|         Encoder-Decoder        	|                 arXiv                	|
| 2024 11 28 	|                             LetsTalk: Latent Diffusion Transformer for Talking Video Synthesis                            	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16748) 	|           Latent           	|         Encoder-Decoder        	|                 arXiv                	|
| 2024 11 23 	|     EmotiveTalk: Expressive Talking Head Generation through Audio Information Decoupling and Emotional Video Diffusion    	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16726) 	|           Region           	|         Diffusion Model        	|                 arXiv                	|
| 2024 11 25 	|                           Sonic: Shifting Focus to Global Audio Perception in Portrait Animation                          	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16331) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 12 04 	|               SINGER: Vivid Audio-driven Singing Video Generation with Multi-scale Spectral Diffusion Model               	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.03430) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 12 01 	|             Hallo3: Highly Dynamic and Realistic Portrait Image Animation with Diffusion Transformer Networks             	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00733) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 12 02 	|                      FLOAT: Generative Motion Latent Flow Matching for Audio-driven Talking Portrait                      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01064) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 12 13 	|                     VQTalker: Towards Multilingual Talking Avatars through Facial Motion Tokenization                     	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09892) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 12 18 	|                          Real-time One-Step Diffusion-based Expressive Portrait Videos Generation                         	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.13479) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2025 01 03 	|                            MoEE: Mixture of Emotion Experts for Audio-Driven Portrait Animation                           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.01808) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2025 02 11 	|                  Playmate: Flexible Control of Portrait Animation via 3D-Implicit Space Guided Diffusion                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07203) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|
| 2024 08 07 	|                ReSyncer: Rewiring Style-based Generator for Unified Audio-Visually Synced Facial Performer                	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.03284) 	|           Latent           	|         Encoder-Decoder        	|               ECCV 2024              	|
| 2023 01 05 	|                            Expressive Speech-driven Facial Animation with controllable emotions                           	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.02008) 	|           Latent           	|         Encoder-Decoder        	|              ICMEW 2023              	|
| 2024 01 28 	|                       Media2Face: Co-speech Facial Animation Generation With Multi-Modality Guidance                      	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.15687) 	|           Latent           	|         Diffusion Model        	|                 arXiv                	|









</details>




## LLM for Motion Planning

<details open><summary>LLM for 2D</summary>

|  **Date**  	|                                    **Title**                                   	|                                        **arXiv Link**                                       	| **Motion  Representation** 	|   **Backbone**  	|  **Tasks**  	| **Venue** 	|
|:----------:	|:------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------:	|:--------------------------:	|:---------------:	|:-----------:	|:---------:	|
| 2023 01 26 	|              Affective Faces for Goal-Driven Dyadic Communication              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.10939) 	|     3D Parameterization    	| Diffusion Model 	|  Text2Face  	|   arxiv   	|
| 2023 11 29 	| Disentangling Planning, Driving and Rendering for Photorealistic Avatar Agents 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17465) 	|           Latent           	| Encoder-Decoder 	| Taking Head 	|   arxiv   	|
| 2024 05 24 	|  InstructAvatar: Text-Guided Emotion and Motion Control for Avatar Generation  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.15758) 	|           Latent           	| Diffusion Model 	| Taking Head 	|   arxiv   	|

</details>



<details><summary>LLM for 3D</summary>

|  **Date**  	|                                               **Title**                                               	|                                        **arXiv Link**                                       	| **Motion  Representation** 	|   **Backbone**  	|      **Tasks**      	|   **Venue**  	|
|:----------:	|:-----------------------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------------:	|:--------------------------:	|:---------------:	|:-------------------:	|:------------:	|
| 2023 08 21 	|                                  Can Language Models Learn to Listen?                                 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.10897) 	|           Latent           	|  Autoregressive 	| Listener Generation 	|   ICCV 2023  	|
| 2023 06 19 	|                    MotionGPT: Finetuned LLMs Are General-Purpose Motion Generators                    	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.10900) 	|           Latent           	|  Autoregressive 	|    Text2Motion3D    	|   AAAI 2024  	|
| 2023 11 27 	|              InterControl: Generate Human Motion Interactions by Controlling Every Joint              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15864) 	|           Latent           	| Diffusion Model 	|    Text2Motion3D    	|     arXiv    	|
| 2023 11 28 	|       AvatarGPT: All-in-One Framework for Motion Understanding, Planning, Generation and Beyond       	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16468) 	|           Latent           	|  Autoregressive 	|    Text2Motion3D    	|   CVPR 2024  	|
| 2023 12 07 	|                Digital Life Project: Autonomous 3D Characters with Social Intelligence                	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04547) 	|           Latent           	| Diffusion Model 	|    Text2Motion3D    	|   CVPR 2024  	|
| 2023 12 19 	|              MotionScript: Natural Language Descriptions for Expressive 3D Human Motions              	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.12634) 	|           Latent           	| Diffusion Model 	|    Text2Motion3D    	|     arXiv    	|
| 2023 12 22 	|                   Plan, Posture and Go: Towards Open-World Text-to-Motion Generation                  	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14828) 	|           Latent           	|  Autoregressive 	|    Text2Motion3D    	|     arXiv    	|
| 2024 08 20 	| Combo: Co-speech holistic 3D human motion generation and efficient customizable adaptation in harmony 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09397) 	|           Latent           	| Encoder-Decoder 	|    Text2Motion3D    	|     arXiv    	|
| 2023 12 22 	|                 FineMoGen: Fine-Grained Spatio-Temporal Motion Generation and Editing                 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.15004) 	|           Latent           	|  Autoregressive 	|    Text2Motion3D    	| NeurIPS 2024 	|

</details>




## Cite The Survey
If you find our survey and repository useful for your research project, please consider citing our paper:

```bibtex
@article{xue2024human,
  title={Human Motion Video Generation: A survey},
  author={Xue, Haiwei and Luo, Xiangyang and Hu, Zhanghao and Zhang, Xin and Xiang, Xunzhi and Dai, Yuqin and Liu, Jianzhuang and Zhang, Zhensong and Li, Minglei and Yang, Jian and others},
  journal={Authorea Preprints},
  year={2024},
  publisher={Authorea}
  doi={10.36227/techrxiv.172793202.22697340/v1}
}
```


## Contributing

Contributions are welcome! Please feel free to create an issue or open a pull request with your contributions.


<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Winn1y"><img src="https://avatars.githubusercontent.com/u/115919287?v=4" width="100px;" alt="Haiwei Xue"/><br /><sub><b>Haiwei Xue</b></sub></a><br /><a href="https://github.com/Winn1y" title="Code">💻</a> <a href="https://github.com/Winn1y" title="Design">🎨</a> <a href="https://github.com/Winn1y" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/luoxyhappy"><img src="https://avatars.githubusercontent.com/u/110818302?v=4" width="100px;" alt="Xiangyang Luo"/><br /><sub><b>Xiangyang Luo</b></sub></a><br /><a href="https://github.com/luoxyhappy" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://hu-xiaobai.github.io/"><img src="https://avatars.githubusercontent.com/u/85933274?v=4" width="100px;" alt="Zhanghao Hu"/><br /><sub><b>Zhanghao Hu</b></sub></a><br /><a href="https://hu-xiaobai.github.io/" title="Bug reports">🥙</a> <a href="https://hu-xiaobai.github.io/" title="Code">💻</a></td>
      </tr>
    <tr>
       <td align="center" valign="top" width="14.28%"><a href="https://github.com/XinZhang0526"><img src="https://avatars.githubusercontent.com/u/148513034?v=4" width="100px;" alt="Xin Zhang"/><br /><sub><b>Xin Zhang</b></sub></a><br /><a href="https://github.com/XinZhang0526" title="Bug reports">😘🎪</a> <a href="https://github.com/XinZhang0526" title="Code">😍</a></td>
       <td align="center" valign="top" width="14.28%"><a href="https://github.com/xunzhi99"><img src="https://avatars.githubusercontent.com/u/163385641?v=4" width="100px;" alt="Xunzhi Xiang"/><br /><sub><b>Xunzhi Xiang</b></sub></a><br /><a href="https://github.com/xunzhi99" title="Bug reports">🚄</a> <a href="https://github.com/xunzhi99" title="Code">😍</a></td>
       <td align="center" valign="top" width="14.28%"><a href="https://da1yuqin.github.io"><img src="https://avatars.githubusercontent.com/u/139312004?v=4" width="100px;" alt="Yuqin Dai"/><br /><sub><b>Yuqin Dai</b></sub></a><br /><a href="https://da1yuqin.github.io" title="Bug reports">😘</a> <a href="https://da1yuqin.github.io" title="Code">👸</a></td>
    </tr>
  </tbody>
</table>


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to acknowledge the contributions of all researchers and developers in the field of human motion video generation. Their work has been instrumental in the advancement of this technology.


