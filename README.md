# Introduction
I am going to be using the K-Means Unsupervised Clustering Algorithm to segment images of lunch trays. <br/> This [dataset](https://www.kaggle.com/thezaza102/tray-food-segmentation) is meant for supervised learning but I am going to attempt to segment the images without any labels given. <br/>
I am going to cluster pixels based on their spatial and color data only.

# Color Spaces
![RBG & HSV](https://miro.medium.com/max/1700/1*W30TLUP9avQwyyLfwu7WYA.jpeg)
<br/>
<br/>
<br/>
I'm concatenating the RGB and HSV color spaces and clustering pixels based on that data. <br/> `256x416x3` + `256x416x3` = `256x416x6`

# Results
![results](https://raw.githubusercontent.com/vee-upatising/K-Means-Image-Segmentation/master/results.png)

# [View Kaggle Notebook](https://www.kaggle.com/function9/k-means-unsupervised-image-segmentation)
# [View Jupyter Notebook](https://nbviewer.jupyter.org/github/vee-upatising/K-Means-Image-Segmentation/blob/master/Tray.ipynb)

