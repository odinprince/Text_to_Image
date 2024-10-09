# Text to Image Synthesis Synthesis using Generative Adversarial Networks

## Intoduction

This project is mainly inspired from [Generative Adversarial Text-to-Image Synthesis paper](https://arxiv.org/abs/1605.05396). We implemented this model using PyTorch. In this model we train a conditional generative adversarial network, conditioned on text captions, to generate images that correspond to the captions. The network architecture is shown below. 

<figure><img src='images/dcgan_network.png'></figure>
Credits: [1]


## Datasets
The datasets can be downloaded from [Caltech-UCSD Birds 200](http://www.vision.caltech.edu/visipedia/CUB-200.html) and [Oxford Flowers](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/) datasets.

