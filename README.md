# 🧠 Skin Cancer Detection using ConvNeXt and Explainable AI

This project focuses on classifying skin lesions using the **ConvNeXt-Tiny** deep learning model, trained on the **HAM10000** dataset. The goal is to not only achieve high accuracy but also to ensure transparency and interpretability through explainable AI techniques.

---

## 📌 Features

- ✅ Skin lesion classification into **7 classes**
- ✅ Model based on **ConvNeXt-Tiny** (pretrained via `timm`)
- ✅ Integrated **explainability using Integrated Gradients**
- ✅ Visualizations: heatmaps, confusion matrix
- ✅ Evaluation with classification report (precision, recall, F1-score)

---

## 📊 Dataset

- **Name:** HAM10000 – Human Against Machine with 10000 training images
- **Source:** [Kaggle](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
- **Classes:**
  - `nv`: Melanocytic nevi
  - `mel`: Melanoma
  - `bkl`: Benign keratosis-like lesions
  - `bcc`: Basal cell carcinoma
  - `akiec`: Actinic keratoses
  - `vasc`: Vascular lesions
  - `df`: Dermatofibroma

---

## 🤝 Acknowledgements

- [HAM10000 Dataset](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
- [ConvNeXt](https://arxiv.org/abs/2201.03545)
- [Captum – Model Interpretability for PyTorch](https://captum.ai/)

---

## 👨‍💻 Author

**Megavarshan. A**  
Undergraduate Intern | AI Research  
SRM University

---

