---
layout: home
permalink: index.html

repository-name: eYY-4yp-project-template
title: S2TPVFormer Landing Page
---

# A Spatiotemporal Approach to Tri-Perspective Representation for 3D Semantic Occupancy Prediction

> [Sathira Silva](https://scholar.google.com/citations?user=3ZiP8OYAAAAJ&hl=en)*, [Savindu Wannigama](https://scholar.google.com/citations?user=I6kUmVIAAAAJ&hl=en)\*, [Gihan Jayatilaka](https://scholar.google.com/citations?user=ZsJpIO8AAAAJ&hl=en) $\ddagger$, [Muhammad Haris Khan](https://scholar.google.com/citations?user=ZgERfFwAAAAJ&hl=en) $\ddagger$, [Prof. Roshan Ragel](https://scholar.google.com/citations?user=UTYj8usAAAAJ&hl=en) $\dagger$

\* Equal contribution, $\ddagger$ Project Co-supervisor, $\dagger$ Project Supervisor


#### [**Link to the Paper**](https://arxiv.org/abs/2401.13785)

## Abstract

Holistic understanding and reasoning in 3D scenes are crucial for the success of autonomous driving systems. The evolution of 3D semantic occupancy prediction as a pretraining task for autonomous driving and robotic applications captures finer 3D details compared to traditional 3D detection methods. Vision-based 3D semantic occupancy prediction is increasingly overlooked in favor of LiDAR-based approaches, which have shown superior performance in recent years. However, we present compelling evidence that there is still potential for enhancing vision-based methods. Existing approaches predominantly focus on spatial cues such as tri-perspective view (TPV) embeddings, often overlooking temporal cues. This study introduces S2TPVFormer, a spatiotemporal transformer architecture designed to predict temporally coherent 3D semantic occupancy. By introducing temporal cues through a novel Temporal Cross-View Hybrid Attention mechanism (TCVHA), we generate Spatiotemporal TPV (S2TPV) embeddings that enhance the prior process. Experimental evaluations on the nuScenes dataset demonstrate a significant **+4.1$%** of absolute gain in mean Intersection over Union (mIoU) for 3D semantic occupancy compared to baseline TPVFormer, validating the effectiveness of S2TPVFormer in advancing 3D scene perception.

## Introduction

Temporal reasoning holds equal importance to spatial reasoning in a cognitive perception system. In human perception, temporal information is crucial for identifying occluded objects and determining the motion state of entities. A system proficient in spatiotemporal reasoning excels in making inferences with high temporal coherence. While previous works emphasize the significance of temporal fusion in 3D object detection, earlier attempts at 3D Semantic Occupancy Prediction (3D SOP) often overlooked the value of incorporating temporal information. The current state-of-the-art in 3D SOP literature seldom exploits temporal cues. This is evident in [TPVFormer](https://github.com/wzzheng/tpvformer)’s SOP visualizations, where adjacent prediction frames lack temporal coherence as they rely solely on the current time step for semantic predictions. 

This work introduces S2TPVFormer, a variant of [TPVFormer](https://github.com/wzzheng/tpvformer), which utilizes a spatiotemporal transformer architecture inspired by [BEVFormer](https://github.com/fundamentalvision/BEVFormer), for dense and temporally coherent 3D semantic occupancy prediction. Leveraging TPV (Top View and Voxel) representation, the model’s spatiotemporal encoder generates temporally rich embeddings, fostering coherent predictions. The study proposes a novel **Temporal Cross-View Hybrid Attention** mechanism, enabling the exchange of spatiotemporal information across different views. To illustrate the efficacy of temporal information incorporation and the potential of the new attention mechanism, the research explores three distinct temporal fusion paradigms.

### Overview of our Contributions

To summarize, this work contributes in the following ways;

- We introduce S2TPVFormer, featuring a novel temporal fusion workflow for TPV representation, and demonstrate how CVHA facilitates the sharing of spatiotemporal information across the three planes.
- S2TPVFormer achieves significant improvements in the 3D SOP task on the nuScenes validation set, with a **+4.1%** mIOU gain over the baseline TPVFormer, highlighting that vision-based 3D SOP still has considerable potential for improvement.


## Architecture

<img src="assets/architecture.jpeg" alt="Table 1" width="750">


## Model Configurations

<img src="assets/table1.jpeg" alt="Table 1" width="400">



## Results

<img src="assets/table2.jpeg" alt="Table 1" width="750">
<img src="assets/table3.jpeg" alt="Table 1" width="750">
<img src="assets/table4.jpeg" alt="Table 1" width="750">



### Team

{% for member in site.data.index.team %}
- {{ member.eNumber }} - {{ member.name }} - [{{ member.email }}](mailto:{{ member.email }})
{% endfor %}

### Supervisors

{% for supervisor in site.data.index.supervisors %}
- {{ supervisor.name }} - [{{ supervisor.email }}](mailto:{{ supervisor.email }})
{% endfor %}



<!-- --- -->

<!-- ### \[⭐Bookmarks\] Related Articles, Blogs
- [CVPR2023-3D-Occupancy-Prediction](https://github.com/CVPR2023-3D-Occupancy-Prediction/CVPR2023-3D-Occupancy-Prediction)
- [Monocular Bird’s-Eye-View Semantic Segmentation for Autonomous Driving](https://towardsdatascience.com/monocular-birds-eye-view-semantic-segmentation-for-autonomous-driving-ee2f771afb59)
- [Monocular BEV Perception with Transformers in Autonomous Driving](https://towardsdatascience.com/monocular-bev-perception-with-transformers-in-autonomous-driving-c41e4a893944)
- [Monocular 3D Object Detection in Autonomous Driving — A Review](https://towardsdatascience.com/monocular-3d-object-detection-in-autonomous-driving-2476a3c7f57e)
- [Deep Understanding Tesla FSD Part 1: HydraNet](https://saneryee-studio.medium.com/deep-understanding-tesla-fsd-part-1-hydranet-1b46106d57)
- [Deep Understanding Tesla FSD Part 2: Vector Space](https://saneryee-studio.medium.com/deep-understanding-tesla-fsd-part-2-vector-space-2964bfc10b17)
- [Andrej Karpathy's Interpretation of Transformer: Communicate Phase & Compute Phase](https://youtu.be/XfpMkf4rD6E?t=1353)
- [DeepSORT: Deep Learning to Track Custom Objects in a Video](https://nanonets.com/blog/object-tracking-deepsort/)
- [Open-MMLab repos](https://github.com/open-mmlab/mmengine)
- [What are Intrinsic and Extrinsic Camera Parameters in Computer Vision?](https://towardsdatascience.com/what-are-intrinsic-and-extrinsic-camera-parameters-in-computer-vision-7071b72fb8ec)
- [Vision-centric Semantic Occupancy Prediction for Autonomous Driving](https://towardsdatascience.com/vision-centric-semantic-occupancy-prediction-for-autonomous-driving-16a46dbd6f65)
- [What is Gradient Accumulation in Deep Learning?](https://towardsdatascience.com/what-is-gradient-accumulation-in-deep-learning-ec034122cfa)
- [Master the overall construction process of MMDetection](https://zhuanlan.zhihu.com/p/341954021)
- [Awesome-Occupancy-Prediction-Multi-Cameras](https://github.com/chaytonmin/Awesome-Surrounding-Semantic-Occupancy-Prediction) -->

<!-- ### Timeline

- **[Apr 27th, 2023]** Literature review started (reading the papers [Attention is All you Need](https://arxiv.org/abs/1706.03762), [NEAT](https://arxiv.org/abs/2109.04456) and [TCP](https://arxiv.org/abs/2206.08129)).
- **[May 12th, 2023]** First meeting with the supervisors, pitching the ideas.
- **[Week starting on May 14th, 2023]** Started reading [BEVFormer](https://arxiv.org/abs/2203.17270), [TPVFormer](https://github.com/wzzheng/TPVFormer), [SurroundOcc](https://arxiv.org/abs/2303.09551), [OccFormer](https://arxiv.org/abs/2304.05316), and other related papers/articles about vision-centric 3D Occupancy prediction for autonomous driving.
- **[Week starting on May 21st, 2023]** Downloading the [nuScenes](https://www.nuscenes.org/nuscenes/) dataset to the department server. 💡New idea popped out, added to the [doc](https://docs.google.com/document/d/1Q0V5T9e5vz9v4gMgqhBe68V2NfEGpRri8H5HDJT0jig/edit?usp=sharing). Getting familar with [mmcv](https://mmengine.readthedocs.io/en/latest/tutorials/runner.html). **_"Understand the runner class, then you will understand everything."_** ~gihan jayatilake <br>Ran a training loop of the TPVFormer with the 3D Occupancy head.
- [Rest of the timeline](https://docs.google.com/spreadsheets/d/1HMXVH5t07wr_fwBvPOInlXgtxpGAyylD0ZThz48vP4E/edit?usp=sharing) -->

<!-- ---

### Quick Links

- [Project Repository (public)](https://github.com/cepdnaclk/e17-4yp-3D-Occupancy-Prediction-for-Autonomous-Driving)
- [Project Repository (private)](https://github.com/autonomousperception/S2TPVFormer)
- [UMD logs (private)](https://github.com/autonomousperception/umd-logs/tree/main)
- [gihans-repo-copy (private)](https://github.com/autonomousperception/gihans-repo-copy)
- [Project Diary](https://docs.google.com/document/d/1ws0hRpEfZc4wDm7a-rtydrG4abKDJQv4r4gB88s6gLo/edit?usp=sharing)
- [Meeting Notes](https://drive.google.com/drive/folders/12DhoAxGAD_xgDAIP6TBwrTsmBXJAfI4c?usp=sharing)
- [IDEAs💡](https://docs.google.com/document/d/1Q0V5T9e5vz9v4gMgqhBe68V2NfEGpRri8H5HDJT0jig/edit?usp=sharing)
- [Literature Review Summary](https://docs.google.com/spreadsheets/d/1t0dZtdaSt9DUCvQl5zDW9iCib0_WepOSmF6MImoRdKg/edit?usp=sharing)
- [Paper Summaries](https://drive.google.com/drive/folders/1MJF-aodwWPemzLQnnnE4CN6oSKosoytd?usp=sharing)
- [Jamboard](https://jamboard.google.com/d/11U-PCR4-SQXJWzTMW90iI3Ad9wVkUIkfwcz_y7w39Ts/viewer?pli=1&f=2)
- [WANDB.AI](https://wandb.ai/fyp-3d-occ)
- [Experiment Results](https://docs.google.com/spreadsheets/d/1i-JYNyIdzsA-OY0sdwwf0jy-vq9h5CuZkAKE_B4S8iU/edit#gid=610804817) -->

<!-- ### Important  Links

- [Zoom Meetings](https://learn.zoom.us/j/61977437413?pwd=SEdRSHNsQUQ0OGcwakxVNkhlOGt4Zz09)
- [CVPR 2023 Leaderboard](https://opendrivelab.com/AD23Challenge.html#3d_occupancy_prediction)
- [CVPR 2023 3D SOP Benchmark](https://github.com/CVPR2023-3D-Occupancy-Prediction/CVPR2023-3D-Occupancy-Prediction)
- [Latest & Biggest 3D SOP Benchmark (OpenOcc)](https://github.com/OpenDriveLab/OpenScene)
- [2024 opendrivelab challenge](https://opendrivelab.com/AD24Challenge.html) -->
