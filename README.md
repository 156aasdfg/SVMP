# SVMP
The code for CVPR18 paper: [Video Representation Learning Using Discriminative Pooling](https://arxiv.org/pdf/1803.10628.pdf)
## How to run the Demo
Two-stream ResNet-152 feature for a subset (10 classes) of HMDB-51 split-1 is provided here: [Training Data](https://drive.google.com/open?id=1hLWDpq0v0r29s1Pd_-3xSXtLgVD9tkCT) and [Testing Data](https://drive.google.com/file/d/1wD4gv0or4nxlkm68DNYu9wvAdRAOmD7t/view?usp=sharing). Features from Spatial and Temporal stream are concatenated for each sequence, which becomes a n by d matrix ( n is the number of samples in each sequence, and d is the feature dimension which is 4096 here). 

Download the feature and code first, and run "demo_SVMP.m"
