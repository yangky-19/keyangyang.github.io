---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

Training neural networks for super-resolution MRI using noisy high-resolution reference data
-----
8/2022 - Present   

**Advisor: [Qiyuan Tian](https://www.nmr.mgh.harvard.edu/~qt012/index.html), Instructor in Radiology, Martinos Center for Biomedical Imaging, Massachusetts General Hospital, Harvard Medical School**
* Designed and conducted both simulation and empirical data experiments and demonstrated comparable effectiveness in the training with noisy high-resolution reference data and clean data in super-resolution tasks;
* Simulated the low-resolution image volume and noisy high-resolution image volume, and realized the neural network MU-Net based on Tensorflow; 
* Proposed a deep learning-based super-resolution method that does not require high-SNR reference data and can potentially reduce the tedious and repeated collection to acquire clean high-resolution MRI images. 
* Currently working on paper writing.

High-frequency oscillations detection using Transformer-based neural network
-----

6/2022 - Present   

**Advisor: [Dominique Duncan](https://sites.usc.edu/duncanlab/), Assistant Professor of Neurology, Neuroscience, and Biomedical Engineering, University of Southern California**
* Designed independently a Transformer-based neural network for the EEG high-frequency oscillation (HFO) detection;
* Pre-processed EEG signals using Matlab, added a linear projection layer before the Transformer, and redesigned the Encoder-Decoder layer to give specific detections of HFO segments; 
* Obtained preliminary results that show the outperformance over the four automatic detectors that are widely used in labs and the previously proposed CNN-based detector; 
* Currently working on further model optimization and validation.

CNN model for sustained attention level evaluation using EEG
-----

09/2021 – 12/2021   

**Advisor: [Milin Zhang](https://www.ee.tsinghua.edu.cn/en/info/1068/1297.htm), Associate Professor of Electronic Engineering, Tsinghua University**
* Built a CNN for attention level classification, consisting of four convolutional blocks, a GAP layer, and a linear layer; 
* Constructed each convolutional block with a 1-d convolutional layer, a 1-d batch normalization (BN) layer, and a rectified linear unit (ReLU) layer;
* Optimized convolutional blocks’ structure and achieved a subject-independent (SI) accuracy of 90%, which is reliable for the attention evaluation application.
