# TML25_A2_15
# TML ASSIGNMENT 2  
## Model Stealing in Supervised Learning

**Team:** 15  
**Members:** Hina Lilaram, Javed Akhtar

---

### Overview

This repository contains our solution for Assignment 2 of the Trustworthy Machine Learning course, focused on **Model Stealing under the B4B (Bucks-for-Buckets) defense**. The objective is to replicate the victim encoder by querying its API and training a surrogate model to minimize the L2 distance between the surrogate’s and the victim’s output representations.

---

### Files and Descriptions

- **test.ipynb**  
  This is the **main implementation file**. It contains the complete end-to-end pipeline for model stealing as per the assignment requirements. The notebook covers:
  - Loading and preprocessing the dataset  
  - Querying the protected victim encoder API  
  - Building and training the stolen model (CNN encoder)  
  - Evaluating and exporting the model for submission  

- **test_improved.ipynb**  
  This notebook builds on the original pipeline, introducing **advanced features and optimizations** to improve the model stealing attack, such as:
  - Stronger and B4B-mimicking data augmentations  
  - Enhanced query strategies  
  - Improved model architecture and loss functions  
  Unfortunately, this notebook could **not be fully executed due to server issues** encountered during the assignment period. However, the included code documents additional ideas for improving model stealing performance.

- **TML25_A2_15_report.pdf**
  This is the report file.

---

*For any questions or clarifications, please contact either team member.*
