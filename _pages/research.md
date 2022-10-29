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

<div>			
    <img src="/keyangyang.github.io/images/figure1.png"
         width=800>
    <br>
    <b>Figure 1. Neural network and training data.</b> SRNHR uses a modified 3D U-Net (MU-Net) composed of 3D convolution layers and ReLU activation layers with skip connection. MU-Net maps the input up-sampled low-resolution image volume to the residual volume between the input and output noisy high-resolution image volume (a). Exemplary coronal image slices from up-sampled low-resolution (b, i), high-SNR high-resolution (b, ii), and simulated noisy high-resolution images (b, ii-vi, with different standard deviations of noise) of a representative HCP subject are shown with enlarged views.
</div>    
<br>   
   
<div>			
    <img src="/keyangyang.github.io/images/figure2.png"
         width=800>
    <br>
    <b>Figure 2. Simulation image results.</b> Exemplary coronal image slices from native high-SNR high-resolution (a, i) and up-sampled low-resolution data (a, ii), and super-resolution results from neural networks trained with noisy high-resolution images (a, iii-vii, with different standard deviations of noise) are shown with enlarged views (b). The difference maps (c, d) depict the similarity compared to the native high-SNR high-resolution image. Mean absolute error (MAE), peak SNR (PSNR) and structural similarity index (SSIM) are listed to quantify the similarity (a).
</div>    
<br>   
   
<div>			
    <img src="/keyangyang.github.io/images/figure3.png"
         width=800>
    <br>
    <b>Figure 3. Simulation image similarity metrics.</b> Group mean (± standard deviation) of the whole-brain averaged mean absolute error (MAE) (a), peak SNR (PSNR) (b), and structural similarity index (SSIM) (c) of the up-sampled low-resolution images (usp) and results from neural networks trained with high-SNR and noisy high-resolution images across 15 evaluation subjects. Detailed values are listed in the table (d).
</div>    
<br>   
   
<div>			
    <img src="/keyangyang.github.io/images/figure4.png"
         width=800>
    <br>
    <b>Figure 4. Empirical image results.</b> Exemplary axial image slices from 10-repetition averaged high-resolution (a, i), single-repetition high-resolution (a, ii), up-sampled low-resolution images (a, iii), and super-resolution results from neural networks trained with 10-repetition averaged and single-repetition high-resolution images from another four subjects are shown with enlarged views (b). The difference maps (c, d) depict the similarity compared to the 10-repetition averaged high-resolution image. Mean absolute error (MAE), peak SNR (PSNR) and structural similarity index (SSIM) are listed to quantify the similarity (a).
</div>   
<br>   
   
<div>			
    <img src="/keyangyang.github.io/images/figure5.png"
         width=800>
    <br>
    <b>Figure 5. Empirical image similarity metrics.</b> Group mean (± standard deviation) of the whole-brain averaged mean absolute error (MAE) (a), peak SNR (PSNR) (b), and structural similarity index (SSIM) (c) of the up-sampled low-resolution images and super-resolution results of neural networks trained with 10-repetition averaged and single-repetition high-resolution images across five evaluation subjects. Detailed values are shown in the table (d). 
</div>    
<br>

High-frequency oscillations detection using Transformer-based neural network
-----

6/2022 - Present   

**Advisor: [Dominique Duncan](https://sites.usc.edu/duncanlab/), Assistant Professor of Neurology, Neuroscience, and Biomedical Engineering, University of Southern California**
* Designed independently a Transformer-based neural network for the EEG high-frequency oscillation (HFO) detection;
* Pre-processed EEG signals using Matlab, added a linear projection layer before the Transformer, and redesigned the Encoder-Decoder layer to give specific detections of HFO segments; 
* Obtained preliminary results that show the outperformance over the four automatic detectors that are widely used in labs and the previously proposed CNN-based detector; 
* Currently working on further model optimization and validation.

<div>			
    <img src="/keyangyang.github.io/images/figure6.png"
         width=800>
    <br>
    <b>Figure.</b> Framework of Transformer-based HFO detection. 
</div>    
<br>   
   
CNN model for sustained attention level evaluation using EEG
-----

09/2021 – 12/2021   

**Advisor: [Milin Zhang](https://www.ee.tsinghua.edu.cn/en/info/1068/1297.htm), Associate Professor of Electronic Engineering, Tsinghua University**
* Built a CNN for attention level classification, consisting of four convolutional blocks, a GAP layer, and a linear layer; 
* Constructed each convolutional block with a 1-d convolutional layer, a 1-d batch normalization (BN) layer, and a rectified linear unit (ReLU) layer;
* Optimized convolutional blocks’ structure and achieved a subject-independent (SI) accuracy of 90%, which is reliable for the attention evaluation application.

<div>			
    <img src="/keyangyang.github.io/images/figure7.png"
         width=800>
    <br>
    <b>Figure.</b> Design of the SaleNet. <i><a href="https://arxiv.org/abs/2209.01386">SaleNet: A low-power end-to-end CNN accelerator for sustained attention level evaluation using EEG</a></i>
</div> 
   
