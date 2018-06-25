# Satellite Image Classification for Planet: Understanding the Amazon from Space

This repository is an example notebook for satellite image classification. Slides can be seen [here](https://docs.google.com/presentation/d/1B32QGa3Fa26d9tEFVtFrlP3D3z31Qggc2CqIISSS7C8/edit?usp=sharing).


We use a ResNet34 architecture pretrained on ImageNet. Some tricks such as data augmentation, slanted triangular learning rates,  and discriminative learning rates are used to maximize performance. With one hour of training, we got best samples F2 score of 0.933028, which is almost as good as the winner of private leaderboard at 0.93317.
