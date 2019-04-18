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
- **Multi-scale Saliency**: "Deep Visual Attention Prediction", in TIP, 2018. (只是简单的对各层进行deep supervision求saliency)．
- **Fine-grained classification**: "Selective Convolutional Descriptor Aggregation for Fine-Grained Image Retrieval", in TIP, 2017.
- **Dilated Conv and weakly Localization**: Fisher Yu, et al. "Dilated Residual Networks", in CVPR, 2017. (**包括我要用到的category-based confidence maps**).
- **Attention**: "ChestNet: A Deep Neural Network for Classification of Thoracic Diseases on Chest Radiography", (文章很差)．
- **Fine-grained Classification**: "Weakly Supervised Local Attention Network for Fine-Grained Visual Classification", in Arxiv, 2018. (multi attention map分别关注同一个物体的不同部位，并且随机dropout某个attention，保证各个部位都能发挥作用)．（**对我的问题并不适用**).




### Segmentation:
- **MILD-Net**: "MILD-Net : Minimal Information Loss Dilated Network for Gland Instance Segmentation in Colon Histology Images", in Medical Image Analysis, 2018.
- **Dense Unet, 2D & 3D**: "H-DenseUNet: Hybrid Densely Connected UNet for Liver and Tumor Segmentation from CT Volumes", in TMI, 2018.
- **Multi-scale Unet**: "Multiscale Network Followed Network Model for Retinal Vessel Segmentation", in MICCAI, 2018.


### Feature Encoding:
- **Feature encoding based on BOW**: "Deep TEN: Texture Encoding Network", in CVPR, 2017. 
- **Context encoding**: "Context Encoding for Semantic Segmentation", in CVPR, 2018. （和SE模块很相似）
- **CCL**: "Context Contrasted Feature and Gated Multi-scale Aggregation for Scene Segmentation", in CVPR, 2018.
- **DSC**: "Direction-aware Spatial Context Features for Shadow Detection", in CVPR, 2018. (都是充分利用context features，可以和CCL以及MIL结合)．



### Multi-instance Learning:
- **Sparse-based MIL**: "Deep Multi-instance Networks with Sparse Label Assignment for Whole Mammogram Classification", in MICCAI, 2017.
- **MIL for Bodypart Recognition**: "Multi-Instance Deep Learning: Discover Discriminative Local Anatomies for Bodypart Recognition", in TMI, 2016.


### Network Ensemble:
- **Correlation Between Multi-modalities**: "Deep Correlational Learning for Survival Prediction from Multi-modality Data", in MICCAI, 2017. (选取不同模态之间最相关的特征合并做预测)．
- **Knowledge based**: "Transferable Multi-model Ensemble for Benign-Malignant Lung Nodule Classification on Chest CT", in MICCAI, 2017.
- **Multi-view Knowledge-based**: "Knowledge-based Collaborative Deep Learning for Benign-Malignant Lung Nodule Classification on Chest CT", in TMI, 2018.
- **Synergic Learning**: "Skin Lesion Classification in Dermoscopy Images Using Synergic Deep Learning", in MICCAI, 2018.
- **Detection & Fine-grained Classification**: "SFCN-OPI: Detection and Fine-grained Classification of Nuclei Using Sibling FCN with Objectness Prior Interaction", in AAAI, 2018. (Based on probability probability).
- **4-stream Person Re-id**: "A Deep Four-Stream Siamese Convolutional Neural Network with Joint Verification and Identification Loss for Person Re-detection", in WACV, 2018.


### Webly & Semi-supervised:
- **Webly Supervision**: "Webly Supervised Learning for Skin Lesion Classification", in MICCAI, 2018. (利用class transition matrix进行噪声校正)
- **Semi Supervised for loc & cls.**: "Joint Weakly and Semi-Supervised Deep Learning for Localization and Classification of Masses in Breast Ultrasound Images", in TMI, 2018.


### Hierarchical Learning:
- **Hierarchical loss**: "Classification of Breast Cancer Histopathological Images using Convolutional Neural Networks with Hierarchical Loss and Global Pooling", in ICIAR, 2018. (求loss时分错大类得到更大的惩罚)．
- **ISBI一篇文章，忘记名字了**．




