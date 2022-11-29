
# ISBI 2012 EM Segmentation Challenge 

Research in Deep Learning is advancing at an incredible pace with the availability of data and computation power. Here, I discuss my experiments relating to U-Net, a Convolutional Neural Network which is well known and was proposed to solve the problems of biomedical image segmentation.
I worked on reproducing results achieved by the authors in the [original U-net paper](https://arxiv.org/abs/1505.04597). 
The experiment was done to provide a solution in the [ISBI Cell Segmentation challenge 2012](https://imagej.net/events/isbi-2012-segmentation-challenge#test-data). I achieved a Rand thin score of 0.9658 and Information thin score of 0.9831.

### Authors of the original paper
The authors of ‘U-Net: Convolutional Networks for Biomedical Image Segmentation’ are Olaf Ronneberger, Philipp Fischer, and Thomas Brox. The research group is from the Computer Science Department, and BIOSS Centre for Biological Signalling Studies, University of Freiburg, Germany.
U-Net solves the problem of semantic segmentation. Semantic segmentation is the problem of classification of every pixel of an image.

### Architecture of the Network

The U-Net architecture consists of three paths: Contracting path, Expanding path, and Concatenation path.
The new architecture proposed by the authors to solve semantic segmentation is more robust compared to previous models. The most significant advantage is that the network requires a lesser number of inputs compared to the previous state-of-the-art convolutional neural networks. An added benefit is that the model is computationally efficient.

![U-net Architecture image](https://github.com/pranjal-dave/ISBI2012-EM-Segmentation-Challenge/blob/main/U-net.png)

Following are the results of the resulting model.

![Results GIF](https://github.com/pranjal-dave/ISBI2012-EM-Segmentation-Challenge/blob/main/Challenge-ISBI-2012-Animation-Input-Labels.gif)
