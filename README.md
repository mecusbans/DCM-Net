# DCM-Net: Dual-Encoder CNN-Mamba Network with Cross-Branch Fusion for Robust Medical Image Segmentation

Background: Medical image segmentation is a critical task for the early detection and diagnosis of various conditions, such as skin cancer, polyps, thyroid nodules, and pancreatic tumors. Recently, deep learning architectures have achieved significant success in this field. However, they face a critical trade-off between local feature extraction and global context modeling. Method: To address this limitation, we present DCM-Net, a dual-encoder architecture that integrates pretrained CNN layers with Visual State Space (VSS) blocks through a Cross-Branch Feature Fusion Module (CBFFM). A Decoder Feature Enhancement Module (DFEM) combines depthwise separable convolutions with MLP-based semantic rectification to extract enhanced decoded features and improve the segmentation performance. Additionally, we present a new 2D pancreas and pancreatic tumor dataset (CCH-PCT-CT) collected from Chongqing University Cancer Hospital, comprising 3,547 annotated CT slices, which is used to validate the proposed model. Results: The proposed DCM-Net architecture achieves competitive performance across all datasets investigated in this study. Conclusions: We develop a novel DCM-Net architecture that generates robust features for tumor and organ segmentation in medical images. DCM-Net significantly outperforms all baseline models in segmentation tasks, with higher Dice Similarity Coefficient (DSC) and mean Intersection over Union (mIoU) scores. Its robustness confirms strong potential for clinical use.

#  Existing Medical Image Segmentation Architectures

![ARC](https://github.com/mecusbans/DCM-Net/blob/fceaa5e810ff7dfa56b5397e8083c9a98b8aa469/Others/Figure%202.png)

# DCM-Net Architecture
![DCM-NetDCM-Net](https://github.com/mecusbans/DCM-Net/blob/bf2d75464e29553cef5a46d8fbdc5a85e1c937f8/Others/Figure%203.png)

# Segmentation Results on the Thyriod Nodule Dataset
![Results](https://github.com/mecusbans/DCM-Net/blob/15749ff3f5bfae698a517b58090f51f2d7fc823c/Others/Figure%2011.png)

# Requirements
Python>= 3.7, Pytorch >= 2.2.1

# Experimental Setting
All experiments were conducted using an NVIDIA GeForce RTX 3090 GPU

# CNN, Transformer, and SSM-based Models for Medical Image Segmentation


| 2015  | U-Net    | U-Net: Convolutional Networks for Biomedical Image Segmentation [(Paper)](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28) | [Code](http://lmb.informatik.uni-freiburg.de/people/ronneber/u-net)|
| 2021  | MSU-Net    | MSU-Net: Multi-scale U-Net for 2D medical image segmentation [(Paper)](https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2021.639930/full) | [Code](https://github.com/CN-zdy/MSU_Net)|
| 2024  | MSDANet   | MSDANet: A multi-scale dilation attention network for medical image segmentation [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S1746809423013228) | [Code](https://github.com/1999luan/MSDANet)|
| 2024  | EMCAD    | EMCAD: Efficient Multi-scale Convolutional Attention Decoding for Medical Image Segmentation [(Paper)](https://ieeexplore.ieee.org/document/10656043/) | [Code](https://github.com/SLDGroup/EMCAD)|
| 2023  | H2Former  | H2Former: An Efficient Hierarchical Hybrid Transformer for Medical Image Segmentation [(Paper)](https://ieeexplore.ieee.org/document/10093768/) | [Code](https://github.com/NKUhealong/H2Former)|
| 2023  | MAXFormer | MAXFormer: Enhanced transformer for medical image segmentation with multi-attention and multi-scale features fusion [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S0950705123007372) | [Code](https://github.com/zhiwei-liang/MAXFormer)|
| 2025  | CoAtUNet   | CoAtUNet: A symmetric encoder-decoder with hybrid transformers for semantic segmentation of breast ultrasound images [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S0925231225003327) | [Code](https://github.com/NadeemAlkilani)|
| 2025  | MPBA-Net   | Lesion boundary detection for skin lesion segmentation based on boundary sensing and CNN-transformer fusion networks [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S0933365725001253) | [Code](https://github.com/FengYuchenGuang/MPBA-Net)|
| 2025  | DFIT-Net   | DFIT-Net: A novel dynamic feature integration transformer for automatic segmentation of multi-organ structures in medical imaging [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S0141938225001246) | [Code](https://github.com/AliMedVisionTech/DFIT-Net)|
| 2024  | VM-UNet    | VM-UNet: Vision Mamba UNet for Medical Image Segmentation [(Paper)](https://arxiv.org/abs/2402.02491) | [Code](https://github.com/JCruan519/VM-UNet)|
| 2024  | VM-UNET-V2 | VM-UNET-V2: Rethinking Vision Mamba UNet for Medical Image Segmentation [(Paper)](https://link.springer.com/chapter/10.1007/978-981-97-5128-0_27) | [Code](https://github.com/nobodyplayer1/VM-UNetV2)|
| 2024 | Swin-UMamba | Swin-UMamba: Mamba-Based UNet with ImageNet-Based Pretraining [(Paper)](https://doi.org/10.1007/978-3-031-72114-4_59) | [Code](https://github.com/Jiarun-Liu/Swin-UMamba)|
| 2025  | SK-VM++    | SK-VM++: Mamba assists skip-connections for medical image segmentation [(Paper)](https://doi.org/10.1016/j.bspc.2025.107646) | [Code](https://github.com/wurenkai/SK-VMPlusPlus)|


#   Contact
mecusbans@gmail.com

#   CCH-PCT-CT Dataset
For the CCH-PCT-CT dataset contact Dr. Hui Li (Email: lih@cqu.edu.cn)

#   Acknowledgments
The authors thank the Chongqing University for their support.


# Cite this article
Atabansi, C., Wang, S., Li, H. et al. DCM-Net: dual-encoder CNN-Mamba network with cross-branch fusion for robust medical image segmentation. BMC Med Imaging 25, 395 (2025). https://doi.org/10.1186/s12880-025-01942-4
