+++
date = "2015-09-06T22:04:14+01:00"
draft = false
title = "Surveys and Datasets"
url = "/Surveys and Datasets"
menu = "main"
+++

### Continual Object Detection Benchmark

In Verwimp et al. Neural Networks 2023, we introduce CLAD, a novel benchmark for continual learning focusing on realistic distribution shifts. The benchmark, built on top of Huawei's [SODA10M](https://soda-2d.github.io/index.html) autonomous driving dataset, comprises a classification (CLAD-C) and an object detection benchmark (CLAD-D). CLAD-C was built from a stream of chronological images, yielding smooth and realistic transitions in terms of domain (e.g. weather) and class distributions. CLAD-D is a domain incremental object detection benchmark, comprising 4 tasks associated with different environmental conditions. The CLAD benchmarks were released as part of the [Self-supervised Learning for Next-Generation Industry-level Autonomous Driving Challenge](https://sslad2021.github.io/pages/challenge.html) and top proposed methodologies are discussed in our paper. Code and details are available [here](https://github.com/VerwimpEli/CLAD).

----------

### Continual Learning Survey

In De Lange et al. PAMI 2021, we carried out a detailed analysis and survey of continual learning methodology for classification tasks. We thoroughly evaluated 11 state of the art methods and the influence of different model components against 4 baselines, on 3 benchmark datasets. Code and details are available [here](https://github.com/Mattdl/CLsurvey).

----------

### Brain Parcellation Survey

In Arslan et al. NeuroImage 2017, we provide a large-scale systematic comparison of more than 30 state-of-the-art connectivity-driven, anatomical, and random parcellation methods.
The preprint, as well as the code and data used for the survey are provided at [the dedicated webpage](https://biomedia.doc.ic.ac.uk/brain-parcellation-survey/).

----------

### Low-Grade Gliomas Database

<!---
<span class="imgleft">![](http://db-gliomas-gradeii.net/onewebstatic/4d21e472ca-Tumex3-eps-converted-to.png)</span>
-->

We have released the database used during my PhD for tumour segmentation and analysis. This is a set of 210 FLAIR MRI of different patients suffering from a diffuse Low Grade Glioma. All the images provided were acquired in a clinical setting, with varying quality and evolution of the disease. It results in a very challenging database for image processing tasks.  

The complete database can be found [here](https://figshare.com/articles/Diffuse_Low_grade_Glioma_Database/1550871) (NIFTI format)
