# Awesome Personalized Driving


![Version](https://img.shields.io/badge/Version-1.0-yellow.svg)
![Topic](https://img.shields.io/badge/Topic-personalized--driving-%23ff69b4.svg)


This is a selection of state-of-the-art research materials (datasets, blogs, papers and public codes) on personalized driving. Wish it could be helpful for both academia and industry. (Still updating)

**Maintainer**: [**Naren Bao**](https://honalele.github.io/homepage/) (Gradute School of Informatics, Nagoya University)

**Email**: bao.naren@g.sp.m.is.nagoya-u.ac.jp

Please feel free to pull request to add new resources or send emails to us for questions, discussion and collaborations.

Please consider citing our work if you found this repo useful:

```
@inproceedings{10.1109/ITSC.2019.8917457,
author = {Bao, Naren and Yang, Dongfang and Carballo, Alexander and \"{O}zg\"{u}ner, \"{U}mit and Takeda, Kazuya},
title = {Personalized Safety-Focused Control by Minimizing Subjective Risk},
year = {2019},
organization = {IEEE},
booktitle = {2019 IEEE Intelligent Transportation Systems Conference (ITSC)},
pages = {3853–3858},
location = {Auckland, New Zealand}
}
```

### Table of Contents

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->
- [**Datasets**](#datasets)
	- [Vehicles and Drivers](#vehicles-and-drivers)
- [**Literature and Codes**](#literature-and-codes)
	- [Survey Papers](#survey-papers)
	- [Driver Model](#driver-model)
	- [Model Predictive Control](#model-predictive-control)
	- [Data-driven Control](#data-driven-control)
	- [Decision Making](#decision-making)
	- [Path Planning](#path-planning)
	- [Benchmark and Evaluation Metrics](#benchmark-and-evaluation-metrics)
	- [Others](#others)
<!-- /TOC -->


## **Datasets**
|                           Dataset                            |            **Driver Info**            |         Scenarios         |        Sensors         |
| :----------------------------------------------------------: | :--------------------------: | :-----------------------: | :--------------------: |
|      [INTERACTION](http://www.interaction-dataset.com/)      | -  | Roundabout / intersection |     Camera     |
|        [KITTI](http://www.cvlibs.net/datasets/kitti/)        | -  |   Highway / rural areas   |     Camera / LiDAR     |
|           [HighD](https://www.highd-dataset.com/)            | -  |          Highway          |         Camera         |
| [NGSIM](https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm) |    -     |      Highway   |         Camera         |
|            [nuScenes](https://www.nuscenes.org/)             |           -           |           Urban           | Camera / LiDAR / RADAR |
|  [BDD100k](https://bdd-data.berkeley.edu/)           | - |      Highway / urban      |         Camera         |
| [Apolloscapes](http://apolloscape.auto/?source=post_page-) | - |           Urban           |         Camera         |
| [Argoverse](https://www.argoverse.org/)            |      -     |           Urban           |     Camera / LiDAR     |
[Lyft Level 5](https://level5.lyft.com/dataset/)               | 20     | Urban                     | Camera/ LiDAR      
[**Ours NU_lane_changes**](https://level5.lyft.com/dataset/)               | 11    | Highway                     | Camera/ CAN 


## **Literature and Codes**
### Survey Papers
### Model Predictive Control
- Learning-based Model Predictive Control for Safe Exploration, CDC 2018 \[[paper](https://arxiv.org/abs/1803.08287)\]
- Practical Reinforcement Learning For MPC: Learning from sparse objectives in under an hour on a real robot, 2020 \[[paper](https://arxiv.org/pdf/2003.03200.pdf)\]
- ABC-LMPC: Safe Sample-Based Learning MPC for Stochastic Nonlinear Dynamical Systems with Adjustable Boundary Conditions, 2020 [[paper](https://arxiv.org/pdf/2003.01410.pdf)\]
- Adaptive MPC under Time Varying Uncertainty: Robust and Stochastic, 2020 [[paper](https://arxiv.org/pdf/1909.13473.pdf)\]



