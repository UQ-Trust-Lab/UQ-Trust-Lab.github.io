+++
title = "Reliable Model Conversion"
date = 2023-11-08

[extra]
hero = "/ICSE2023_MOB_Hao_Hero.png"
+++

As machine learning technology becomes increasingly prevalent, its applications have broadened from high-performance servers to encompass mobile and embedded devices.
Given the resource limitations inherent in these smaller devices, machine learning models frequently require conversion before deployment.

Prominent machine learning frameworks such as PyTorch and TensorFlow offer tools to facilitate this process.
However, the complexity of the models can lead to errors during optimization, potentially impeding successful deployment.

Although machine learning bugs on training and inference have been studied extensively, the characteristics of model conversion bugs have not been explored in detail.

<!-- more -->

![landscape](/ICSE2023_MOB_Hao_Preview.jpg)

## Empirical Study on Model Optimization Bugs

After the model training, some optimization techniques like pruning and quantization can enhance the size efficiency and speed of models, which is a common part of model conversion.
However, these optimization techniques make significant changes to the model and may introduce bugs.
These issues are collectively termed as Model Optimization Bugs (MOBs).

In our study, we present the first comprehensive categorization and analysis of MOBs.
We collect a dataset of 371 MOBs from the PyTorch and TensorFlow repositories and conduct a comprehensive study on the bugs.
We have identified four symptom categories and five root causes.

With the analysis on the root causes and the existing bug detection techniques, we have summarized five challenges in the detection of MOBs.
Based on our insights, we propose actionable recommendations for framework developers and end-users to mitigate these challenges effectively.

![portrait](/ICSE2023_MOB_Hao_Method.png)

## Paper

- Hao Guan, Ying Xiao, Jiaying Li, Yepang Liu, Guangdong Bai, **A Comprehensive Study of Real-World Bugs in Machine Learning Model Optimization**,
*The International Conference on Software Engineering (ICSE) , 2023*.
