# Understanding deep learning
The aim of this repo is to list some of the deep learning resources to go through in order to better understand core concepts, architectures, and techniques of deep learning. A paper to read is to be decided by participants each week. 

## Monday 19th November 2018
AlexNet is one of the first architectures that has deep layers (eight layers: 5 convolutional layers and 3 fully-connected layers), reducing the Top-5 error rate by ~9% on the 2010 ImageNet classification competition data.

1. Paper to read: https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf
2. Lectures that would be helpful to understand jargons and concepts in the paper: 
  * Standford CS231n: Convolutional Neural Networks for Visual Recognition Lecture 1-5 https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv
  * Code-oriented lectures on deep learning: https://www.fast.ai/, in particular, Part 1 will be helpful: https://course.fast.ai/
3. My notes on the paper: http://yjpark.me/blog/jekyll/update/2018/11/09/notes-on-alexnet.html
4. Other blogs that were helpful: https://medium.com/@smallfishbigsea/a-walk-through-of-alexnet-6cbd137a5637

## Monday 26th November 2018
ZFNet (Zeiler Furgus Net) won 2013 ImageNet challenge by visualising each layer of AlexNet and using these to modify and improve hyperparameters of AlexNet. 2013 paper could be read in conjunction with Zeiler et al., 2011 (DeconvNet).

1. Papers to read: Zeiler and Furgus, 2013 (https://arxiv.org/abs/1311.2901) and Zeiler et al., 2011 (http://www.matthewzeiler.com/wp-content/uploads/2017/07/iccv2011.pdf)

2. Dive into Pytorch through Udacity Intro to Deep Learning with PyTorch: https://www.udacity.com/course/deep-learning-pytorch--ud188 (practice materials available here https://github.com/udacity/deep-learning-v2-pytorch)

3. My notes on the paper: http://yjpark.me/blog/jekyll/update/2018/11/18/notes-on-zfnet.html

4. Other resources: Visualisation of Resnet-based models through Gradient-weighted Class Activation Mapping (Grad-CAM) https://arxiv.org/abs/1610.02391


## Monday 3rd December 2018
Zeiler et al., 2011 (DeconvNet) and Selvaraju et al., 2016 (Grad-CAM) provides visualisation techniques for layers in your model. This week, we decided to attempt to visualise our model on any choice of data sets.

1. Papers to read: Zeiler et al., 2011 (http://www.matthewzeiler.com/wp-content/uploads/2017/07/iccv2011.pdf) or Visualisation of Resnet-based models through Gradient-weighted Class Activation Mapping (Grad-CAM) https://arxiv.org/abs/1610.02391

2. My notes on the paper: http://yjpark.me/blog/jekyll/update/2018/12/02/notes-on-grad-cam.html

## Monday 10th December 2018
We decided to read the VGG paper by Oxford Visual Geometry Group since we came across VGG16 and VGG19 frequently while studying visualisations. VGG is also one of the winners of ImageNet challenge 2014. 
1. Paper to read: Simonyan and Zisserman, 2014 (https://arxiv.org/abs/1409.1556)

2. My notes on the paper: http://yjpark.me/blog/jekyll/update/2018/12/09/notes-on-vgg.html

## Monday 14th January 2019
The first paper to read in a new year is the ResNet paper. Though the paper was from 2015, the ResNet model has been consistently used (modified or not) in many recent models such as Residual Attention Network (Wang et al., 2017) and SENet (Hu et al., 2017).

1. Paper to read: He et al., 2015 - Deep Residual Learning for Image Recognition (ResNet - identity mapping) https://arxiv.org/abs/1512.03385

2. Related paper: Xie et al., 2016 - Aggregated Residual Transformations for Deep Neural Networks (ResNeXt - cardinality) https://arxiv.org/abs/1611.05431


## Monday 18th February 2019
Paper to read:Goodfellow et al., 2014 - GANs https://arxiv.org/abs/1406.2661
