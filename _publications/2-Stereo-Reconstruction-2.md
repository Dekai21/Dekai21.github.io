---
title: "Stereo Reconstruction"
collection: publications
permalink: /publication/Stereo-Reconstruction
---

2021.5 - 2021.8

<center>
<b>Dekai Zhu</b>, Dongyue Lu, Qianyi Yang, Weihua Huang <br /> 
Supervisor: Yuchen Rao, Prof. Angela Dai <br /> 
Technical University of Munich 
</center>


![shape](../images/stereo.png)


<p align = "justify"> 
In this project, we apply different stereo matching methods to reconstruct 3D scenes and compare their performance. Based on key-point detectors and eight-point algorithm, we recover the camera's extrinsic and rectify the images from left and right camera for the next step. Then we apply three dense matching methods to generate the disparity map respectively and further reconstruct the 3D scene. We evaluate the impact of different detectors and bundle adjustment on the accuracy of the estimated transformation. The experiment shows that SIFT performs better than ORB, and the accuracy of the estimated transform is also improved after using bundle adjustment. For dense matching, with PSMNet, which is the SOTA in disparity prediction, we can get much higher precision than classic methods block matching and semi-global matching.
</p>

[[project report](http://dylanorange.github.io/files/3d.pdf)]
[[code](https://github.com/Dekai21/Stereo_Reconstruction)]