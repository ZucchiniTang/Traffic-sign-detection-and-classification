# Traffic-sign-detection-and-classification

## 1. Idea

1. __Extract__ better __feature map__ which input to detection/classification model
    1. Using __Saliency map__ (try to combine traditional and Neural network method to get saliency map) 
        1. Traditional method
            1. Paper: *Accurate and Efficient Traffic Sign Detection Using Discriminative AdaBoost and Support Vector Regression* http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7328325 
              1. Page 4008: Enhancd Feature Pyramids - 根据traffic sign的颜色和（形状）特性来改变color channel.
              2. Page 4010: Learn a Gaussian mixture model(GMM) to approximate the distribution of these signs' positions in the detection image.
        2. Neural Network method
            1. Paper: *Shallow and Deep Convolutional Networks for Saliency Prediction* - shallow and deep CNN model, transfer learning
            2. Paper: *SalGAN: Visual Saliency Prediction with Generative Adversarial Networks* - GAN
    2. Using Segmentation 'U-Net' to remove background 
        1. What is 'U-Net': 用于图像分割的神经网络架构。 U-Net最初被设计用于生物医学图像分割（例如，在CT扫描中识别肺结节），但它也可用于分割常规2D图像。在下文将看到，即使没有大数据集，U-Net的强大功能也能让你大吃一惊。

          



```python

```
