
# ACKNOWLEDGMENT 
- This work was supported in part by the Center for Research, Innovation, and Transformation of Green University of Bangladesh.
# Paper Link 
 -https://ieeexplore.ieee.org/document/10464453
# Dataset Link 
- https://www.kaggle.com/datasets/mizanurrahmanrafi/mixed-color-rose-flower-dataset

# Classification of Mixed Color Rose Types Using Convolutional Neural Network

📄 *Published in:* 2023 5th International Conference on Sustainable Technologies for Industry 5.0 (STI)  
📅 *Date:* December 9, 2023  
📍 *Pages:* 1–5  
📚 *Publisher:* IEEE  
🔗 *Citations:* Cited by 2 (as of 2025)

---

## 🌹 Overview

This repository contains the official code and resources related to the research:

> **"Classification of Mixed Color Rose Types Using Convolutional Neural Network"**  
> *Authors:* Farhin Mujahid, Prothoma Khan Chowdhury, Tawheda Beenta Zaman, Md Mizanur Rahman, Md Tanzim Reza, Nazib Abdun Nasir, Montaser Abdul Quader, Mozdaher Abdul Quader

We created our own dataset of 538 photos of six different kinds of roses for the automated classification of roses. The dataset's images were collected from stock photography, Flickr, and Google Pictures. After that, we used the dataset to train our own effective CNN models, and we examined the outcomes using a number of different parameters. All things considered, our CNN model performs admirably when it comes to classifying the species present in the dataset. In order to investigate the variations in the outcomes, we also used the same experimental setup on the dataset's greyscale version in the following phase.
This study proposes an intelligent classification system to automatically identify rose flower species—especially *mixed-color* variants—using Convolutional Neural Networks (CNN). This tool removes the dependency on manual identification, providing a practical solution for botanical research, automated gardening, and ornamental plant monitoring. 

---

## 🎯 Objective

- To classify visually similar and mixed-color rose species.
- To automate flower species recognition with high accuracy using image-based deep learning.
- To support non-expert users in identifying roses without requiring expert botanical knowledge.

---

## 🌸 Targeted Rose Species

We classified the following **six mixed-color rose types**:

1. 🌺 **Pink-Red Rose**  
2. 🌈 **Rainbow Rose**  
3. 💎 **Neil Diamond**  
4. 🌼 **Graham Thomas**  
5. 🪄 **Abracadabra Rose**  
6. 🌹 **Double Delight Rose**

---

## 🧠 Methodology

- Utilized a **Convolutional Neural Network (CNN)** based deep learning model
- Created a **custom rose image dataset** with labeled images across six categories
- Applied **data augmentation** techniques to increase generalizability
- Evaluated model performance using accuracy, precision, recall, and confusion matrix

---

## 📊 Results Summary

| Metric       | Value (Approx.) |
|--------------|-----------------|
| Accuracy     | 91%             |
| Precision    | 89%             |
| Recall       | 90%             |
| F1-Score     | 89.5%           |

The model demonstrated strong performance in distinguishing between visually complex rose types with subtle color differences.

---

## 🗂️ Repository Structure

```bash
├── dataset/                 # Labeled rose images per category
├── model/                   # CNN architecture and trained weights
├── preprocessing/           # Scripts for data augmentation and preparation
├── notebooks/               # Jupyter notebooks for training and evaluation
├── results/                 # Visual results, confusion matrices, sample predictions
├── paper/                   # Published paper PDF and citation details
└── README.md                # Project description and documentation

