# Reading-List
Reading list on deep learning

## Reading list before 2019.04.18:

### Loss Functions:
- **CosFace**: "Large Margin Cosine Loss for Deep Face Recognition", in CVPR, 2018.
- **Adaptive margin**: "Rethinking Feature Distribution for Loss Functions in Image Classification", in CVPR, 2018.
- **RIIS-DenseNet**: "RIIS-DenseNet: Rotation-Invariant and Image Similarity Constrained Densely Connected Convolutional Network for Polyp Detection", in MICCAI, 2018. 


### Attention & Saliency:
- **MLF + SLF**: "Deep Attentional Features for Prostate Segmentation in Ultrasound", in MICCAI, 2018.
- **Autofocus**: "Autofocus Layer for Semantic Segmentation", in MICCAI, 2018.
- **Masked salient region for local branch**: "Diagnose like a Radiologist : Attention Guided Convolutional Neural Network for Thorax Disease", arXiv:1801.09927, 2018. （直接根据最后一个block的特征求出heatmap，然后设置阈值得到显著区域的mask，在原图上crop此区域之后作为local branch的输入，最后global和local branch合并）．
- **Multi-scale Attention based on Compatibility Score**: "Learn to Pay Attention", in CVPR, 2018. （利用高层和低层特征的一致性为低层特征的每个位置分配attention，最后各层合并）.
- **Saliency Detection**: "Efficient saliency detection using convolutional neural networks with feature selection", in Information Sciences, 2018.
- **Grad-CAM**: "Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization", in ICCV, 2017.



### Segmentation:
- **CCL**: "Context Contrasted Feature and Gated Multi-scale Aggregation for Scene Segmentation", in CVPR, 2018.
- **MILD-Net**: "MILD-Net : Minimal Information Loss Dilated Network for Gland Instance Segmentation in Colon Histology Images", in Medical Image Analysis, 2018.
- **Dense Unet, 2D & 3D**: "H-DenseUNet: Hybrid Densely Connected UNet for Liver and Tumor Segmentation from CT Volumes", in TMI, 2018.


### Feature Encoding:
- **Feature encoding based on BOW**: "Deep TEN: Texture Encoding Network", in CVPR, 2017. 
- **Context encoding**: "Context Encoding for Semantic Segmentation", in CVPR, 2018. （和SE模块很相似）


### Multi-instance Learning:
- **Sparse-based MIL**: "Deep Multi-instance Networks with Sparse Label Assignment for Whole Mammogram Classification", in MICCAI, 2017.
- **MIL for Bodypart Recognition**: "Multi-Instance Deep Learning: Discover Discriminative Local Anatomies for Bodypart Recognition", in TMI, 2016.


### Weakly Supervised:
- **Dilated Conv and weakly Localization**: Fisher Yu, et al. "Dilated Residual Networks", in CVPR, 2017. (**包括我要用到的category-based confidence maps**).


### Network Ensemble:
- **Correlation Between Multi-modalities**: "Deep Correlational Learning for Survival Prediction from Multi-modality Data", in MICCAI, 2017. (选取不同模态之间最相关的特征合并做预测)．


### Webly & Semi-supervised:
- **Webly Supervision**: Webly Supervised Learning for Skin Lesion Classification, in MICCAI, 2018. (利用class transition matrix进行噪声校正)




