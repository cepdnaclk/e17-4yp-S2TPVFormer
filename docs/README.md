---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: eYY-4yp-project-template
title:
---

# Project Title

In the field of autonomous driving, accurate representation of the 3D space surrounding the vehicle is crucial for various tasks such as prediction, planning, and motion control. While lidar-based approaches have been used for precise 3D object detection, they have limitations in terms of cost and sensitivity to adverse weather conditions. As a result, achieving reliable and accurate 3D perception using only one or multiple RGB images has become the **holy grail** for autonomous driving. Additionally, temporal reasoning, along with spatial reasoning, plays a vital role in autonomous driving models. Therefore, our project aims to combine the strengths of various approaches to **develop a vision-based End-to-End autonomous driving model** that can compete with existing architectures. However, our **primary goal during the FYP is to _focus on 3D occupancy prediction that can enhance downstream driving and vision tasks_**.

#### Team

{% for member in site.data.index.team %}
- {{ member.eNumber }} - {{ member.name }} - [{{ member.email }}](mailto:{{ member.email }})
{% endfor %}

#### Supervisors

{% for supervisor in site.data.index.supervisors %}
- {{ supervisor.name }} - [{{ supervisor.email }}](mailto:{{ supervisor.email }})
{% endfor %}

#### Table of content

1. [Abstract](#abstract)
2. [Related works](#related-works)
3. [Methodology](#methodology)
4. [Experiment Setup and Implementation](#experiment-setup-and-implementation)
5. [Results and Analysis](#results-and-analysis)
6. [Conclusion](#conclusion)
7. [Publications](#publications)
8. [Links](#links)

---

## Abstract

## Related works

## Methodology

## Experiment Setup and Implementation

## Results and Analysis

## Conclusion

## Publications
[//]: # "Note: Uncomment each once you uploaded the files to the repository"

<!-- 1. [Semester 7 report](./) -->
<!-- 2. [Semester 7 slides](./) -->
<!-- 3. [Semester 8 report](./) -->
<!-- 4. [Semester 8 slides](./) -->
<!-- 5. Author 1, Author 2 and Author 3 "Research paper title" (2021). [PDF](./). -->


## Links

[//]: # ( NOTE: EDIT THIS LINKS WITH YOUR REPO DETAILS )

- [Project Repository](https://github.com/cepdnaclk/repository-name)
- [Project Page](https://cepdnaclk.github.io/repository-name)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)