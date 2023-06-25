# [Project-List](https://github.com/xiaochengfuhuo/Project-List)
It is the page that records my projects. If you are interested in my project or have some ideas, you are welcome to make a discussion with me.
## MGTCF: Multi-Generator Tropical Cyclone Forecasting with Heterogeneous Meteorological Data
This work was accepted by AAAI (2023) and the paper will be published in April 2023. [[code]](https://github.com/Zjut-MultimediaPlus/MGTCF)
### Abstract
Accurate forecasting of tropical cyclone (TC) plays a critical role in the prevention and defense of TC disasters. We
must explore a more accurate method for TC prediction.
Deep learning methods are increasingly being implemented
to make TC prediction more accurate. However, most existing methods lack a generic framework for adapting heterogeneous meteorological data 
and do not focus on the importance of the environment. 
Therefore, we propose a **M**ulti-**G**enerator **T**ropical **C**yclone **F**orecasting model (MGTCF),
a generic, extensible, multi-modal TC prediction model with
the key modules of Generator Chooser Network (GC-Net)
and Environment Net (Env-Net). The proposed method can
utilize heterogeneous meteorologic data efficiently and mine
environmental factors. In addition, the Multi-generator with
Generator Chooser Net is proposed to tackle the drawbacks
of single-generator TC prediction methods: the prediction of
undesired out-of-distribution samples and the problems stemming from insufficient learning ability. 
To prove the effectiveness of MGTCF, we conduct extensive experiments on the
China Meteorological Administration Tropical Cyclone Best
Track Dataset. MGTCF obtains better performance compared with other deep learning methods and outperforms
the official prediction method of the China Central Meteorological Observatory in most indexes.
## MMSTN: A multi-modal spatial-temporal network for tropical cyclone short-term prediction
This work was accepted by Geophysical Research Letters (2022). [[Code]](https://github.com/Zjut-MultimediaPlus/MMSTN) 
[[Paper]](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021GL096898)
### Abstract
Forecasting the trajectory and intensity of tropical cyclones (TCs) is important in disaster 
mitigation as TC usually causes huge damages. However, it remains a substantial challenge due to the limited 
understanding of TC complexity. Still, TCs have been observed and recorded for several decades, and so can be 
predicted if viewed as a spatial-temporal prediction problem with a huge amount of existing data. We propose 
a novel TC trajectory and intensity short-term prediction method: Multi-Modal Spatial-temporal Networks 
(MMSTN). It not only predicts the TC's central pressure, winds, and the location of its center, but also forecasts 
the TC's varied possible tendencies. Experiments were conducted on the China Meteorological Administration 
Tropical Cyclone Best Track Dataset. Experimental results show that the proposed MMSTN outperformed 
state-of-the-art methods as well as the official prediction method of the China Central Meteorological 
Observatory, in intensity prediction and 6 hr trajectory prediction.

## Tropical Cyclones Tracking Based on Satellite Cloud Images: Database and Comprehensive Study
This work was accepted by MMM (2021). [[Dataset]](https://github.com/Zjut-MultimediaPlus/TCTSCI) 
[[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-67835-7_2) 
### Abstract
The tropical cyclone is one of disaster weather that cause
serious damages for human community. It is necessary to forecast the
tropical cyclone efficiently and accurately for reducing the loss caused by
tropical cyclones. With the development of computer vision and satellite
technology, high quality meteorological data can be got and advanced
technologies have been proposed in visual tracking domain. This makes
it possible to develop algorithms to do the automatic tropical cyclone
tracking which plays a critical role in tropical cyclone forecast. In this
paper, we present a novel database for Typical Cyclone Tracking based
on Satellite Cloud Image, called TCTSCI. To the best of our knowledge,
TCTSCI is the first satellite cloud image database of tropical cyclone
tracking. It consists of 28 video sequences and totally 3,432 frames with
6001×6001 pixels. It includes tropical cyclones of five different intensities
distributing in 2019. Each frame is scientifically inspected and labeled
with the authoritative tropical cyclone data. Besides, to encourage and
facilitate research of multimodal methods for tropical cyclone tracking,
TCTSCI provides not only visual bounding box annotations but multimodal meteorological data of tropical cyclones. 
We evaluate 11 state-of-the-art and widely used trackers by using OPE and EAO metrics and
analyze the challenges on TCTSCI for these trackers.

## Res2-UNeXt: a novel deep learning framework for few-shot cell image segmentation
This work was accepted by Multimedia Tools and Applications (2021). [[Paper]](https://link.springer.com/article/10.1007/s11042-021-10536-5) 
### Abstract
Recently, developing more accurate and more efficient deep learning algorithms for medical
images segmentation attracts more and more attentions of researchers. Most of methods
increase the depth of the network to replace with acquiring multi-information. The costs of
training images annotation are too expensive to label by hand. In this paper, we propose
a multi-scale and better performance deep architecture for medical image segmentation,
named Res2-UNeXt. Our architecture is an encoder-decoder network with Res2XBlocks.
The Res2XBlocks aim at acquiring multi-scale information better in images. To cooperate
with Res2-UNeXt, we put forward a simple and efficient method of data augmentation.
The data augmentation method, based on the process of cell movement and deformation,
has biological implications in away. We evaluate Res2-UNeXt in comparison with recent
variants of U-Net: UNet++, CE-Net and LadderNet and the method that different from U-
Net architecture: FCN and DFANet on the dataset of ISBI cell tracking challenge 2019
via four different cell images. The experimental results demonstrate that Res2-UNeXt can
achieve better performance than both recent variants of U-Net and non-U-Net architecture
methods. Besides, the proposed architecture and the data augmentation method have been
proven efficiently by the ablation experiments.
