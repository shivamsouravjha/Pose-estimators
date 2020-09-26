# Toward fast and accurate human pose estimation via soft-gated skip connections

# INTRODUCTION
Being one of the most challenging computer vision problems with a multitude of applications, human pose estimation
has been one of the primary research areas that the computer
vision community tried to solve with Deep Learning and
Convolutional Neural Networks (CNNs). Given that the
results produced by existing state-of-the-art methods look
at least impressive both qualitatively and quantitatively, it is
natural to question how much progress can be expected on
this problem over the next years and whether there is room
for further improvement.

# Abstract of Research Paper
This paper is on highly accurate and highly
efficient human pose estimation. Recent works based on Fully
Convolutional Networks (FCNs) have demonstrated excellent
results for this difficult problem. While residual connections
within FCNs have proved to be quintessential for achieving
high accuracy, we re-analyze this design choice in the context of
improving both the accuracy and the efficiency over the state-ofthe-art. In particular, we make the following contributions: (a)
We propose gated skip connections with per-channel learnable
parameters to control the data flow for each channel within the
module within the macro-module. (b) We introduce a hybrid
network that combines the HourGlass and U-Net architectures
which minimizes the number of identity connections within the
network and increases the performance for the same parameter
budget. Our model achieves state-of-the-art results on the MPII
and LSP datasets. In addition, with a reduction of 3× in model
size and complexity, we show no decrease in performance when
compared to the original HourGlass network.
# Skit -Gates 
![img](https://img2020.cnblogs.com/blog/1033571/202009/1033571-20200907190733717-1742101000.png)

# Feature Integration
![imh](https://img2020.cnblogs.com/blog/1033571/202009/1033571-20200907192227591-124027453.png)

# References
https://arxiv.org/pdf/2002.11098v1.pdf

# Research Paper 
@1adrianb is the original author of the paper 
