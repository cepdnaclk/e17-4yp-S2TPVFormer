---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: eYY-4yp-project-template
title:
---

# 3D Occpuancy Prediction for End-to-End Autonomous Driving

In the field of autonomous driving, accurate representation of the 3D space surrounding the vehicle is crucial for various tasks such as prediction, planning, and motion control. While lidar-based approaches have been used for precise 3D object detection, they have limitations in terms of cost and sensitivity to adverse weather conditions. As a result, achieving reliable and accurate 3D perception using only one or multiple RGB images has become the **holy grail** for autonomous driving. Additionally, temporal reasoning, along with spatial reasoning, plays a vital role in autonomous driving models. Therefore, our project aims to combine the strengths of various approaches to **develop a vision-based End-to-End autonomous driving model** that can compete with existing architectures. However, our **primary goal during the FYP is to _focus on 3D occupancy prediction that can enhance downstream driving and vision tasks_**.

### Team

{% for member in site.data.index.team %}
- {{ member.eNumber }} - {{ member.name }} - [{{ member.email }}](mailto:{{ member.email }})
{% endfor %}

### Supervisors

{% for supervisor in site.data.index.supervisors %}
- {{ supervisor.name }} - [{{ supervisor.email }}](mailto:{{ supervisor.email }})
{% endfor %}


### \[⭐Bookmarks\] Related Articles, Blogs
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


### Timeline

- **[Apr 27th, 2023]** Literature review started (reading the papers [Attention is All you Need](https://arxiv.org/abs/1706.03762), [NEAT](https://arxiv.org/abs/2109.04456) and [TCP](https://arxiv.org/abs/2206.08129)).
- **[May 12th, 2023]** First meeting with the supervisors, pitching the ideas.
- **[Week starting on May 14th, 2023]** Started reading [BEVFormer](https://arxiv.org/abs/2203.17270), [TPVFormer](https://github.com/wzzheng/TPVFormer), [SurroundOcc](https://arxiv.org/abs/2303.09551), [OccFormer](https://arxiv.org/abs/2304.05316), and other related papers/articles about vision-centric 3D Occupancy prediction for autonomous driving.
- **[Week starting on May 21st, 2023]** Downloading the [nuScenes](https://www.nuscenes.org/nuscenes/) dataset to the department server. 💡New idea popped out, added to the [doc](https://docs.google.com/document/d/1Q0V5T9e5vz9v4gMgqhBe68V2NfEGpRri8H5HDJT0jig/edit?usp=sharing). Getting familar with [mmcv](https://mmengine.readthedocs.io/en/latest/tutorials/runner.html). **_"Understand the runner class, then you will understand everything."_** ~gihan jayatilake <br>Ran a training loop of the TPVFormer with the 3D Occupancy head.
- [Rest of the timeline](https://docs.google.com/spreadsheets/d/1HMXVH5t07wr_fwBvPOInlXgtxpGAyylD0ZThz48vP4E/edit?usp=sharing)

---

### Quick Links

- [Project Repository](https://github.com/cepdnaclk/e17-4yp-3D-Occupancy-Prediction-for-Autonomous-Driving)
- [Project Diary](https://docs.google.com/document/d/1ws0hRpEfZc4wDm7a-rtydrG4abKDJQv4r4gB88s6gLo/edit?usp=sharing)
- [Meeting Notes](https://drive.google.com/drive/folders/12DhoAxGAD_xgDAIP6TBwrTsmBXJAfI4c?usp=sharing)
- [IDEAs💡](https://docs.google.com/document/d/1Q0V5T9e5vz9v4gMgqhBe68V2NfEGpRri8H5HDJT0jig/edit?usp=sharing)
- [Literature Review Summary](https://docs.google.com/spreadsheets/d/1t0dZtdaSt9DUCvQl5zDW9iCib0_WepOSmF6MImoRdKg/edit?usp=sharing)
- [Paper Summaries](https://drive.google.com/drive/folders/1MJF-aodwWPemzLQnnnE4CN6oSKosoytd?usp=sharing)
- [Jamboard](https://jamboard.google.com/d/11U-PCR4-SQXJWzTMW90iI3Ad9wVkUIkfwcz_y7w39Ts/viewer?pli=1&f=2)

<!-- ### Other Links
- [Project Page](https://url.ce.pdn.ac.lk/e17-4yp-3D-Occ-for-AD)
- [University of Peradeniya](https://eng.pdn.ac.lk/)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/) -->



