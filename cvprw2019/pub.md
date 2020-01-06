# Directing DNNs Attention for Facial Attribution Classification usingGradient-weighted Class Activation Mapping

Xi Yang, The University of Tokyo

Bojian Wu, SIAT

Issei Sato, The University of Tokyo

Takeo Igarashi, The University of Tokyo

## Abstract

Deep neural networks (DNNs) have a high accuracy on image classification tasks. However, DNNs trained by such dataset with co-occurrence bias may rely on wrong features while making decisions for classification. It will greatly affect the transferability of pre-trained DNNs.  In this paper,we propose an interactive method to direct classifiers paying attentions to the regions that are manually specified bythe users, in order to mitigate the influence of co-occurrence bias.  We test on CelebA dataset, the pre-trained AlexNet is fine-tuned to focus on the specific facial attributes based on the results of Grad-CAM.

![](image.png)

Examples from the CelebA dataset.  Grad-CAM shows that  a  pre-trained  DNN  ‘lipstick’  attribute  focuses  on  not  only the  mouth  region  but  also  on  the  eyes,  eyebrows,  and  other  regions (first row).  Our fine-tuned DNN focuses on the mouth only(second row). The predictive importance of various facial regions(high to low) is colorized blue to red.

## Download:

[PDF](https://arxiv.org/pdf/1905.00593.pdf  " ")

[Poster](cvpr19_poster.pdf " ")

## Acknowledgement

This work was supported by JST CREST Grant Number JPMJCR17A1, Japan.

## Bibtex

@InProceedings{Yang_2019_CVPR_Workshops,
author = {Yang, Xi and Wu, Bojian and Sato, Issei and Igarashi, Takeo},
title = {Directing DNNs Attention for Facial Attribution Classification using Gradient-weighted Class Activation Mapping},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
month = {June},
year = {2019}
}

