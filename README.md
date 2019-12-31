# K-Means-Image-Segmentation
Segmenting Images of Food using K-Means Unsupervised Clustering Algorithm

# Introduction
I am going to be using the K-Means Unsupervised Clustering Algorithm to segment images of lunch trays. <br/> This dataset is meant for supervised learning but I am going to attempt to segment the images without any labels given. <br/>
I am going to cluster pixels based on their spatial and color data only.

# Color Spaces
![RBG & HSV](https://miro.medium.com/max/1700/1*W30TLUP9avQwyyLfwu7WYA.jpeg)
<br/>
<br/>
<br/>
I'm concatenating the RGB and HSV color spaces. `256x416x3` + `256x416x3` = `256x416x6`
