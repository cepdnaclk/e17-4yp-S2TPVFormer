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

### Quick Links

- [Project Repository](https://github.com/cepdnaclk/e17-4yp-3D-Occupancy-Prediction-for-Autonomous-Driving)
- [Meeting Notes](https://drive.google.com/drive/folders/12DhoAxGAD_xgDAIP6TBwrTsmBXJAfI4c?usp=sharing)
- [Paper Summaries](https://drive.google.com/drive/folders/1MJF-aodwWPemzLQnnnE4CN6oSKosoytd?usp=sharing)
- [IDEAs💡](https://docs.google.com/document/d/1Q0V5T9e5vz9v4gMgqhBe68V2NfEGpRri8H5HDJT0jig/edit?usp=sharing)

### \[⭐Bookmarks\] Related Articles, Blogs
- [Monocular Bird’s-Eye-View Semantic Segmentation for Autonomous Driving](https://towardsdatascience.com/monocular-birds-eye-view-semantic-segmentation-for-autonomous-driving-ee2f771afb59)
- [Monocular BEV Perception with Transformers in Autonomous Driving](https://towardsdatascience.com/monocular-bev-perception-with-transformers-in-autonomous-driving-c41e4a893944)
- [Monocular 3D Object Detection in Autonomous Driving — A Review](https://towardsdatascience.com/monocular-3d-object-detection-in-autonomous-driving-2476a3c7f57e)
- [Deep Understanding Tesla FSD Part 1: HydraNet](https://saneryee-studio.medium.com/deep-understanding-tesla-fsd-part-1-hydranet-1b46106d57)
- [Deep Understanding Tesla FSD Part 2: Vector Space](https://saneryee-studio.medium.com/deep-understanding-tesla-fsd-part-2-vector-space-2964bfc10b17)

### Timeline

\>\> TODO

---

### Related Links

- [Project Repository](https://github.com/cepdnaclk/e17-4yp-3D-Occupancy-Prediction-for-Autonomous-Driving)
- [Project Page](https://url.ce.pdn.ac.lk/e17-4yp-3D-Occ-for-AD)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)