## MobileNet

Paper: MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications
Link: https://arxiv.org/pdf/1704.04861.pdf

For mobile and embedded vision applications
eg object detection, finegrain classification, face attributes and large scale geo-localization.

object: focus on optimizing for latency but also yield small networks

 Inception models: Batch normalization: accelerating deep network training by reducing internal covariate shift
 Flattened networks: feedforward accelearation ; build a network out of fully factorized convolutions and showed the potential of extremely factorized networks
 Factorized Networks: topological connections
 Xception network: 
 Squeezenet:
 
 tricks：
 spatial separable convolutions： seperate a kernel into two small kernel, eg sobel will be replaced with [1 2 1]^T*[-1 0 1]
 Depthwise Convolution:
 Pointwise Convolution:
 1x1 Kernels:
