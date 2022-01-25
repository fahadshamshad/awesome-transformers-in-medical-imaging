# <p align=center>`Awesome Transformers in Medical Imaging`</p>
# <p align=center> Repo suplements our [[Survey on Transformers in Medical Imaging](https://arxiv.org/abs/2201.09873)] </p>
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Transformers resources in medical imaging, inspired by the other awesome-initiatives. 
<!--This repository is also a supplement for our survey paper **Transformer in Medical Imaging: A Survey**.-->

If you find some overlooked papers, please open issue or contact at fahad.shamshad3@gmail.com.

![](TMIsurvey_gif.gif)

## Overview
- [Survey papers](#survey)
- [Medical Image Segmentation](#segmentation)
- [Medical Image Classification](#classification)
- [Medical Image Reconstruction](#reconstruction)
- [Medical Image Registration](#registration)
- [Medical Image Synthesis](#synthesis)
- [Medical Image Detection](#detection)
- [Clinical Report Generation](#clinical-report-generation)
- [Others](#others)

# Survey

**Transformer in Medical Imaging: A survey.** [25th Jan., 2022] <br>
*Fahad Shamshad, Salman Khan, Syed Waqas Zamir, Muhammad Haris Khan, Munawar Hayat, Fahad Shahbaz Khan, and Huazhu Fu.*<br>
[[PDF](https://arxiv.org/abs/2201.09873)] 

**Abstract:** Following unprecedented success on the natural language tasks, Transformers have been successfully applied to several computer vision problems, achieving state-of-the-art results and prompting researchers to reconsider the supremacy of convolutional neural networks (CNNs) as {de facto} operators.
Capitalizing on these advances in computer vision, the medical imaging field has also witnessed growing interest for Transformers that can capture global context compared to CNNs with local receptive fields. Inspired from this transition, in this survey, we attempt to provide a comprehensive review of the applications of Transformers in medical imaging covering various aspects, ranging from recently proposed architectural designs to unsolved issues. Specifically, we survey the use of Transformers in medical image segmentation, detection, classification, reconstruction, synthesis, registration, clinical report generation, and other tasks. In particular, for each of these applications, we develop taxonomy, identify application-specific challenges as well as provide insights to solve them, and highlight recent trends. Further, we provide a critical discussion of the field's current state as a whole, including the identification of key challenges, open problems, and outlining promising future directions. We hope this survey will ignite further interest in the community and provide researchers with an up-to-date reference regarding applications of Transformer models in medical imaging. Finally, to cope with the rapid development in this field, we intend to regularly update the relevant latest papers and their open-source implementations on this page.

**Application of Transformer in Medical Image Segmentation.** [25th Oct., 2021].<br>
*Wenyin Zhang, Weijie Hao, Yuan Qi and Yong Wu.*<br>
 [[PDF](https://biomedgrid.com/pdf/AJBSR.MS.ID.002014.pdf)] 



# Segmentation

**Attention-Based Transformers for Instance Segmentation of Cells in Microstructures.** [20th Nov., 2020].<br>
*Tim Prangemeier, Christoph Reich, Heinz Koeppl.*<br>
 [[PDF](https://arxiv.org/abs/2011.09763)] 
 
 **TransUNet: Transformers Make Strong Encoders for Medical Image Segmentation.** [8th Feb., 2021].<br>
*Jieneng Chen, Yongyi Lu, Qihang Yu, Xiangde Luo, Ehsan Adeli, Yan Wang, Le Lu, Alan L. Yuille, Yuyin Zhou.*<br>
 [[PDF](https://arxiv.org/abs/2102.04306)] [[Github](https://github.com/Beckschen/TransUNet)]
 
  **TransFuse: Fusing Transformers and CNNs for Medical Image Segmentation.** [16th Feb., 2021] [⚡MICCAI, 2021].<br>
*Yundong Zhang, Huiye Liu, Qiang Hu.*<br>
 [[PDF](https://arxiv.org/abs/2102.08005)] [[Github](https://github.com/Rayicer/TransFuse)]
 
  **Convolution-Free Medical Image Segmentation using Transformers.** [26th Feb., 2021] [⚡MICCAI, 2021].<br>
*Davood Karimi, Serge Vasylechko, Ali Gholipour.*<br>
 [[PDF](https://arxiv.org/abs/2102.13645)]
 
  **CoTr: Efficiently Bridging CNN and Transformer for 3D Medical Image Segmentation.** [4th March, 2021] [⚡MICCAI, 2021].<br>
*Yutong Xie, Jianpeng Zhang, Chunhua Shen, Yong Xia.*<br>
 [[PDF](https://arxiv.org/abs/2103.03024)] [[Github](https://github.com/YtongXie/CoTr)]
 
  **SpecTr: Spectral Transformer for Hyperspectral Pathology Image Segmentation.** [5th March, 2021].<br>
*Boxiang Yun, Yan Wang, Jieneng Chen, Huiyu Wang, Wei Shen, Qingli Li.*<br>
 [[PDF](https://arxiv.org/abs/2103.03604)] [[Github](https://github.com/hfut-xc-yun/SpecTr)]
 
  **TransBTS: Multimodal Brain Tumor Segmentation Using Transformer.** [7th March, 2021] [⚡MICCAI, 2021].<br>
*Wenxuan Wang, Chen Chen, Meng Ding, Jiangyun Li, Hong Yu, Sen Zha.*<br>
 [[PDF](https://arxiv.org/abs/2103.04430)] [[Github](https://github.com/Wenxuan-1119/TransBTS)]
 
  **U-Net Transformer: Self and Cross Attention for Medical Image Segmentation.** [10th March, 2021].<br>
*Olivier Petit, Nicolas Thome, Clément Rambour, Luc Soler.*<br>
 [[PDF](https://arxiv.org/abs/2103.06104)] [[Github](https://github.com/HXLH50K/U-Net-Transformer)]
 
   **UNETR: Transformers for 3D Medical Image Segmentation .** [18th March, 2021].<br>
*Ali Hatamizadeh, Yucheng Tang, Vishwesh Nath, Dong Yang, Andriy Myronenko, Bennett Landman, Holger Roth, Daguang Xu.*<br>
 [[PDF](https://arxiv.org/abs/2103.10504)] [[Github](https://github.com/Project-MONAI/research-contributions/tree/master/UNETR/BTCV)]
 
   **Medical Transformer: Universal Brain Encoder for 3D MRI Analysis.** [28th April, 2021].<br>
*Eunji Jun, Seungwoo Jeong, Da-Woon Heo, Heung-Il Suk.*<br>
 [[PDF](https://arxiv.org/abs/2104.13633)]
 
   **Pyramid Medical Transformer for Medical Image Segmentation .** [29th April, 2021].<br>
*Zhuangzhuang Zhang, Baozhou Sun, Weixiong Zhang.*<br>
 [[PDF](https://arxiv.org/abs/2104.14702)]
 
   **GasHis-Transformer: A Multi-scale Visual Transformer Approach for Gastric Histopathology Image Classification.** [29th April, 2021].<br>
*Haoyuan Chen, Chen Li, Xiaoyan Li, Ge Wang, Weiming Hu, Yixin Li, Wanli Liu, Changhao Sun, Yudong Yao, Yueyang Teng, Marcin Grzegorzek.*<br>
 [[PDF](https://arxiv.org/abs/2104.14528)]
 
   **Swin-Unet: Unet-like Pure Transformer for Medical Image Segmentationr.** [12th May, 2021].<br>
*Hu Cao, Yueyue Wang, Joy Chen, Dongsheng Jiang, Xiaopeng Zhang, Qi Tian, Manning Wang.*<br>
 [[PDF](https://arxiv.org/abs/2105.05537)]
 
   **Medical Image Segmentation Using Squeeze-and-Expansion Transformers.** [20th May, 2021] [⚡IJCAI, 2021].<br>
*Shaohua Li, Xiuchao Sui, Xiangde Luo, Xinxing Xu, Yong Liu, Rick Goh.*<br>
 [[PDF](https://arxiv.org/abs/2105.09511)] [[Github](https://github.com/askerlee/segtran)]
 
   **A Multi-Branch Hybrid Transformer Network for Corneal Endothelial Cell Segmentation.** [21st May, 2021] [⚡MICCAI, 2021].<br>
*Yinglin Zhang, Risa Higashita, Huazhu Fu, Yanwu Xu, Yang Zhang, Haofeng Liu, Jian Zhang, Jiang Liu.*<br>
 [[PDF](https://arxiv.org/abs/2106.07557)] 
 
   **DS-TransUNet:Dual Swin Transformer U-Net for Medical Image Segmentation.** [12 June, 2021].<br>
*Ailiang Lin, Bingzhi Chen, Jiayu Xu, Zheng Zhang, Guangming Lu.*<br>
 [[PDF](https://arxiv.org/abs/2106.06716)] 
 
   **More than Encoder: Introducing Transformer Decoder to Upsample.** [20th June, 2021].<br>
*Yijiang Li, Wentian Cai, Ying Gao, Xiping Hu.*<br>
 [[PDF](https://arxiv.org/abs/2106.10637)]
 
   **Multi-Compound Transformer for Accurate Biomedical Image Segmentation.** [28th June, 2021] [⚡MICCAI, 2021].<br>
*Yuanfeng Ji, Ruimao Zhang, Huijie Wang, Zhen Li, Lingyun Wu, Shaoting Zhang, Ping Luo.*<br>
 [[PDF](https://arxiv.org/abs/2106.14385)] [[Github](https://github.com/JiYuanFeng/MCTrans)]
 
   **UTNet: A Hybrid Transformer Architecture for Medical Image Segmentation.** [2nd July, 2021] [⚡MICCAI, 2021].<br>
*Yunhe Gao, Mu Zhou, Dimitris Metaxas.*<br>
 [[PDF](https://arxiv.org/abs/2107.04805)] [[Github](https://github.com/askerlee/segtran)]
 
   **Few-Shot Domain Adaptation with Polymorphic Transformers.** [10th July, 2021] [⚡MICCAI, 2021].<br>
*Shaohua Li, Xiuchao Sui, Jie Fu, Huazhu Fu, Xiangde Luo, Yangqin Feng, Xinxing Xu, Yong Liu, Daniel Ting, Rick Siow Mong Goh.*<br>
 [[PDF](https://arxiv.org/abs/2103.04430)] [[Github](https://github.com/Wenxuan-1119/TransBTS)]
 
   **TransClaw U-Net: Claw U-Net with Transformers for Medical Image Segmentation.** [12th July, 2021].<br>
*Yao Chang, Hu Menghan, Zhai Guangtao, Zhang Xiao-Ping.*<br>
 [[PDF](https://arxiv.org/abs/2107.05188)]
 
   **TransAttUnet: Multi-level Attention-guided U-Net with Transformer for Medical Image Segmentation.** [12th July, 2021].<br>
*Bingzhi Chen, Yishu Liu, Zheng Zhang, Guangming Lu, David Zhang.*<br>
 [[PDF](https://arxiv.org/abs/2107.05274)]
 
   **LeViT-UNet: Make Faster Encoders with Transformer for Medical Image Segmentation.** [19th July, 2021].<br>
*Guoping Xu, Xingrong Wu, Xuan Zhang, Xinwei He.*<br>
 [[PDF](https://arxiv.org/abs/2107.08623)] [[Github](https://github.com/apple1986/LeViT_UNet)]
 
   **Polyp-PVT: Polyp Segmentation with Pyramid Vision Transformers.** [16th August, 2021].<br>
*Bo Dong, Wenhai Wang, Deng-Ping Fan, Jinpeng Li, Huazhu Fu, Ling Shao.*<br>
 [[PDF](https://arxiv.org/abs/2108.06932)] [[Github](https://github.com/DengPingFan/Polyp-PVT)]
 
   **Evaluating Transformer-based Semantic Segmentation Networks for Pathological Image Segmentation.** [26th August, 2021].<br>
*Cam Nguyen, Zuhayr Asad, Yuankai Huo.*<br>
 [[PDF](https://arxiv.org/abs/2108.11993)]
 
   **Automated Kidney Tumor Segmentation with Convolution and Transformer Network.** [30th August, 2021] [👍 MICCAI KiTS Challenge, 2021].<br>
*Zhiqiang Shen, Zhiqiang_Shen, Hua Yang, Zhen Zhang, Shaohua Zheng.*<br>
 [[PDF](https://openreview.net/forum?id=voteINyy36u)]
 
   **nnFormer: Interleaved Transformer for Volumetric Segmentation.** [7th Sep., 2021].<br>
*Hong-Yu Zhou, Jiansen Guo, Yinghao Zhang, Lequan Yu, Liansheng Wang, Yizhou Yu.*<br>
 [[PDF](https://arxiv.org/abs/2109.03201)] [[Github](https://github.com/282857341/nnformer)]
 
   **UCTransNet: Rethinking the Skip Connections in U-Net from a Channel-wise Perspective with Transformer.** [9th, Sep.,].<br>
*Haonan Wang, Peng Cao, Jiaqi Wang, Osmar R.Zaiane.*<br>
 [[PDF](https://arxiv.org/abs/2109.04335)] [[Github](https://github.com/mcgregorwwww/uctransnet)]
 
   **MISSFormer: An Effective Medical Image Segmentation Transformer.** [15th, Sep. 2021].<br>
*Xiaohong Huang, Zhifang Deng, Dandan Li, Xueguang Yuan.*<br>
 [[PDF](https://arxiv.org/abs/2109.07162)]
 
   **TransBridge: A Lightweight Transformer for Left Ventricle Segmentation in Echocardiography.** [21st Sep., 2021] [👍 MICCAI Simplifying Medical Ultrasound Workshop, 2021].<br>
*Kaizhong DengYanda MengDongxu GaoJoshua BridgeYaochun ShenGregory LipYitian ZhaoYalin Zheng.*<br>
 [[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87583-1_7)] 
 
   **BiTr-Unet: a CNN-Transformer Combined Network for MRI Brain Tumor Segmentation.** [25th Sep., 2021] [👍 MICCAI BraTS DREAM Challenge ShuLab, 2021].<br>
*Qiran Jia, Hai Shu.*<br>
 [[PDF](https://arxiv.org/abs/2109.12271)]
 
   **GT U-Net: A U-Net Like Group Transformer Network for Tooth Root Segmentation .** [30th Sep., 2021] [👍 MICCAI MLMI Workshop, 2021].<br>
*Yunxiang Li, Shuai Wang, Jun Wang, Guodong Zeng, Wenjun Liu, Qianni Zhang, Qun Jin, Yaqi Wang.*<br>
 [[PDF](https://arxiv.org/abs/2109.14813)] [[Github](https://github.com/kent0n-li/gt-u-net)]
 
   **Transformer Assisted Convolutional Network for Cell Instance Segmentation.** [5th Oct., 2021] [👍 ISBI Workshop, 2021].<br>
*Deepanshu Pandey, Pradyumna Gupta, Sumit Bhattacharya, Aman Sinha, Rohit Agarwal.*<br>
 [[PDF](https://arxiv.org/abs/2110.02270)] [[Github](https://github.com/dsciitism/segpc-2021)]
 
   **Boundary-aware Transformers for Skin Lesion Segmentation.** [8th Oct., 2021] [⚡MICCAI, 2021].<br>
*Jiacheng Wang, Lan Wei, Liansheng Wang, Qichao Zhou, Lei Zhu, Jing Qin.*<br>
 [[PDF](https://arxiv.org/abs/2110.03864)] [[Github](https://github.com/jcwang123/BA-Transformer)]
 
   **Spine-transformers: Vertebra labeling and segmentation in arbitrary field-of-view spine CTs via 3D transformers.** [10th Oct., 2021] [⚡MIA, 2021].<br>
*Rong Taoa, Wenyong Liub, Guoyan Zheng.*<br>
 [[PDF](https://www.sciencedirect.com/science/article/pii/S1361841521003030)]
 
   **AFTer-UNet: Axial Fusion Transformer UNet for Medical Image Segmentation.** [20th Oct., 2021].<br>
*Xiangyi Yan, Hao Tang, Shanlin Sun, Haoyu Ma, Deying Kong, Xiaohui Xie.*<br>
 [[PDF](https://arxiv.org/abs/2110.10403)]
 
   **Hepatic vessel segmentation based on 3D swin-transformer with inductive biased multi-head self-attention.** [5th Nov., 2021].<br>
*Mian Wu, Yinling Qian, Xiangyun Liao, Qiong Wang, Pheng-Ann Heng.*<br>
 [[PDF](https://arxiv.org/abs/2111.03368)] 
 
   **Mixed Transformer U-Net For Medical Image Segmentation.** [8th, Nov. 2021].<br>
*Hongyi Wang, Shiao Xie, Lanfen Lin, Yutaro Iwamoto, Xian-Hua Han, Yen-Wei Chen, Ruofeng Tong.*<br>
 [[PDF](https://arxiv.org/abs/2111.04734)] [[Github](https://github.com/dootmaan/mt-unet)]
 
   **T-AutoML: Automated Machine Learning for Lesion Segmentation using Transformers in 3D Medical Imaging.** [15th Nov., 2021] [⚡ICCV, 2021].<br>
*Dong Yang, Andriy Myronenko, Xiaosong Wang, Ziyue Xu, Holger R. Roth, Daguang Xu.*<br>
 [[PDF](https://arxiv.org/abs/2111.07535)]
 
   **A Volumetric Transformer for Accurate 3D Tumor Segmentation.** [26th Nov., 2021].<br>
*Himashi Peiris, Munawar Hayat, Zhaolin Chen, Gary Egan, Mehrtash Harandi.*<br>
 [[PDF](https://arxiv.org/abs/2111.13300)] [[Github](https://github.com/himashi92/vt-unet)]
 
   **Exploiting full Resolution Feature Context for Liver Tumor and Vessel Segmentation via Fusion Encoder: Application to Liver Tumor and Vessel 3D reconstruction.** [26th Nov., 2021].<br>
*Xiangyu Meng, Xudong Zhang, Gan Wang, Ying Zhang, Xin Shi, Huanhuan Dai, Zixuan Wang, Xun Wang.*<br>
 [[PDF](https://arxiv.org/abs/2111.13299)]
 
   **Self-Supervised Pre-Training of Swin Transformers for 3D Medical Image Analysis.** [29th Nov., 2021].<br>
*Yucheng Tang, Dong Yang, Wenqi Li, Holger Roth, Bennett Landman, Daguang Xu, Vishwesh Nath, Ali Hatamizadeh.*<br>
 [[PDF](https://arxiv.org/abs/2111.14791)] [[Github](https://github.com/Project-MONAI/research-contributions/tree/master/SwinUNETR)]
 
   **MT-TransUNet: Mediating Multi-Task Tokens in Transformers for Skin Lesion Segmentation and Classification.** [3rd Dec., 2021].<br>
*Jingye Chen, Jieneng Chen, Zongwei Zhou, Bin Li, Alan Yuille, Yongyi Lu.*<br>
 [[PDF](https://arxiv.org/abs/2112.01767)] [[Github](https://github.com/jingyechen/mt-transunet)]
 
   **FAT-Net: Feature Adaptive Transformers for Automated Skin Lesion Segmentation.** [4th Dec., 2021] [⚡MIA, 2021].<br>
*Huisi Wu, Shihuai Chen, Guilian Chen, Wei Wang, Baiying Lei, Zhenkun Wen.*<br>
 [[PDF](https://www.sciencedirect.com/science/article/pii/S1361841521003728)] [[Github](https://github.com/SZUcsh/FAT-Net)]
 
   **Semi-Supervised Medical Image Segmentation via Cross Teaching between CNN and Transformer.** [9th Dec., 2021].<br>
*Xiangde Luo, Minhao Hu, Tao Song, Guotai Wang, Shaoting Zhang.*<br>
 [[PDF](https://arxiv.org/abs/2112.04894v1)] [[Github](https://github.com/HiLab-git/SSL4MIS)]
 
   **D-Former: A U-shaped Dilated Transformer for 3D Medical Image Segmentation.** [3rd Jan., 2022].<br>
*Yixuan Wu, Kuanlun Liao, Jintai Chen, Jinhong Wang, Danny Z. Chen, Honghao Gao, Jian Wu.*<br>
 [[PDF](https://arxiv.org/abs/2201.00462)]
 
   **Swin UNETR: Swin Transformers for Semantic Segmentation of Brain Tumors in MRI Images.** [4th Jan., 2022].<br>
*Ali Hatamizadeh, Vishwesh Nath, Yucheng Tang, Dong Yang, Holger Roth, Daguang Xu.*<br>
 [[PDF](https://arxiv.org/abs/2201.01266)] [[Github](https://github.com/Project-MONAI/research-contributions/tree/master/SwinUNETR/BRATS21)]
 

 
 
# Classification

  **TransMed: Transformers Advance Multi-modal Medical Image Classification.** [10th March, 2021].<br>
*Yin Dai, Yifan Gao.*<br>
 [[PDF](https://arxiv.org/abs/2103.05940)]
 
   **Medical Transformer: Universal Brain Encoder for 3D MRI Analysis.** [28th April, 2021].<br>
*Eunji Jun, Seungwoo Jeong, Da-Woon Heo, Heung-Il Suk.*<br>
 [[PDF](https://arxiv.org/abs/2104.13633)] 
 
   **TransMIL: Transformer based Correlated Multiple Instance Learning for Whole Slide Image Classification.** [2nd June, 2021] [⚡NeurIPS, 2021].<br>
*Zhuchen Shao, Hao Bian, Yang Chen, Yifeng Wang, Jian Zhang, Xiangyang Ji, Yongbing Zhang.*<br>
 [[PDF](https://arxiv.org/abs/2106.00908)] [[Github](https://github.com/szc19990412/TransMIL)]
 
   **Vision Transformer-based recognition of diabetic retinopathy grade.** [15 July, 2021] [⚡CVPR, 2021].<br>
*Rui Sun, Yihao Li, Tianzhu Zhang, Zhendong Mao, Feng Wu, Yongdong Zhang.*<br>
 [[PDF](https://openaccess.thecvf.com/content/CVPR2021/html/Sun_Lesion-Aware_Transformers_for_Diabetic_Retinopathy_Grading_CVPR_2021_paper.html)] 
 
   **Is it Time to Replace CNNs with Transformers for Medical Images?** [20th Aug., 2021] [👍ICCV Workshop of Automated Medical Diagnosis, 2021].<br>
*Christos Matsoukas, Johan Fredin Haslum, Magnus Söderberg, Kevin Smith.*<br>
 [[PDF](https://arxiv.org/abs/2108.09038)] [[Github](https://github.com/chrismats/medical_transformers)]
 
   **Gene Transformer: Transformers for the Gene Expression-based Classification of Lung Cancer Subtypes** [26th Aug., 2021].<br>
*Anwar Khan, Boreom Lee.*<br>
 [[PDF](https://arxiv.org/abs/2108.11833)]
 
   **A transformer-based deep learning approach for classifying brain metastases into primary organ sites using clinical whole brain MRI.** [7th Oct., 2021].<br>
*Qing Lyu, Sanjeev V. Namjoshi, Emory McTyre, Umit Topaloglu, Richard Barcus, Michael D. Chan, Christina K. Cramer, Waldemar Debinski, Metin N. Gurcan, Glenn J. Lesser, Hui-Kuan Lin, Reginald F. Munden, Boris C. Pasche, Kiran Kumar Solingapuram Sai, Roy E. Strowd, Stephen B. Tatter, Kounosuke Watabe, Wei Zhang, Ge Wang, Christopher T. Whitlow.*<br>
 [[PDF](https://arxiv.org/abs/2110.03588)] 
 
   **CAE-Transformer: Transformer-based Model to Predict Invasiveness of Lung Adenocarcinoma Subsolid Nodules from Non-thin Section 3D CT Scans.** [17th Oct., 2021].<br>
*Shahin Heidarian, Parnian Afshar, Anastasia Oikonomou, Konstantinos N. Plataniotis, Arash Mohammadi.*<br>
 [[PDF](https://arxiv.org/abs/2110.08721)] 
 
   **Vision Transformer-based recognition of diabetic retinopathy grade.** [25th Oct., 2021].<br>
*Jianfang Wu, Ruo Hu, Zhenghong Xiao, Jiaxu Chen, Jingwei Liu.*<br>
 [[PDF](https://pubmed.ncbi.nlm.nih.gov/34693536/)] 
 
   **VISION TRANSFORMERS FOR CLASSIFICATION OF BREAST ULTRASOUND IMAGES.** [27th Oct., 2021].<br>
*Behnaz Gheflati, Hassan Rivaz.*<br>
 [[PDF](https://arxiv.org/abs/2110.14731)]
 
 
## Classification COVID19 (Separate section due to its current significance)

  **Vision Transformer for COVID-19 CXR Diagnosis using Chest X-ray Feature Corpus.** [12th March, 2021].<br>
*Sangjoon Park, Gwanghyun Kim, Yujin Oh, Joon Beom Seo, Sang Min Lee, Jin Hwan Kim, Sungjun Moon, Jae-Kwang Lim, Jong Chul Ye.*<br>
 [[PDF](https://arxiv.org/abs/2103.07055)]
 
   **Vision Transformer using Low-level Chest X-ray Feature Corpus for COVID-19 Diagnosis and Severity Quantification.** [15th April, 2021].<br>
*Sangjoon Park, Gwanghyun Kim, Yujin Oh, Joon Beom Seo, Sang Min Lee, Jin Hwan Kim, Sungjun Moon, Jae-Kwang Lim, Jong Chul Ye.*<br>
 [[PDF](https://arxiv.org/abs/2104.07235)]
 
   **POCFormer: A Lightweight Transformer Architecture for Detection of COVID-19 Using Point of Care Ultrasound.** [15th May, 2021].<br>
*Shehan Perera, Srikar Adhikari, Alper Yilmaz.*<br>
 [[PDF](https://arxiv.org/abs/2105.09913)] 
 
   **Automatic Diagnosis of COVID-19 Using a tailored Transformer-Like Network.** [20th May, 2021].<br>
*Chengeng Liu1, Qingshan Yin.*<br>
 [[PDF](https://iopscience.iop.org/article/10.1088/1742-6596/2010/1/012175)]
 
   **COVID-VIT: Classification of COVID-19 from CT chest images based on vision transformer models.** [4th July, 2021].<br>
*Xiaohong Gao, Yu Qian, Alice Gao.*<br>
 [[PDF](https://arxiv.org/abs/2107.01682)] [[Github](https://github.com/xiaohong1/COVID-ViT)]
 
   **xViTCOS: Explainable Vision Transformer Based COVID-19 Screening Using Radiography .** [6th July, 2021].<br>
*Arnab Kumar MondalArnab Kumar Mondal, Arnab Bhattacharjee, Parag Singla, Prathosh AP.*<br>
 [[PDF](https://www.techrxiv.org/articles/preprint/xViTCOS_Explainable_Vision_Transformer_Based_COVID-19_Screening_Using_Radiography/14912367/1)]
 
   **Visual Transformer with Statistical Test for COVID-19 Classification.** [12th July, 2021] [👍ICCV MIA Workshop, 2021].<br>
*Chih-Chung Hsu, Guan-Lin Chen, Mei-Hsuan Wu.*<br>
 [[PDF](https://arxiv.org/abs/2107.05334)] 
 
   **MIA-COV19D: A transformer-based framework for COVID19 classification in chest CTs.** [15th July, 2021] [👍ICCV MIA Workshop, 2021].<br>
*Lei Zhang, Yan Wen.*<br>
 [[PDF](https://www.researchgate.net/publication/353105641_MIA-COV19D_A_transformer-based_framework_for_COVID19_classification_in_chest_CTs)]
 
   **COViT-GAN: Vision Transformer forCOVID-19 Detection in CT images.** [10th August, 2021].<br>
*Ara Abigail E. Ambita, Eujene Nikka V. Boquio, Prospero C. Naval Jr.*<br>
 [[PDF](https://www.springerprofessional.de/en/covit-gan-vision-transformer-forcovid-19-detection-in-ct-scan-im/19652482)] 
 
   **COVID-Transformer: Interpretable COVID-19 Detection Using Vision Transformer for Healthcare.** [23rd Sep., 2021].<br>
*Debaditya Shome, T Kar, Sachi Nandan Mohanty, Prayag Tiwari, Khan Muhammad, Abdullah AlTameem, Yazhou Zhang, Abdul Khader Jilani Saudagar.*<br>
 [[PDF](https://pubmed.ncbi.nlm.nih.gov/34769600/)]
 
   **Vision Transformer based COVID-19 Detection using Chest X-rays.** [9th Oct., 2021].<br>
*Koushik Sivarama Krishnan, Karthik Sivarama Krishnan.*<br>
 [[PDF](https://arxiv.org/abs/2110.04458)]  
 
   **COVID-19 Detection in Chest X-ray Images Using Swin-Transformer and Transformer in Transformer.** [16th Oct., 2021].<br>
*Juntao Jiang, Shuyi Lin.*<br>
 [[PDF](https://arxiv.org/abs/2110.08427)] 
 
   **Federated Split Vision Transformer for COVID-19 CXR Diagnosis using Task-Agnostic Training.** [2nd Nov., 2021] [⚡NeurIPS, 2021].<br>
*Sangjoon Park, Gwanghyun Kim, Jeongsol Kim, Boah Kim, Jong Chul Ye.*<br>
 [[PDF](https://arxiv.org/abs/2111.01338)]
 
   **Multi-task vision transformer using low-level chest X-ray feature corpus for COVID-19 diagnosis and severity quantification.** [4th Nov., 2021] [⚡MIA, 2021].<br>
*Sangjoon Parka, Gwanghyun Kima,Yujin Oha, Joon Beom Seo, Sang Min Lee, Jin Hwan Kimc,Sungjun Moond, Jae-Kwang Lime, Jong Chul Ye.*<br>
 [[PDF](https://www.sciencedirect.com/science/article/pii/S1361841521003443)]
 

# Reconstruction

   **TransCT: Dual-path Transformer for Low Dose Computed Tomography.** [28th Feb., 2021] [⚡MICCAI, 2021].<br>
*Zhicheng Zhang, Lequan Yu, Xiaokun Liang, Wei Zhao, Lei Xing.*<br>
 [[PDF](https://arxiv.org/abs/2103.00634)] [[Github](https://github.com/zzc623/TransCT)]
 
   **Unsupervised MRI Reconstruction via Zero-Shot Learned Adversarial Transformers.** [15th May, 2021].<br>
*Yilmaz Korkmaz, Salman UH Dar, Mahmut Yurt, Muzaffer Özbey, Tolga Çukur.*<br>
 [[PDF](https://arxiv.org/abs/2103.04430)] [[Github](https://github.com/Wenxuan-1119/TransBTS)]
 
   **TED-net: Convolution-free T2T Vision Transformer-based Encoder-decoder Dilation network for Low-dose CT Denoising.** [8th June, 2021].<br>
*Dayang Wang, Zhan Wu, Hengyong Yu.*<br>
 [[PDF](https://arxiv.org/abs/2106.04650)]
 
   **Task Transformer Network for Joint MRI Reconstruction and Super-Resolution.** [12th June, 2021] [⚡MICCAI, 2021].<br>
*Chun-Mei Feng, Yunlu Yan, Huazhu Fu, Li Chen, Yong Xu.*<br>
 [[PDF](https://arxiv.org/abs/2106.06742)] [[Github](https://github.com/chunmeifeng/T2Net)]
 
   **Accelerated Multi-Modal MR Imaging with Transformers.** [27th June, 2021].<br>
*Chun-Mei Feng, Yunlu Yan, Geng Chen, Huazhu Fu, Yong Xu, Ling Shao.*<br>
 [[PDF](https://arxiv.org/abs/2106.14248)] [[Github](https://github.com/chunmeifeng/MTrans)]
 
   **E-DSSR: Efficient Dynamic Surgical Scene Reconstruction with Transformer-based Stereoscopic Depth Perception.** [1st July, 2021] [⚡MICCAI, 2021].<br>
*Yonghao Long, Zhaoshuo Li, Chi Hang Yee, Chi Fai Ng, Russell H. Taylor, Mathias Unberath, Qi Dou.*<br>
 [[PDF](https://arxiv.org/abs/2107.00229)]
 
   **Eformer: Edge Enhancement based Transformer for Medical Image Denoising.** [16th Sep., 2021] [👍ICCV Workshop, 2021].<br>
*Achleshwar Luthra, Harsh Sulakhe, Tanish Mittal, Abhishek Iyer, Santosh Yadav.*<br>
 [[PDF](https://arxiv.org/abs/2109.08044)] 
 
   **Transformer-Unet: Raw Image Processing with Unet.** [17th Sep., 2021].<br>
*Youyang Sha, Yonghong Zhang, Xuquan Ji, Lei Hu.*<br>
 [[PDF](https://arxiv.org/abs/2109.08417)]
 
   **Deep MRI Reconstruction with Generative Vision Transformers .** [25th Sep., 2021].<br>
*Yilmaz KorkmazMahmut Yurt, Salman Ul Hassan Dar, Muzaffer Özbey, Tolga Cukur.*<br>
 [[PDF](https://link.springer.com/chapter/10.1007/978-3-030-88552-6_6)] [[Github](https://github.com/icon-lab/SLATER)]
 
   **3D Transformer-GAN for High-quality PET Reconstruction.** [29th Sep., 2021] [⚡MICCAI, 2021].<br>
*Yanmei Luo, Yan Wang, Chen Zu, Bo Zhan, Xi Wu, Jiliu Zhou, Dinggang Shen, Luping Zhou.*<br>
 [[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87231-1_27)] 
 
   **TranSMS: Transformers for Super-Resolution Calibration in Magnetic Particle Imaging.** [3rd Nov., 2021] .<br>
*Alper Güngör, Baris Askin, Damla Alptekin Soydan, Emine Ulku Saritas, Can Barış Top, Tolga Çukur.*<br>
 [[PDF](https://arxiv.org/abs/2111.02163)] 
 
   **DuDoTrans: Dual-Domain Transformer Provides More Attention for Sinogram Restoration in Sparse-View CT Reconstruction.** [21st Nov., 2021] .<br>
*Ce Wang, Kun Shang, Haimiao Zhang, Qian Li, Yuan Hui, S. Kevin Zhou.*<br>
 [[PDF](https://arxiv.org/abs/2111.10790)]
 
   **Self-supervised CT super-resolution with hybrid model.** [23rd Nov., 2021] .<br>
*Zhicheng Zhang, Shaode Yu, Wenjian Qin, Xiaokun Liang, Yaoqin Xie, Guohua Cao.*<br>
 [[PDF](https://www.sciencedirect.com/science/article/pii/S0010482521005692)] 
 
   **MIST-net: Multi-domain Integrative Swin Transformer network for Sparse-View CT Reconstruction.** [29th Nov., 2021] .<br>
*Jiayi Pan, Weiwen Wu, Zhifan Gao, Heye Zhang.*<br>
 [[PDF](https://arxiv.org/abs/2111.14831)]

# Registration

  **ViT-V-Net: Vision Transformer for Unsupervised Volumetric Medical Image Registration.** [13th April, 2021] [👍MIDL Short Paper, 2021].<br>
*Junyu Chen, Yufan He, Eric C. Frey, Ye Li, Yong Du.*<br>
 [[PDF](https://arxiv.org/abs/2104.06468)] [[Github](https://github.com/junyuchen245/ViT-V-Net_for_3D_Image_Registration_Pytorch)]
 
   **Attention for Image Registration (AiR): an unsupervised Transformer approach.** [5th May, 2021].<br>
*Zihao Wang, Hervé Delingette.*<br>
 [[PDF](https://arxiv.org/abs/2105.02282)]
 
   **Learning Dual Transformer Network for Diffeomorphic Registration.** [21st Sep., 2021] [⚡MICCAI, 2021].<br>
*Yungeng Zhang, Yuru Pei, Hongbin Zha.*<br>
 [[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87202-1_13)]
 
   **TransMorph: Transformer for unsupervised medical image registration.** [19th Nov., 2021].<br>
*Junyu Chen, Yong Du, Yufan He, William P. Segars, Ye Li, Eric C. Frey.*<br>
 [[PDF](https://arxiv.org/abs/2111.10480)] [[Github](https://github.com/junyuchen245/TransMorph_Transformer_for_Medical_Image_Registration)]

# Synthesis

  **VTGAN: Semi-supervised Retinal Image Synthesis and Disease Prediction using Vision Transformers.** [14th April, 2021] [👍ICCV Workshop on Computer Vision for Automated Medical Diagnosi, 2021].<br>
*Sharif Amit Kamran, Khondker Fariha Hossain, Alireza Tavakkoli, Stewart Lee Zuckerbrod, Salah A. Baker.*<br>
 [[PDF](https://arxiv.org/abs/2104.06757)] [[Github](https://github.com/SharifAmit/VTGAN)]
 
   **PTNet: A High-Resolution Infant MRI Synthesizer Based on Transformer.** [28th May, 2021].<br>
*Xuzhe Zhang, Xinzi He, Jia Guo, Nabil Ettehadi, Natalie Aw, David Semanek, Jonathan Posner, Andrew Laine, Yun Wang.*<br>
 [[PDF](https://arxiv.org/abs/2105.13993)] [[Github](https://github.com/XuzheZ/PTNet)]
 
   **ResViT: Residual vision transformers for multi-modal medical image synthesis.** [30th June, 2021].<br>
*Onat Dalmaz, Mahmut Yurt, Tolga Çukur.*<br>
 [[PDF](https://arxiv.org/abs/2106.16031)] [[Github](https://github.com/icon-lab/ResViT)]
 
   **CyTran: Cycle-Consistent Transformers for Non-Contrast to Contrast CT Translation.** [12th Oct., 2021].<br>
*Nicolae-Catalin Ristea, Andreea-Iuliana Miron, Olivian Savencu, Mariana-Iuliana Georgescu, Nicolae Verga, Fahad Shahbaz Khan, Radu Tudor Ionescu.*<br>
 [[PDF](https://arxiv.org/abs/2110.06400)] [[Github](https://github.com/ristea/cycle-transformer)]

# Detection
 
   **COTR: Convolution in Transformer Network for End to End Polyp Detection.** [23rd May, 2021].<br>
*Zhiqiang Shen, Chaonan Lin, Shaohua Zheng.*<br>
 [[PDF](https://arxiv.org/abs/2105.10925)]
  
   **Transformer for Polyp Detection.** [14th Oct., 2021].<br>
*Shijie Liu, Hongyu Zhou, Xiaozhou Shi, Junwen Pan.*<br>
 [[PDF](https://arxiv.org/abs/2111.07918)]
  
   **Lymph Node Detection in T2 MRI with Transformers.** [9th Nov., 2021].<br>
*Tejas Sudharshan Mathai, Sungwon Lee, Daniel C. Elton, Thomas C. Shen, Yifan Peng, Zhiyong Lu, Ronald M. Summers.*<br>
 [[PDF](https://arxiv.org/abs/2111.04885)]
 
# Clinical-Report-Generation

   **Reinforced Transformer for Medical Image Captioning.** [10th Oct., 2019].[MLMI, 2019]<br>
*Yuxuan Xiong, Bo Du, Pingkun Yan.*<br>
 [[PDF](https://link.springer.com/chapter/10.1007/978-3-030-32692-0_77)] 

   **Improving Factual Completeness and Consistency of Image-to-Text Radiology Report Generation.** [20th Oct., 2020].[NAACL, 2020]<br>
*Yasuhide Miura, Yuhao Zhang, Emily Bao Tsai, Curtis P. Langlotz, Dan Jurafsky.*<br>
 [[PDF](https://arxiv.org/abs/2010.10042)] [[Github](https://github.com/ysmiura/ifcc)]

   **Generating Radiology Reports via Memory-driven Transformer.** [30th Oct., 2020].[EMNLP, 2020]<br>
*Zhihong Chen, Yan Song, Tsung-Hui Chang, Xiang Wan.*<br>
 [[PDF](https://arxiv.org/abs/2010.16056)] [[Github](https://github.com/cuhksz-nlp/R2Gen)]
 
   **Hierarchical X-Ray Report Generation via Pathology tags and Multi Head Attention.** [30th Nov., 2020].[EMNLP, 2020]<br>
*Preethi Srinivasan, Daksh Thapar, Arnav Bhavsar, Aditya Nigam.*<br>
 [[PDF](https://openaccess.thecvf.com/content/ACCV2020/html/Srinivasan_Hierarchical_X-Ray_Report_Generation_via_Pathology_tags_and_Multi_Head_ACCV_2020_paper.html)]
 
   **Confidence-Guided Radiology Report Generation.** [21st June, 2021].[⚡MICCAI, 2021]<br>
*Yixin Wang, Zihao Lin, Jiang Tian, Zhongchao Shi, Yang Zhang, Jianping Fan, Zhiqiang He.*<br>
 [[PDF](https://arxiv.org/abs/2106.10887)]
 
   **Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation.** [13th June, 2021].[⚡CVPR, 2021]<br>
*Fenglin Liu, Xian Wu, Shen Ge, Wei Fan, Yuexian Zou.*<br>
 [[PDF](https://arxiv.org/abs/2106.06963)]
 
   **RATCHET: Medical Transformer for Chest X-ray Diagnosis and Reporting.** [5th July, 2021].[⚡MICCAI, 2021]<br>
*Benjamin Hou, Georgios Kaissis, Ronald Summers, Bernhard Kainz.*<br>
 [[PDF](https://arxiv.org/abs/2107.02104)] [[Github](https://github.com/farrell236/RATCHET)]
 
   **Surgical Instruction Generation with Transformers.** [14th July, 2021].[⚡MICCAI, 2021]<br>
*Jinglu Zhang, Yinyu Nie, Jian Chang, Jian Jun Zhang.*<br>
 [[PDF](https://arxiv.org/abs/2107.06964)]
 
   **Automated Generation of Accurate and Fluent Medical X-ray Reports.** [27th Aug., 2021].[EMNLP, 2021]<br>
*Hoang T.N. Nguyen, Dong Nie, Taivanbat Badamdorj, Yujie Liu, Yingying Zhu, Jason Truong, Li Cheng.*<br>
 [[PDF](https://arxiv.org/abs/2108.12126)] [[Github](https://github.com/ginobilinie/xray_report_generation)]
 
   **AlignTransformer: Hierarchical Alignment of Visual Regions and Disease Tags for Medical Report Generation.** [1st Sep., 2021].[⚡MICCAI, 2021]<br>
*Di You, Fenglin Liu, Shen Ge, Xiaoxia Xie, Jing Zhang, Xian Wu.*<br>
 [[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_7)] 
 
   **Automatic Generation of Chest X-ray Reports Using a Transformer-based Deep Learning Model.** [20th Oct., 2021].[ICDS, 2021]<br>
*Ayoub Benali Amjoud; Mustapha Amrouch.*<br>
 [[PDF](https://ieeexplore.ieee.org/document/9626725/)]
  
   **FFA-IR: Towards an Explainable and Reliable Medical Report Generation Benchmark.** [31st Oct., 2021].[⚡NeurIPS, 2021]<br>
*Mingjie Li, Wenjia Cai, Rui Liu, Yuetian Weng, Xiaoyun Zhao, Cong Wang, Xin Chen, Zhong Liu, Caineng Pan, Mengke Li, yingfeng zheng, Yizhi Liu, Flora D. Salim, Karin Verspoor, Xiaodan Liang, Xiaojun Chang.*<br>
 [[PDF](https://openreview.net/pdf?id=FgYTwJbjbf)] [[Github](https://github.com/mlii0117/FFA-IR)]
 
   **Auto-Encoding Knowledge Graph for Unsupervised Medical Report Generation.** [8th Nov., 2021].[⚡NeurIPS, 2021]<br>
*Fenglin Liu, Chenyu You, Xian Wu, Shen Ge, Sheng Wang, Xu Sun.*<br>
 [[PDF](https://arxiv.org/abs/2111.04318)]
 

# Others

   **Multimodal Co-Attention Transformer for Survival Prediction in Gigapixel Whole Slide Images.** [22nd Sep., 2021]. [⚡ICCV, 2021]<br>
*Chen, Richard J and Lu, Ming Y and Weng, Wei-Hung and Chen, Tiffany Y and Williamson, Drew FK and Manz, Trevor and Shady, Maha and Mahmood, Faisal.*<br>
 [[PDF](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_Multimodal_Co-Attention_Transformer_for_Survival_Prediction_in_Gigapixel_Whole_Slide_ICCV_2021_paper.pdf)][[Github](https://github.com/mahmoodlab/mcat)]
 
   **Limitations of Transformers on Clinical Text Classification.** [25th Sep., 2021].<br>
*Shang Gao, Mohammed Alawad, M Todd Young, John Gounley, Noah Schaefferkoetter, Hong Jun Yoon, Xiao-Cheng Wu, Eric B Durbin, Jennifer Doherty, Antoinette Stroup, Linda Coyle, Georgia Tourassi.*<br>
 [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9364676)]

   **Explainable Transformer-Based Neural Network for the Prediction of Survival Outcomes in Non-Small Cell Lung Cancer (NSCLC).** [14th Oct., 2021].<br>
*Elly Kipkogei, Gustavo Alonso Arango Argoty, Ioannis Kagiampakis, Arijit Patra, Etai Jacob.*<br>
 [[PDF](https://www.medrxiv.org/content/10.1101/2021.10.11.21264761v1)]

   **3D Medical Point Transformer: Introducing Convolution to Attention Networks for Medical Point Cloud Analysis.** [9th Dec., 2021].<br>
*Jianhui Yu, Chaoyi Zhang, Heng Wang, Dingxin Zhang, Yang Song, Tiange Xiang, Dongnan Liu, Weidong Cai.*<br>
 [[PDF](https://arxiv.org/abs/2112.04863)]
 
   **Pre-training and Fine-tuning Transformers for fMRI Prediction Tasks.** [10th Dec., 2021].<br>
*Itzik Malkiel, Gony Rosenman, Lior Wolf, Talma Hendler.*<br>
 [[PDF](https://arxiv.org/abs/2112.05761)]
 
   **Does CLIP Benefit Visual Question Answering in the Medical Domain as Much as it Does in the General Domain?.** [27th Dec., 2021].<br>
*Sedigheh Eslami, Gerard de Melo, Christoph Meinel.*<br>
 [[PDF](https://arxiv.org/abs/2112.13906)]
 
