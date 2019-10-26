# Deep Learning with PyTorch  

## Style Transfer with Deep Neural Networks  
In this notebook, we’ll recreate a style transfer method that is outlined in the paper, [Image Style Transfer Using Convolutional Neural Networks, by Gatys in PyTorch](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)   

In this paper, style transfer uses the features found in the 19-layer VGG Network, which is comprised of a series of convolutional and pooling layers, and a few fully-connected layers. In the image below, the convolutional layers are named by stack and their order in the stack. Conv_1_1 is the first convolutional layer that an image is passed through, in the first stack. Conv_2_1 is the first convolutional layer in the second stack. The deepest convolutional layer in the network is conv_5_4.  

 It was a part of Deep learning Nanodegree by [Udacity](https://udacity.com)  

## Setup  
 1. Clone this repo:  
```  
git clone https://github.com/keshav787/cnn-style-transfer.git  
```  
 2. Install all the dependencies    
 3. Follow Instructions in [cnn_Style_Transfer.ipynb](https://github.com/keshav787/cnn-style-transfer/blob/master/cnn_Style_Transfer.ipynb)  
