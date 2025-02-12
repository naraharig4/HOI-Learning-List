# HOI-Learning-List
Some recent (2015-now) Human-Object Interaction Learing studies. If you find any errors or problems, please feel free to comment.

A list of Transfomer-based vision works: https://github.com/DirtyHarryLYL/Transformer-in-Vision.

## Dataset/Benchmark

- Bongard-HOI [[Paper]](https://openreview.net/pdf?id=mHrF3-r8-8t)

- HOI-COCO (CVPR2021) [[Website]](https://github.com/zhihou7/HOI-CL)

- PaStaNet-HOI (TPAMI2021) [[Benchmark]](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network/tree/master/PaStaNet-HOI_Benckmark)

- HAKE (CVPR2020) [[YouTube]](https://t.co/hXiAYPXEuL?amp=1) [[bilibili]](https://www.bilibili.com/video/BV1s54y1Y76s) [[Website]](http://hake-mvig.cn/home/) [[Paper]](https://arxiv.org/pdf/2004.00945.pdf) [[HAKE-Action-Torch]](https://github.com/DirtyHarryLYL/HAKE-Action-Torch) [[HAKE-Action-TF]](https://github.com/DirtyHarryLYL/HAKE-Action)

- Ambiguous-HOI (CVPR2020) [[Website]](https://github.com/DirtyHarryLYL/DJ-RN) [[Paper]](https://arxiv.org/pdf/2004.08154.pdf)

- HICO-DET (WACV2018) [[Website]](http://www-personal.umich.edu/~ywchao/hico/) [[Paper]](http://www-personal.umich.edu/~ywchao/publications/chao_wacv2018.pdf)

- HCVRD (AAAI2018) [[Website]](https://bitbucket.org/jingruixiaozhuang/hcvrd-a-benchmark-for-large-scale-human-centered-visual/src/master/) [[Paper]](https://pdfs.semanticscholar.org/c94f/1aaf62f87d97dd579cb6451cb9149fb4967d.pdf)

- V-COCO (May 2015) [[Website]](https://github.com/s-gupta/v-coco) [[Paper]](https://arxiv.org/pdf/1505.04474.pdf)

- HICO (ICCV2015) [[Website]](http://www-personal.umich.edu/~ywchao/hico/) [[Paper]](http://www-personal.umich.edu/~ywchao/publications/chao_iccv2015.pdf)

- OpenImage [[Website]](https://visualgenome.org/) [[Paper]](https://arxiv.org/abs/1602.07332)

- PIC [[Website]](http://picdataset.com/challenge/index/)

More...

### Video HOI Datasets

- VidHOI [[Paper]](https://arxiv.org/pdf/2105.11731.pdf)

- AVA [[Website]](http://research.google.com/ava/), HOIs (human-object, human-human) and pose (body motion) actions

- Action Genome [[Website]](https://www.actiongenome.org/), action verbs and spatial relationships

- CAD120 [[Paper]](https://arxiv.org/pdf/1210.1207.pdf), [[Website]](http://pr.cs.cornell.edu/humanactivities/)


## Method

### HOI Image Generation
- Exploiting Relationship for Complex-scene Image Generation (arXiv 2021.04) [[Paper]](https://arxiv.org/pdf/2104.00356.pdf)

- Specifying Object Attributes and Relations in Interactive Scene Generation (arXiv 2019.11) [[Paper]](https://arxiv.org/pdf/1909.05379.pdf)

### HOI Recognition: Image-based, to recognize all the HOIs in one image.

- DEFR-CLIP (arXiv 2021.07) [[Paper]](https://arxiv.org/pdf/2107.13083.pdf)

- PaStaNet: Toward Human Activity Knowledge Engine 
(CVPR2020) [[Code]](https://github.com/DirtyHarryLYL/HAKE-Action/tree/Image-level-HAKE-Action) [[Data]](https://github.com/DirtyHarryLYL/HAKE) [[Paper]](https://arxiv.org/pdf/2004.00945.pdf) [[YouTube]](https://t.co/hXiAYPXEuL?amp=1) [[bilibili]](https://www.bilibili.com/video/BV1s54y1Y76s)

- Pairwise (ECCV2018) [[Paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Haoshu_Fang_Pairwise_Body-Part_Attention_ECCV_2018_paper.pdf)

- Attentional Pooling for Action Recognition (NIPS2017) [[Code]](https://github.com/rohitgirdhar/AttentionalPoolingAction) [[Paper]](https://arxiv.org/pdf/1711.01467.pdf)

- Learning Models for Actions and Person-Object Interactions with Transfer to Question Answering (ECCV2016) [[Code]](https://uofi.box.com/s/yflrqbser1r5m3iez1satkprawmsouag) [[Paper]](https://arxiv.org/pdf/1604.04808.pdf)

- Contextual Action Recognition with R\*CNN (ICCV2015) [[Code]](https://github.com/gkioxari/RstarCNN) [[Paper]](https://arxiv.org/pdf/1505.01197.pdf)

- HOCNN (ICCV2015) [[Code]](https://github.com/ywchao/hico_benchmark) [[Paper]](http://www-personal.umich.edu/~ywchao/publications/chao_iccv2015.pdf)

- SGAP-Net (AAAI2020) [[Paper]](https://aaai.org/Papers/AAAI/2020GB/AAAI-JiZ.4799.pdf)

More...

#### Unseen or zero-shot learning (image-level recognition).

- Compositional Learning for Human Object Interaction (ECCV2018) [[Paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Keizo_Kato_Compositional_Learning_of_ECCV_2018_paper.pdf)

- Zero-Shot Human-Object Interaction Recognition via Affordance Graphs (Sep. 2020) [[Paper]](https://arxiv.org/pdf/2009.01039.pdf)

More...

### HOI Detection: Instance-based, to detect the human-object pairs and classify the interactions.

- CDN (arXiv 2021.8) [[Paper]](https://arxiv.org/pdf/2108.05077.pdf)

- GTNet (arXiv 2021.8) [[Paper]](https://arxiv.org/pdf/2108.00596.pdf), [[Code]](https://github.com/UCSB-VRL/GTNet)

- HOI-MO-Net (IVC 2021) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0262885621001670?via%3Dihub#tbl0005)

- IPGN (TIP 2021.7) [[Paper]](https://ieeexplore.ieee.org/document/9489275)

- SCG (arXiv 2021.5, SAG, v2) [[Paper]](https://arxiv.org/pdf/2012.06060.pdf), [[Code]](https://github.com/fredzzhang/spatially-conditioned-graphs)

- Human Object Interaction Detection using Two-Direction Spatial Enhancement and Exclusive Object Prior (arXiv) [[Paper]](https://arxiv.org/pdf/2105.03089.pdf)

- PST (arXiv 2021.5) [[Paper]](https://arxiv.org/pdf/2105.02170.pdf)

- RR-Net (arXiv 2021.5) [[Paper]](https://arxiv.org/pdf/2104.15015.pdf)

- HOTR (CVPR2021) [[Paper]](https://arxiv.org/pdf/2104.13682.pdf), [[Code]](https://github.com/kakaobrain/HOTR)

- GGNet (CVPR2021) [[Paper]](https://arxiv.org/pdf/2104.05269.pdf), [[Code]](https://github.com/SherlockHolmes221/GGNet)

- ATL (CVPR2021) [[Paper]](https://arxiv.org/pdf/2104.02867.pdf), [[Code]](https://github.com/zhihou7/HOI-CL)

- FCL (CVPR2021) [[Paper]](https://arxiv.org/pdf/2103.08214.pdf), [[Code]](https://github.com/zhihou7/FCL)

- AS-Net (CVPR2021) [[Paper]](https://arxiv.org/pdf/2103.05983.pdf), [[Code]](https://github.com/yoyomimi/AS-Net)

- End-to-End Human Object Interaction Detection with HOI Transformer (CVPR2021), [[Paper]](https://arxiv.org/pdf/2103.04503.pdf), [[Code]](https://github.com/bbepoch/HoiTransformer)

- QPIC (CVPR2021) [[Paper]](https://arxiv.org/pdf/2103.05399.pdf), [[Code]](https://github.com/hitachi-rd-cv/qpic)

- TIN (TPAMI2021) [[Paper]](https://arxiv.org/pdf/2101.10292.pdf), [[Code]](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network)

- IDN (NeurIPS2020) [[Paper]](https://arxiv.org/pdf/2010.16219.pdf) [[Code]](https://github.com/DirtyHarryLYL/HAKE-Action-Torch/tree/IDN-(Integrating-Decomposing-Network))

- DIRV (AAAI2021) [[Paper]](https://arxiv.org/pdf/2010.01005.pdf)

- DecAug (AAAI2021) [[Paper]](https://arxiv.org/pdf/2010.01007.pdf)

- OSGNet (IEEE Access) [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9360596)

- PFNet (CVM) [[Paper]](https://link.springer.com/content/pdf/10.1007/s41095-020-0188-2.pdf)

- UniDet (ECCV2020) [[Paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600494.pdf)

- DRG (ECCV2020) [[Paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570681.pdf) [[Code]](https://github.com/vt-vl-lab/DRG)

- FCMNet (ECCV2020) [[Paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590239.pdf)

- Contextual Heterogeneous Graph Network for Human-Object Interaction Detection (ECCV2020) [[Paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620239.pdf)

- PD-Net (ECCV2020) [[Paper-1]](https://www.researchgate.net/publication/343536295_Polysemy_Deciphering_Network_for_Human-Object_Interaction_Detection) [[Paper-2]](https://arxiv.org/pdf/2008.02918.pdf) [[Code]](https://github.com/MuchHair/PD-Net)

- VCL (ECCV2020) [[Paper]](https://arxiv.org/pdf/2007.12407.pdf) [[Code]](https://github.com/zhihou7/VCL)

- ACP (ECCV2020) [[Paper]](https://arxiv.org/pdf/2007.08728.pdf) [[Code]](https://github.com/Dong-JinKim/ActionCooccurrencePriors/)

- ConsNet (ACMMM2020) [[Paper]](https://arxiv.org/pdf/2008.06254.pdf) [[Code]](https://github.com/yeliudev/ConsNet), **HICO-DET Python API**: A general Python toolkit for the HICO-DET dataset, including APIs for data loading & processing, human-object pair IoU & NMS calculation, and standard evaluation. [[Code]](https://github.com/yeliudev/ConsNet) [[Documentation]](https://consnet.readthedocs.io/)

- Action-Guided Attention Mining and Relation Reasoning Network for Human-Object Interaction Detection (IJCAI2020) [[Paper]](https://www.ijcai.org/Proceedings/2020/0154.pdf)

- PaStaNet (CVPR2020) [[Code]](https://github.com/DirtyHarryLYL/HAKE-Action/tree/Instance-level-HAKE-Action) [[Data]](https://github.com/DirtyHarryLYL/HAKE) [[Paper]](https://arxiv.org/pdf/2004.00945.pdf) [[YouTube]](https://t.co/hXiAYPXEuL?amp=1) [[bilibili]](https://www.bilibili.com/video/BV1s54y1Y76s)

- DJ-RN (CVPR2020) [[Code]](https://github.com/DirtyHarryLYL/DJ-RN) [[Paper]](https://arxiv.org/pdf/2004.08154.pdf)

- Cascaded Human-Object Interaction Recognition (CVPR2020) [[Code]](https://github.com/tfzhou/C-HOI) [[Paper]](https://arxiv.org/pdf/2003.04262.pdf)

- PPDM (CVPR2020) [[Code]](https://github.com/YueLiao/PPDM) [[Paper]](https://arxiv.org/pdf/1912.12898.pdf)

- IP-Net (CVPR2020) [[Code]](https://github.com/vaesl/IP-Net) [[Paper]](https://arxiv.org/pdf/2003.14023.pdf)

- VSGNet (CVPR2020) [[Code]](https://github.com/ASMIftekhar/VSGNet) [[Paper]](https://arxiv.org/pdf/2003.05541.pdf)

- HOID (CVPR2020) [[Code]](https://github.com/scwangdyd/zero_shot_hoi) [[Paper]](https://cse.buffalo.edu/~jsyuan/papers/2020/05225.pdf)

- Diagnosing Rarity in Human-Object Interaction Detection (CVPRW2020) [[Paper]](https://arxiv.org/pdf/2006.05728.pdf)

- MLCNet (ICMR2020) [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3372278.3390671)

- SIGN (ICME2020) [[Paper]](https://ieeexplore.ieee.org/ielx7/9099125/9102711/09102755.pdf)

- In-GraphNet (IJCAI-PRICAI 2020) [[Paper]](https://arxiv.org/pdf/2007.06925.pdf)

- PMFNet(ICCV2019) [[Code]](https://github.com/bobwan1995/PMFNet) [[Paper]](https://arxiv.org/abs/1909.08453)

- No-Frills (ICCV2019) [[Code]](https://github.com/BigRedT/no_frills_hoi_det) [[Paper]](http://tanmaygupta.info/assets/img/no_frills/paper.pdf)

- Analogy (ICCV2019) [[Code]](https://github.com/jpeyre/analogy) [[Paper]](https://www.di.ens.fr/willow/research/analogy/paper.pdf)

- RPNN (ICCV2019) [[Paper]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhou_Relation_Parsing_Neural_Network_for_Human-Object_Interaction_Detection_ICCV_2019_paper.pdf)

- Deep Contextual Attention for Human-Object Interaction Detection (ICCV2019) [[Paper]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Deep_Contextual_Attention_for_Human-Object_Interaction_Detection_ICCV_2019_paper.pdf)

- Interactiveness (CVPR2019) [[Code]](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network) [[Paper]](https://arxiv.org/pdf/1811.08264.pdf)

- Turbo (AAAI2019) [[Paper]](https://arxiv.org/pdf/1903.06355.pdf)

- GPNN (ECCV2018) [[Code]](https://github.com/SiyuanQi/gpnn) [[Paper]](https://arxiv.org/pdf/1808.07962.pdf)

- iCAN (BMVC2018) [[Code]](https://github.com/vt-vl-lab/iCAN) [[Paper]](https://arxiv.org/pdf/1808.10437.pdf)

- InteractNet (CVPR2018) [[Paper]](https://arxiv.org/pdf/1704.07333.pdf)

- Scaling Human-Object Interaction Recognition through Zero-Shot Learning (WACV2018) [[Paper]](http://vision.stanford.edu/pdf/shen2018wacv.pdf)

- HO-RCNN (WACV2018) [[Code]](https://github.com/ywchao/ho-rcnn) [[Paper]](http://www-personal.umich.edu/~ywchao/publications/chao_wacv2018.pdf) 

- VS-GATs (Mar. 2020) [[Paper]](https://arxiv.org/pdf/2001.02302.pdf)

- Classifying All Interacting Pairs in a Single Shot (Jan. 2020) [[Paper]](https://arxiv.org/pdf/2001.04360.pdf)

- Novel Human-Object Interaction Detection via Adversarial Domain Generalization (May. 2020) [[Paper]](https://arxiv.org/pdf/2005.11406.pdf)

- PMN (Jul. 2020) [[Paper]](https://arxiv.org/pdf/2008.02042.pdf) [[Code]](https://github.com/birlrobotics/PMN)

- SAG (Dec 2020) [[Paper]](https://arxiv.org/pdf/2012.06060.pdf) [[Code]](https://github.com/fredzzhang/spatio-attentive-graphs)

- SABRA (Dec 2020) [[Paper]](https://arxiv.org/pdf/2012.12510.pdf)

More...

#### Unseen or zero-shot learning (instance-level detection).
- DGIG-Net (TOC2021) [[Paper]](https://ieeexplore.ieee.org/abstract/document/9352497)

- ATL (CVPR2021)  [[Paper]](https://arxiv.org/pdf/2104.02867.pdf), [[Code]](https://github.com/zhihou7/HOI-CL)

- FCL (CVPR2021) [[Paper]](https://arxiv.org/pdf/2103.08214.pdf), [[Code]](https://github.com/zhihou7/FCL)

- Detecting Human-Object Interaction with Mixed Supervision (WACV 2021) [[Paper]](https://arxiv.org/pdf/2011.04971v1.pdf)

- ConsNet (ACMMM2020) [[Paper]](https://arxiv.org/pdf/2008.06254.pdf) [[Code]](https://github.com/yeliudev/ConsNet)

- Zero-Shot Human-Object Interaction Recognition via Affordance Graphs (Sep. 2020) [[Paper]](https://arxiv.org/pdf/2009.01039.pdf)

- VCL (ECCV2020) [[Paper]](https://arxiv.org/pdf/2007.12407.pdf) [[Code]](https://github.com/zhihou7/VCL)

- HOID (CVPR2020) [[Code]](https://github.com/scwangdyd/zero_shot_hoi) [[Paper]](https://cse.buffalo.edu/~jsyuan/papers/2020/05225.pdf)

- Novel Human-Object Interaction Detection via Adversarial Domain Generalization (May. 2020) [[Paper]](https://arxiv.org/pdf/2005.11406.pdf)

- Analogy (ICCV2019) [[Code]](https://github.com/jpeyre/analogy) [[Paper]](https://www.di.ens.fr/willow/research/analogy/paper.pdf)

- Functional (AAAI2020) [[Paper]](https://arxiv.org/pdf/1904.03181.pdf)

- Scaling Human-Object Interaction Recognition through Zero-Shot Learning (WACV2018) [[Paper]](http://vision.stanford.edu/pdf/shen2018wacv.pdf)

More...

### Video HOI methods
- VidHOI (May 2021), [[Paper]](https://arxiv.org/pdf/2105.11731.pdf)

- LIGHTEN (ACMMM2020) [[Paper]](https://www.cse.iitb.ac.in/~rdabral/docs/acm_lighten.pdf) [[Code]](https://github.com/praneeth11009/LIGHTEN-Learning-Interactions-with-Graphs-and-Hierarchical-TEmporal-Networks-for-HOI)

- Generating Videos of Zero-Shot Compositions of Actions and Objects (Jul 2020), HOI GAN, [[Paper]](https://arxiv.org/pdf/1912.02401.pdf)

- Grounded Human-Object Interaction Hotspots from Video (ICCV2019) [[Code]](https://github.com/Tushar-N/interaction-hotspots) [[Paper]](https://arxiv.org/pdf/1812.04558.pdf)

- GPNN (ECCV2018) [[Code]](https://github.com/SiyuanQi/gpnn) [[Paper]](https://arxiv.org/pdf/1808.07962.pdf)

More...

## Result

### [PaStaNet-HOI](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network):
Proposed by TIN (TPAMI version, Transferable Interactiveness Network).
It is built on HAKE data, includes 110K+ images and 520 HOIs (without the 80 "no_interaction" HOIs of HICO-DET to avoid the incomplete labeling). 
It has a more severe long-tailed data distribution thus is more difficult.

#### Detector: COCO pre-trained
|Method| mAP |
|:---:|:---:|
|iCAN|11.00|
|iCAN+NIS|13.13|
|[TIN](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network)| **15.38**|


### HICO-DET:

#### 1) Detector: COCO pre-trained
|Method| Pub|Full(def) | Rare(def) | None-Rare(def)| Full(ko) | Rare(ko) | None-Rare(ko) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[Shen et al.](http://vision.stanford.edu/pdf/shen2018wacv.pdf)| WACV2018 |  6.46 | 4.24 | 7.12| - | - | - |
|[HO-RCNN](http://www-personal.umich.edu/~ywchao/publications/chao_wacv2018.pdf)| WACV2018 | 7.81|  5.37|  8.54|  10.41|  8.94 | 10.85 |
|[InteractNet](https://arxiv.org/pdf/1704.07333.pdf)| CVPR2018 |  9.94|  7.16 | 10.77| - | - |-|
|[Turbo](https://arxiv.org/pdf/1903.06355.pdf)|AAAI2019|11.40| 7.30| 12.60|- | - |-|
|[GPNN](https://arxiv.org/pdf/1808.07962.pdf)| ECCV2018 |  13.11 | 9.34 | 14.23| - | - |-|
|[Xu et. al](https://www-users.cs.umn.edu/~qzhao/publications/pdf/xu2019cvpr.pdf)|ICCV2019|14.70 |13.26| 15.13|-|-|-|
|[iCAN](https://arxiv.org/pdf/1808.10437.pdf)| BMVC2018 | 14.84|  10.45 | 16.15 | 16.26  | 11.33| 17.73 |
|[Wang et. al.](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Deep_Contextual_Attention_for_Human-Object_Interaction_Detection_ICCV_2019_paper.pdf)|ICCV2019|16.24 |11.16| 17.75| 17.73| 12.78| 19.21|
|[Lin et. al](https://www.ijcai.org/Proceedings/2020/0154.pdf)|IJCAI2020|16.63 |11.30| 18.22| 19.22| 14.56| 20.61|
|[Functional](https://arxiv.org/pdf/1904.03181.pdf) (suppl)|AAAI2020|16.96| 11.73 |18.52| -|-|-|
|[Interactiveness](https://arxiv.org/pdf/1811.08264.pdf)| CVPR2019 | 17.03 | 13.42| 18.11| 19.17| 15.51|20.26|
|[No-Frills](http://tanmaygupta.info/assets/img/no_frills/paper.pdf)| ICCV2019 | 17.18 |12.17| 18.68 |-|-|-|
|[RPNN](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhou_Relation_Parsing_Neural_Network_for_Human-Object_Interaction_Detection_ICCV_2019_paper.pdf)|ICCV2019|17.35| 12.78| 18.71|-|-|-|
|[PMFNet](https://arxiv.org/pdf/1909.08453.pdf)| ICCV2019 | 17.46| 15.65| 18.00| 20.34| 17.47| 21.20|
|[SIGN](https://ieeexplore.ieee.org/ielx7/9099125/9102711/09102755.pdf)|ICME2020|17.51| 15.31 |18.53 |20.49| 17.53| 21.51|
|[Interactiveness-optimized](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network)| CVPR2019 | 17.54	|13.80	|18.65|	19.75|	15.70|	20.96|
|[Liu et.al.](https://arxiv.org/pdf/2105.03089.pdf)|arXiv|17.55 |20.61|-|-|-|-|
|[Wang et al.](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620239.pdf)|ECCV2020|17.57 |16.85| 17.78| 21.00| 20.74| 21.08|
|[In-GraphNet](https://arxiv.org/pdf/2007.06925.pdf)|IJCAI-PRICAI 2020|17.72 |12.93 |19.31|-|-|-|
|[HOID](https://github.com/scwangdyd/zero_shot_hoi)|CVPR2020| 17.85 |12.85 |19.34|-|-|-|
|[MLCNet](https://dl.acm.org/doi/pdf/10.1145/3372278.3390671)| ICMR2020| 17.95 |16.62 |18.35|22.28 |20.73 |22.74|
|[SAG](https://github.com/fredzzhang/spatio-attentive-graphs)|arXiv| 18.26 |13.40 |19.71|-|-|-|
|[Sarullo et al.](https://arxiv.org/pdf/2009.01039.pdf)|arXiv|18.74|-|-|-|-|-|
|[DRG](https://github.com/vt-vl-lab/DRG)|ECCV2020|19.26 |17.74 |19.71 |23.40 |21.75 |23.89|
|[Analogy](https://www.di.ens.fr/willow/research/analogy/paper.pdf)| ICCV2019 | 19.40 |14.60| 20.90|-|-|-|
|[VCL](https://github.com/zhihou7/VCL)|ECCV2020|19.43 |16.55| 20.29| 22.00| 19.09| 22.87|
|[VS-GATs](https://arxiv.org/pdf/2001.02302.pdf)|arXiv|19.66 |15.79 |20.81|-|-|-|
|[VSGNet](https://github.com/ASMIftekhar/VSGNet)|CVPR2020|19.80 |16.05| 20.91|-|-|-|
|[PFNet](https://link.springer.com/content/pdf/10.1007/s41095-020-0188-2.pdf)|CVM|20.05 |16.66 |21.07| 24.01| 21.09| 24.89|
|[ATL(w/ affordance)](https://github.com/zhihou7/HOI-CL)|CVPR2021 |20.08| 15.57| 21.43|-|-|-|
|[ATL](https://github.com/zhihou7/HOI-CL)|CVPR2021|21.07 |16.79| 22.35|-|-|-|
|[FCMNet](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590239.pdf)|ECCV2020|20.41 |17.34| 21.56| 22.04 |18.97| 23.12|
|[ACP](https://github.com/Dong-JinKim/ActionCooccurrencePriors/)|ECCV2020|20.59 |15.92| 21.98|-|-|-|
|[PD-Net](https://github.com/MuchHair/PD-Net)|ECCV2020|20.81 |15.90| 22.28| 24.78| 18.88| 26.54|
|[TIN-PAMI](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network)|TAPMI2021|20.93	|18.95|	21.32|	23.02|	20.96|	23.42|
|[PMN](https://github.com/birlrobotics/PMN)|arXiv|21.21 |17.60| 22.29|-|-|-|
|[IPGN](https://ieeexplore.ieee.org/document/9489275)|TIP2021|21.26|18.47|22.07|-|-|-|
|[DJ-RN](https://github.com/DirtyHarryLYL/DJ-RN)| CVPR2020 | 21.34|18.53|22.18|23.69|20.64|24.60|
|[OSGNet](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9360596)|IEEE Access|21.40 |18.12| 22.38|-|-|-|
|[DIRV](https://arxiv.org/pdf/2010.01005.pdf)| AAAI2021|21.78| 16.38| 23.39| 25.52| 20.84| 26.92|
|[SCG](https://github.com/fredzzhang/spatially-conditioned-graphs)|arXiv| 21.85| 18.11 |22.97|-|-|-|
|[ConsNet](https://github.com/yeliudev/ConsNet)|ACMMM2020|22.15|17.55|23.52|26.57|20.8|**28.3**|
|[IDN](https://github.com/DirtyHarryLYL/HAKE-Action-Torch/tree/IDN-(Integrating-Decomposing-Network))|NeurIPS2020|**23.36**|**22.47**|**23.63**|**26.43**|**25.01**|26.85|

#### 2) Detector: pre-trained on COCO, fine-tuned on HICO-DET train set (with GT human-object pair boxes) or one-stage detector (point-based, transformer-based)
Finetuned detector would learn to **only detect the interactive humans and objects** (with interactiveness), thus suppress many wrong pairings (non-interactive human-object pairs) and boost the performance.
|Method| Pub|Full(def) | Rare(def) | None-Rare(def)| Full(ko) | Rare(ko) | None-Rare(ko) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[UniDet](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600494.pdf)|ECCV2020|17.58 |11.72 |19.33 |19.76 |14.68 |21.27|
|[IP-Net](https://arxiv.org/pdf/2003.14023.pdf) | CVPR2020| 19.56 |12.79| 21.58 |22.05 |15.77 |23.92|
|[RR-Net](https://arxiv.org/pdf/2104.15015.pdf)|arXiv|20.72 |13.21 |22.97| -|-|-|
|[PPDM](https://arxiv.org/pdf/1912.12898v1.pdf) (paper) |CVPR2020|21.10 |14.46| 23.09| -|-|-|
|[PPDM](https://github.com/YueLiao/PPDM) (github-hourglass104) |CVPR2020|21.73/21.94	|13.78/13.97	|24.10/24.32	|24.58/24.81|	16.65/17.09|	26.84/27.12|
|[Functional](https://arxiv.org/pdf/1904.03181.pdf) |AAAI2020|21.96 |16.43|23.62| -|-|-|
|[SABRA-Res50](https://arxiv.org/pdf/2012.12510.pdf)| arXiv| 23.48| 16.39| 25.59| 28.79| 22.75| 30.54|
|[VCL](https://github.com/zhihou7/VCL)|ECCV2020|23.63 |17.21 |25.55 |25.98 |19.12 |28.03|
|[PST](https://arxiv.org/pdf/2105.02170.pdf)|arXiv|23.93| 14.98| 26.60| 26.42| 17.61| 29.05|
|[SABRA-Res50FPN](https://arxiv.org/pdf/2012.12510.pdf)| arXiv| 24.12 |15.91| 26.57| 29.65| 22.92| 31.65|
|[DRG](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570681.pdf)|ECCV2020|24.53 |19.47 |26.04 |27.98 |23.11 |29.43|
|[HOTR](https://github.com/kakaobrain/HOTR)|CVPR2021|25.10| 17.34| 27.42| -|-|-|
|[ConsNet-F](https://github.com/yeliudev/ConsNet)|ACMMM2020|25.94|19.35|27.91|30.34|23.4|32.41|
|[SABRA-Res152](https://arxiv.org/pdf/2012.12510.pdf)| arXiv| 26.09 |16.29| 29.02| 31.08| 23.44| 33.37|
|[IDN](https://github.com/DirtyHarryLYL/HAKE-Action-Torch/tree/IDN-(Integrating-Decomposing-Network))|NeurIPS2020|26.29|22.61|27.39|28.24|24.47|29.37|
|[Zou et al.](https://github.com/bbepoch/HoiTransformer)|CVPR2021|26.61 |19.15| 28.84| 29.13| 20.98| 31.57|
|[ATL](https://github.com/zhihou7/HOI-CL)|CVPR2021|27.68 |20.31 |29.89 |30.05 |22.40 |32.34|
|[GTNet](https://github.com/UCSB-VRL/GTNet)|arXiv|28.03 |22.73| 29.61| 29.98| 24.13| 31.73|
|[ATL(w/ affordance)](https://github.com/zhihou7/HOI-CL)|CVPR2021|28.53 |21.64| 30.59| 31.18| 24.15| 33.29|
|[AS-Net](https://github.com/yoyomimi/AS-Net)|CVPR2021|28.87 |24.25 |30.25 |31.74 |27.07|33.14|
|[QPIC-Res50](https://github.com/hitachi-rd-cv/qpic)|CVPR2021| 29.07 |21.85 |31.23 |31.68 |24.14 |33.93|
|[FCL](https://github.com/zhihou7/FCL)|CVPR2021|29.12 |23.67 |30.75 |31.31 |25.62 |33.02|
|[GGNet](https://github.com/SherlockHolmes221/GGNet)|CVPR2021|29.17 |22.13 |30.84 |33.50| 26.67 |34.89|
|[QPIC-Res101](https://github.com/hitachi-rd-cv/qpic)|CVPR2021|29.90 |23.92 |31.69 |32.38 |26.06 |34.27|
|[SCG](https://github.com/fredzzhang/spatially-conditioned-graphs)|arXiv|31.33| 24.72| 33.31|-|-|-|
|[CDN](https://arxiv.org/pdf/2108.05077.pdf)|arXiv|**32.07**| **27.19**| **33.53**| **34.79**| **29.48**| **36.38**|

#### 3) Ground Truth human-object pair boxes (only evaluating HOI recognition)
|Method| Pub|Full(def) | Rare(def) | None-Rare(def)|
|:---:|:---:|:---:|:---:|:---:|
|[iCAN](https://arxiv.org/pdf/1808.10437.pdf)| BMVC2018 | 33.38|  21.43 |36.95|
|[Interactiveness](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network)| CVPR2019 |34.26|22.90 |37.65|
|[Analogy](https://www.di.ens.fr/willow/research/analogy/paper.pdf)| ICCV2019 |34.35 | 27.57 |36.38|
|[ATL](https://github.com/zhihou7/HOI-CL)|CVPR2021|43.32 |33.84| 46.15|
|[IDN](https://github.com/DirtyHarryLYL/HAKE-Action-Torch/tree/IDN-(Integrating-Decomposing-Network))|NeurIPS2020|43.98|40.27|45.09|
|[ATL(w/ affordance)](https://github.com/zhihou7/HOI-CL)|CVPR2021|44.27| 35.52| 46.89|
|[FCL](https://github.com/zhihou7/FCL)|CVPR2021|45.25|36.27 |47.94|
|[GTNet](https://github.com/UCSB-VRL/GTNet)|arXiv|46.45 |35.10 |49.84|
|[SCG](https://github.com/fredzzhang/spatially-conditioned-graphs)|arXiv|51.53| **41.01**| 54.67|
|[ConsNet](https://github.com/yeliudev/ConsNet)|ACMMM2020|**53.04**|38.79|**57.3**|

#### 4) Enhanced with HAKE:
|Method| Pub|Full(def) | Rare(def) | None-Rare(def)| Full(ko) | Rare(ko) | None-Rare(ko) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[iCAN](https://arxiv.org/pdf/1808.10437.pdf)| BMVC2018 | 14.84	|10.45	|16.15|	16.26	|11.33|	17.73|
|[iCAN + HAKE-HICO-DET](https://github.com/DirtyHarryLYL/HAKE-Action/tree/Instance-level-HAKE-Action)| CVPR2020 | 19.61 (**+4.77**)	|17.29	|20.30|	22.10|	20.46|	22.59|
|[Interactiveness](https://arxiv.org/pdf/1811.08264.pdf)| CVPR2019 | 17.03 | 13.42| 18.11| 19.17| 15.51|20.26|
|[Interactiveness + HAKE-HICO-DET](https://github.com/DirtyHarryLYL/HAKE-Action/tree/Instance-level-HAKE-Action)| CVPR2020 | 22.12 (**+5.09**)|20.19|22.69|24.06|22.19|24.62|
|[Interactiveness + HAKE-Large](https://github.com/DirtyHarryLYL/HAKE-Action/tree/Instance-level-HAKE-Action)| CVPR2020 | 22.66 (**+5.63**)|21.17|23.09|24.53|23.00|24.99|

#### 5) Zero-Shot HOI detection:

##### Unseen action-object combination scenario (UC)

| Method | Pub | Detector | Full(def) | Seen(def) | Unseen(def)|
|:---:|:---:|:---:|:---:|:---:|:---:|
| [Shen et al.](http://vision.stanford.edu/pdf/shen2018wacv.pdf) | WACV2018 | COCO | 6.26 | - | 5.62 |
| [Functional](https://arxiv.org/pdf/1904.03181.pdf) | AAAI2020 | HICO-DET | 12.45 ± 0.16 | 12.74 ± 0.34 | 11.31 ± 1.03 |
| [VCL](https://github.com/zhihou7/VCL) | ECCV2020 | HICO-DET | 18.06 | 18.52 | 16.22 |
| [ATL(w/ affordance)](https://github.com/zhihou7/HOI-CL)|CVPR2021| HICO-DET |18.67|18.78|18.25|
| [FCL](https://github.com/zhihou7/FCL) | CVPR2021 | HICO-DET | 19.37 | 19.55 | **18.66** |
| [ConsNet](https://github.com/yeliudev/ConsNet) | ACMMM2020 | COCO | **19.81 ± 0.32** | **20.51 ± 0.62** | 16.99 ± 1.67 |

##### Unseen object scenario (UO)

| Method | Pub | Detector | Full(def) | Seen(def) | Unseen(def)|
|:---:|:---:|:---:|:---:|:---:|:---:|
| [Functional](https://arxiv.org/pdf/1904.03181.pdf) | AAAI2020 | HICO-DET | 13.84 | 14.36 | 11.22 |
| [FCL](https://github.com/zhihou7/FCL) | CVPR2021 | HICO-DET | 19.87 | 20.74 | 15.54 |
| [ConsNet](https://github.com/yeliudev/ConsNet) | ACMMM2020 | COCO | **20.71** | **20.99** | **19.27** |

##### Unseen action scenario (UA)

| Method | Pub | Detector | Full(def) | Seen(def) | Unseen(def)|
|:---:|:---:|:---:|:---:|:---:|:---:|
| [ConsNet](https://github.com/yeliudev/ConsNet) | ACMMM2020 | COCO | **19.04** | **20.02** | **14.12** |

### [Ambiguous-HOI](https://github.com/DirtyHarryLYL/DJ-RN)
#### Detector: COCO pre-trained
|Method| mAP |
|:---:|:---:|
|[iCAN](https://github.com/vt-vl-lab/iCAN)| 8.14 |
|[Interactiveness](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network)| 8.22 |
|[Analogy(reproduced)](https://github.com/jpeyre/analogy)| 9.72 |
|[DJ-RN](https://github.com/DirtyHarryLYL/DJ-RN)| **10.37** |


### V-COCO: Scenario1

#### 1) Detector: COCO pre-trained or one-stage detector
|Method| Pub | AP(role) |
|:---:|:---:|:---:|
|[Gupta et al.](https://arxiv.org/pdf/1505.04474.pdf)|arXiv| 31.8|
|[InteractNet](https://arxiv.org/pdf/1704.07333.pdf)|CVPR2018|40.0|
|[Turbo](https://arxiv.org/pdf/1903.06355.pdf)|AAAI2019|42.0|
|[GPNN](https://arxiv.org/pdf/1808.07962.pdf)|ECCV2018|44.0|
|[iCAN](https://arxiv.org/pdf/1808.10437.pdf)| BMVC2018 | 45.3| 
|[Xu et. al](https://www-users.cs.umn.edu/~qzhao/publications/pdf/xu2019cvpr.pdf)| CVPR2019| 45.9|
|[Wang et. al.](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Deep_Contextual_Attention_for_Human-Object_Interaction_Detection_ICCV_2019_paper.pdf)| ICCV2019|47.3|
|[UniDet](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600494.pdf)|ECCV2020|47.5|
|[Interactiveness](https://arxiv.org/pdf/1811.08264.pdf)| CVPR2019 | 47.8| 
|[Lin et. al](https://www.ijcai.org/Proceedings/2020/0154.pdf)|IJCAI2020|48.1|
|[VCL](https://github.com/zhihou7/VCL)|ECCV2020|48.3|
|[Zhou et. al.](https://arxiv.org/pdf/2003.04262.pdf) |CVPR2020|48.9|
|[In-GraphNet](https://arxiv.org/pdf/2007.06925.pdf)|IJCAI-PRICAI 2020|48.9|
|[Interactiveness-optimized](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network)| CVPR2019 | 49.0|
|[TIN-PAMI](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network)|TAPMI2021|49.1|
|[IP-Net](https://arxiv.org/pdf/2003.14023.pdf)|CVPR2020|51.0|
|[DRG](https://github.com/vt-vl-lab/DRG)|ECCV2020|51.0|
|[VSGNet](https://arxiv.org/pdf/2003.05541.pdf)|CVPR2020|51.8|
|[PMN](https://github.com/birlrobotics/PMN)|arXiv|51.8|
|[PMFNet](https://arxiv.org/pdf/1909.08453.pdf)|ICCV2019|52.0|
|[Liu et.al.](https://arxiv.org/pdf/2105.03089.pdf)|arXiv|52.28|
|[FCL](https://github.com/zhihou7/FCL)|CVPR2021|52.35|
|[PD-Net](https://github.com/MuchHair/PD-Net)|ECCV2020|52.6|
|[Wang et.al.](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620239.pdf)|ECCV2020|52.7|
|[PFNet](https://link.springer.com/content/pdf/10.1007/s41095-020-0188-2.pdf)|CVM|52.8|
|[Zou et al.](https://github.com/bbepoch/HoiTransformer)|CVPR2021|52.9|
|[SIGN](https://ieeexplore.ieee.org/ielx7/9099125/9102711/09102755.pdf)|ICME2020|53.1|
|[ACP](https://github.com/Dong-JinKim/ActionCooccurrencePriors/)|ECCV2020|52.98 (53.23)|
|[FCMNet](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590239.pdf)|ECCV2020|53.1|
|[ConsNet](https://arxiv.org/pdf/2008.06254.pdf)|ACMMM2020|53.2|
|[IDN](https://github.com/DirtyHarryLYL/HAKE-Action-Torch/tree/IDN-(Integrating-Decomposing-Network))|NeurIPS2020|53.3|
|[OSGNet](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9360596)|IEEE Access|53.43|
|[SABRA-Res50](https://arxiv.org/pdf/2012.12510.pdf)| arXiv| 53.57|
|[IPGN](https://ieeexplore.ieee.org/document/9489275)|TIP2021|53.79|
|[AS-Net](https://github.com/yoyomimi/AS-Net)|CVPR2021|53.9|
|[RR-Net](https://arxiv.org/pdf/2104.15015.pdf)|arXiv|54.2|
|[SCG](https://github.com/fredzzhang/spatially-conditioned-graphs)|arXiv|54.2|
|[SABRA-Res50FPN](https://arxiv.org/pdf/2012.12510.pdf)| arXiv| 54.69|
|[GGNet](https://github.com/SherlockHolmes221/GGNet)|CVPR2021|54.7|
|[MLCNet](https://dl.acm.org/doi/pdf/10.1145/3372278.3390671)| ICMR2020|55.2|
|[HOTR](https://github.com/kakaobrain/HOTR)|CVPR2021|55.2|
|[DIRV](https://arxiv.org/pdf/2010.01005.pdf)|AAAI2021|56.1|
|[SABRA-Res152](https://arxiv.org/pdf/2012.12510.pdf)| arXiv| 56.62|
|[GTNet](https://github.com/UCSB-VRL/GTNet)|arXiv|58.29|
|[QPIC-Res101](https://github.com/hitachi-rd-cv/qpic)|CVPR2021|58.3|
|[QPIC-Res50](https://github.com/hitachi-rd-cv/qpic)|CVPR2021| 58.8|
|[CDN](https://arxiv.org/pdf/2108.05077.pdf)|arXiv|**63.91**|

#### 2) Enhanced with HAKE:
|Method| Pub | AP(role) |
|:---:|:---:|:---:|
|[iCAN](https://arxiv.org/pdf/1808.10437.pdf)| CVPR2019 | 45.3| 
|[iCAN + HAKE-Large](https://github.com/DirtyHarryLYL/HAKE-Action/tree/Instance-level-HAKE-Action) (transfer learning)| CVPR2020 | 49.2 (**+3.9**)|
|[Interactiveness](https://arxiv.org/pdf/1811.08264.pdf)| CVPR2019 | 47.8| 
|[Interactiveness + HAKE-Large](https://github.com/DirtyHarryLYL/HAKE-Action/tree/Instance-level-HAKE-Action) (transfer learning)| CVPR2020 | 51.0 (**+3.2**)|

### [HOI-COCO](https://github.com/zhihou7/HOI-CL): 
based on V-COCO

| Method | Pub | Full | Seen | Unseen|
|:---:|:---:|:---:|:---:|:---:|
|[VCL](https://github.com/zhihou7/VCL)|ECCV2020|23.53 |8.29| 35.36|
|[ATL(w/ affordance)](https://github.com/zhihou7/HOI-CL)|CVPR2021|23.40 |8.01 |35.34|


### HICO

#### 1) Default
|Method| mAP |
|:---:|:---:|
[R\*CNN](https://arxiv.org/pdf/1505.01197.pdf) | 28.5 |
[Girdhar et.al.](https://arxiv.org/pdf/1711.01467.pdf) |34.6|
[Mallya et.al.](https://arxiv.org/pdf/1604.04808.pdf) |36.1|
[Pairwise](http://openaccess.thecvf.com/content_ECCV_2018/papers/Haoshu_Fang_Pairwise_Body-Part_Attention_ECCV_2018_paper.pdf) |39.9| 
[DEFR-base](https://arxiv.org/pdf/2107.13083.pdf)|44.1|
[DEFR-CLIP](https://arxiv.org/pdf/2107.13083.pdf)|**60.5**|

#### 2) Enhanced with HAKE:
|Method| mAP |
|:---:|:---:|
[Mallya et.al.](https://arxiv.org/pdf/1604.04808.pdf) |36.1|
[Mallya et.al.+HAKE-HICO](https://github.com/DirtyHarryLYL/HAKE-Action/tree/Image-level-HAKE-Action) |45.0 (**+8.9**)|
[Pairwise](http://openaccess.thecvf.com/content_ECCV_2018/papers/Haoshu_Fang_Pairwise_Body-Part_Attention_ECCV_2018_paper.pdf) |39.9| 
[Pairwise+HAKE-HICO](https://github.com/DirtyHarryLYL/HAKE-Action/tree/Image-level-HAKE-Action)|45.9 (**+6.0**)|
[Pairwise+HAKE-Large](https://github.com/DirtyHarryLYL/HAKE-Action/tree/Image-level-HAKE-Action)|46.3 (**+6.4**)|
