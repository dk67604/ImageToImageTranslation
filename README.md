# ImageToImageTranslation
The project was propsed for a course CSCI 8000 Advanced Topics in Machine Learning offered by Dr. Sheng Li. In the recent past, Generative Adversarial Networks have received substantial attention in the area of deep learning. There are several flavors of Generative Adversarial Networks, each having their own pros and cons over one and other. In this project we explore two different networks on the task of Image to  Image Translation: Conditional Generative Adversarial Network and Wasserstein Generative Adversarial Network. For both these methods we adopted the pix2pix architecture. With the advent of mobile computer vision, the current deep learning models face an in-memory problem when it comes to performing inferences. To address this problem we used Depthwise Separable Convolutions to reduce the network size. 

Our implementation is inspired by below code
Code Reference: https://github.com/eriklindernoren/Keras-GAN

### Dataset 
- Facade Dataset
- Link: https://people.eecs.berkeley.edu/~tinghuiz/projects/pix2pix/datasets/

### Notebooks description
- pix2pix : Basic CGAN adopting pix2pix(https://arxiv.org/pdf/1611.07004.pdf)
- pix2pix_mobile : Implemented Mobile version using the idea of Depthwise Seperable Convolution
- wgan : Variation in WGAN using pix2pix approach(http://cs230.stanford.edu/projects_spring_2018/reports/8289943.pdf)
- wgan_mobile : Implemented Mobile version using the idea of Depthwise Seperable Convolution

### Requirement:
- Python 3.5
- tensorflow 1.10.0(cpu)
- Keras 2.2.4(cpu)
- tensorflow 1.4.1(gpu)
- if GPU, Keras 2.1.4


