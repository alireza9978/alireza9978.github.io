---
title: "Achieving Pareto Optimality using Efficient Parameter Reduction for DNNs in Resource-Constrained Edge Environment"
collection: publications
permalink: /publication/pareto-optimality
date: 2024-03-14
venue: 'Canadian AI 2024'
paperurl: 'https://arxiv.org/abs/2403.10569'
---
This paper proposes an optimization of an existing Deep Neural Network (DNN) that improves its hardware utilization and facilitates on-device training for resource-constrained edge environments. We implement efficient parameter reduction strategies on Xception that shrink the model size without sacrificing accuracy, thus decreasing memory utilization during training. We evaluate our model in two experiments: Caltech-101 image classification and PCB defect detection and compare its performance against the original Xception and lightweight models, EfficientNetV2B1 and MobileNetV2. The results of the Caltech-101 image classification show that our model has a better test accuracy (76.21%) than Xception (75.89%), uses less memory on average (847.9MB) than Xception (874.6MB), and has faster training and inference times. The lightweight models overfit with EfficientNetV2B1 having a 30.52% test accuracy and MobileNetV2 having a 58.11% test accuracy. Both lightweight models have better memory usage than our model and Xception. On the PCB defect detection, our model has the best test accuracy (90.30%), compared to Xception (88.10%), EfficientNetV2B1 (55.25%), and MobileNetV2 (50.50%). MobileNetV2 has the least average memory usage (849.4MB), followed by our model (865.8MB), then EfficientNetV2B1 (874.8MB), and Xception has the highest (893.6MB). We further experiment with pre-trained weights and observe that memory usage decreases thereby showing the benefits of transfer learning. A Pareto analysis of the models' performance shows that our optimized model architecture satisfies accuracy and low memory utilization objectives.

[Download paper here](https://arxiv.org/abs/2403.10569)

Recommended citation:
Mih, A. N., Rahimi, A., Kawnine, A., Palma, F., Wachowicz, M., Dubay, R., & Cao, H. (2024). Achieving Pareto Optimality using Efficient Parameter Reduction for DNNs in Resource-Constrained Edge Environment. arXiv preprint arXiv:2403.10569.