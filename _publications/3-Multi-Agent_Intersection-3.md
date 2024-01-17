---
title: "Multi-Vehicle Trajectory Prediction and Control at Intersections using State and Intention Information"
collection: publications
permalink: /publication/Multi-Agent_Intersection
---

2022.1 - 2022.12 (Accepted by Neurocomputing)

<center>
<b>Dekai Zhu*</b>, Qadeer Khan*, Prof. Daniel Cremers <br /> 
Technical University of Munich 
</center>


![shape](../images/intersection.png)


<p align = "justify"> 
Traditional deep learning approaches for prediction of future trajectory of multiple road agents rely on knowing information about their past trajectory. In contrast, this work utilizes information of only the current state and intended direction to predict the future trajectory of multiple vehicles at intersections. Incorporating intention information has two distinct advantages: (1) It allows to not just predict the future trajectory but also control the multiple vehicles. (2) By manipulating the intention, the interaction among the vehicles is adapted accordingly to achieve desired behavior. Both these advantages would otherwise not be possible using only past trajectory information Our model utilizes message passing of information between the vehicle nodes for a more holistic overview of the environment, resulting in better trajectory prediction and control of the vehicles. This work also provides a thorough investigation and discussion into the disparity between offline and online metrics for the task of multi-agent control. We particularly show why conducting only offline evaluation would not suffice, thereby necessitating online evaluation. We demonstrate the superiority of utilizing intention information rather than past trajectory in online scenarios. Lastly, we show the capability of our method in adapting to different domains through experiments conducted on two distinct simulation platforms i.e. SUMO and CARLA.
</p>

[[project page](https://dekai21.github.io/Multi_Agent_Intersection/)]
[[video](https://github.com/Dekai21/Multi_Agent_Intersection/tree/master/videos)]
[[code](https://github.com/Dekai21/Multi_Agent_Intersection)]
[[paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231223013437)]
[[arxiv](https://arxiv.org/abs/2301.02561)]