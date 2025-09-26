# ♻️ Recyclable Waste Classification

This repository contains an **image classification** project developed as part of the *Global AI Hub Bootcamp*.  
The goal is to **classify recyclable and household waste** into the correct categories using deep learning.

---

## 📌 Introduction
- **Dataset:** [Recyclable and Household Waste Classification Dataset](https://www.kaggle.com/datasets/alistairking/recyclable-and-household-waste-classification)
- **Classes:** 30 categories (~500 images per class)
- **Format:** All images are in `.png` format  
- **Model:** [EfficientNet-B0](https://arxiv.org/abs/1905.11946)
- **Techniques Used:**  
  - Data augmentation (Random crop, rotation, color jitter, horizontal flip)  
  - Transfer learning with fine-tuning  
  - Advanced methods: **MixUp**, **Label Smoothing**, **Cosine Annealing LR Scheduler**

> 📓 Technical explanations are provided directly inside the notebook  
> [`recyclable-waste-classification.ipynb`](./waste-classification.ipynb) with detailed markdown cells.

---

## 📊 Metrics
**Validation Accuracy:** ~84%  
**Test Accuracy:** ~83%

- ✅ Strong **generalization** thanks to augmentation  
- ⚡ Lightweight & efficient due to EfficientNet-B0 base  
- 🔎 **Confusion Matrix** used to analyze class-based performance

**Challenges:**  
- Some visually similar categories are hard to distinguish (e.g., `cardboard_boxes` vs `cardboard_packaging`).

---

## ✨ Extras
- 🖼️ **Grad-CAM** visualization to see which image regions the model focuses on.  
- ⚙️ **Hyperparameter Optimization (HPO):** tuned learning rate & weight decay for better performance.  

---

## 🚀 Conclusion & Future Work
- ✔️ Successfully classified recyclable waste using an **EfficientNet-B0** model with competitive accuracy.  
- 🔮 Future improvements:  
  - Try larger EfficientNet models (B3, B4).  
  - Deploy a real-time web demo (e.g., **Streamlit**).  
  - Extend the dataset to improve accuracy further.  

This project provides a **solid foundation for AI-powered environmental solutions** 🌱.

---

## 🔗 Links
- 📂 [Kaggle_Project]([https://www.kaggle.com/datasets/alistairking/recyclable-and-household-waste-classification](https://www.kaggle.com/code/mehmetselimdere/waste-classification))

