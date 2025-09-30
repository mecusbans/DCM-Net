# DCM-Net: Dual-Encoder CNN-Mamba Network with Cross-Branch Fusion for Robust Medical Image Segmentation

Background: Medical image segmentation is a critical task for the early detection and diagnosis of various conditions, such as skin cancer, polyps, thyroid nodules, and pancreatic tumors. Recently, deep learning architectures have achieved significant success in this field. However, they face a critical trade-off between local feature extraction and global context modeling. Method: To address this limitation, we present DCM-Net, a dual-encoder architecture that integrates pretrained CNN layers with Visual State Space (VSS) blocks through a Cross-Branch Feature Fusion Module (CBFFM). A Decoder Feature Enhancement Module (DFEM) combines depthwise separable convolutions with MLP-based semantic rectification to extract enhanced decoded features and improve the segmentation performance. Additionally, we present a new 2D pancreas and pancreatic tumor dataset (CCH-PCT-CT) collected from Chongqing University Cancer Hospital, comprising 3,547 annotated CT slices, which is used to validate the proposed model. Results: The proposed DCM-Net architecture achieves competitive performance across all datasets investigated in this study. Conclusions: We develop a novel DCM-Net architecture that generates robust features for tumor and organ segmentation in medical images. DCM-Net significantly outperforms all baseline models in segmentation tasks, with higher Dice Similarity Coefficient (DSC) and mean Intersection over Union (mIoU) scores. Its robustness confirms strong potential for clinical use.

#  Existing Medical Image Segmentation Architectures

![ARC](https://github.com/mecusbans/DCM-Net/blob/fceaa5e810ff7dfa56b5397e8083c9a98b8aa469/Others/Figure%202.png)

# DCM-Net Architecture
![DCM-NetDCM-Net](https://github.com/mecusbans/DCM-Net/blob/bf2d75464e29553cef5a46d8fbdc5a85e1c937f8/Others/Figure%203.png)

# Segmentation Results on the Thyriod Nodule Dataset
![Results](https://github.com/S-domain/E-TransConvNet/blob/eb811931c50e8a87f2db7b1297a432959df84a94/Figures/Kidney_US2.png)

# Requirements
Python>= 3.7, Pytorch >= 2.2.1

# Experimental Setting
All experiments were conducted using an NVIDIA GeForce RTX 3090 GPU
