---
title: ""
permalink: /experience/
author_profile: true
---

# Work Experiences
## Siemens Healthineers 
**Senior Research Engineer** (Mar 2023 - Present) - Bangalore, India 
- Developed a semantic segmentation pipeline for calculating **tumor-stroma ratio (TSR)** of histopathological whole slide images (WSI) for breast cancer prognosis based on **DeepLabV3+** with a **ResNet50** backbone. Optimized pipeline using ONNX, network pruning, mixed-precision quantization, color normalization, and background separation, enabling fast and accurate inference on consumer GPU. Achieved Dice co-efficient of **0.85** and IoU of **0.63**. Collaborating hospital partners validated model accuracy and performance on real-world WSIs, leading to further research on other prognostic factors for breast cancer.

- Introduced a novel algorithm for detection of **semantically uncertain regions** in WSIs based on ensemble model
divergence, enabling minimal-input feedback loop for active model learning.

- Led a team to migrate the MI service analytics tool from full-text SQL search to a language model-based **semantic search**. Developed custom API using Python, BERT, Milvus VectorDB, and fastAPI, and deployed backend on AWS
cloud, leading to savings of **$20,000** per annum and onboarding of new modalities.

- Developed an unsupervised **topic modeling** method based on BERT and HDBSCAN and created a Power BI dashboard to identify semantic and domain-relevant failure modes, leading to **redesign of autoQC** sub-component in SPECT.

**Skills:** Keras · PyTorch · ONNX · Python · Convolutional Neural Networks (CNN) · Natural Language Processing (NLP) · Unsupervised Learning · REST APIs 

**Research Engineer** (Dec 2021 - Feb 2023) - Bangalore, India 
- Developed a novel set of image features for a machine learning classification model and an unsupervised ROI-agnostic artifact segmentation model for **automated grading** of SPECT Gamma Camera QC images. Improved F1-score from **0.45** to **0.75** compared to baseline uniformity metrics. The work resulted in an invention disclosure, leading to the successful patent filing for the automated grading algorithm.

- Developed an unsupervised method based on Word2Vec embeddings and DBSCAN for **clustering domain-relevant words** into a thesaurus to significantly improve the baseline full-text SQL search of the service analytics tool for historical PET/SPECT service tickets. Eliminated the need for manual effort in creating domain-relevant thesaurus and increased cluster count from **15** to **346**, thus aiding service engineers with more accurate and relevant search results.

- Developed an end-to-end information extraction pipeline for PET/SPECT service tickets using a roBERTa-based Entity Recognition model, enhancing search results by extracting **Cause-Action phrases**, thus improving granularity, searchability, and readability. Increased ticket coverage from **14%** to **52%** compared to the earlier POS tagging model.

**Skills:** Deep Learning · Machine Learning · Natural Language Processing (NLP) · Image Processing ·  Python 

## Cognizant Technolgy Solutions 
**Programmer Analyst Trainee** (Nov 2020 - Sep 2021) - Kolkata, India 
- Developed and executed automated test scripts using Java, Selenium, REST API, HTML, CSS, and JavaScript to ensure quality of API and web applications. Contributed to development of the automation testing framework. 

- Actively participated in the requirements analysis and test development process. Worked closely with developers to identify and resolve defects.

**Skills:** Java · Selenium · REST APIs · HTML · JavaScript · CSS

---

# Internships

## Plant Vision Lab, University of Nebraska-Lincoln
**Research Internship** (Jul 2021 - Dec 2021) - Remote   
under <a href="https://snr.unl.edu/aboutus/who/people/faculty-member.aspx?pid=2369" target="_blank">Prof. Sruti Das Choudhary</a>, 
<a href="https://computing.unl.edu/ashok-samal/" target="_blank">Prof. Ashok Samal</a>

Developed two novel algorithms to predict onset of drought stress in cotton plants using **Dynamic Time Warping (DTW)** on computed phenotypes and leveraged **1D-CNN**-based network for predicting propagation of temporal stress using hyperspectral imagery. Predicted stressed pixels showed F1-score of **0.98** and average Pearson correlation coefficient of **-0.85** with soil water content. The work led to a publication in a peer-reviewed journal.

## Sensordrops Networks Pvt. Ltd, IIT Kharagpur
**Research Internship** (Jul 2021 - Dec 2021) - Remote   
under <a href="https://scholar.google.com/citations?user=FSlsUEwAAAAJ&hl=en" target="_blank">Dr. Rituparna Saha</a>, 
<a href="https://cse.iitkgp.ac.in/%7Esmisra/" target="_blank">Prof. Sudip Misra</a>

Introduced a novel algorithm for **Federated Learning in non-IID datasets** based on K-Means clustering of client data statistics. Surpassed accuracy of baseline Federated Averaging (FedAvg) by **2%** and reduced aggregation time by **67%** compared to baseline clustering on local weights. Currently working towards a publication.

## AI Lab, Jadavpur University
**Summer Internship** (May - Jul, 2019) - Kolkata, WB   
under <a href="https://scholar.google.co.in/citations?user=s1F23CAAAAAJ&hl=en" target="_blank">Prof. Amit Konar</a>, INAE Fellow

Project conducted under **INAE** Student Mentoring Program under INAE Fellows. Programmed a 6-DOF Robotic Arm from Kinova (JACO) in C#. Developed an **Obstacle Avoidance and Trajectory Planning system** for 3-DOF Robotic Arms based on the A* Heuristic Search algorithm and kinematics. Verified the algorithm using simulations on MATLAB and submitted a technical report to INAE, upon which the stipend was disbursed.


## IoT Lab, IRPE, University of Calcutta
**Summer Internship** (May - Jul, 2018) - Kolkata, WB   
under <a href="https://scholar.google.co.in/citations?user=dkbXW_UAAAAJ&hl=en" target="_blank">S. Basu</a>, 
<a href="https://drsoumyapandit.in/" target="_blank">Prof. S. Pandit</a>, 
<a href="https://scholar.google.co.in/citations?hl=en&user=of2_-JsAAAAJ" target="_blank">Prof. S. Barman (Mandal)</a>

Implemented an **IoT-based health monitoring system** using Arduino UNO, different non-invasive sensors, Wi-Fi module, and Thingspeak IoT platform to read health parameters, display it on an LCD, and transmit data to cloud for secure storage and future analysis. The work resulted in a conference paper that was presented at the International Conference on Computational Intelligence in Pattern Recognition (CIPR), 2019, IIEST Shibpur.