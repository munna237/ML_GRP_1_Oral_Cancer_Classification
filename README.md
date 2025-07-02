# 🧠 Oral Cancer Detection using Self-Supervised Learning

This project implements a deep learning pipeline to detect **oral cancer** using **self-supervised learning (SSL)**. SSL allows us to pretrain models on large volumes of **unlabeled medical images**, reducing the need for costly manual annotations. We then fine-tune the pretrained model on a small set of labeled samples to accurately classify cancerous and non-cancerous cases.

---

## 📌 Objectives

- Utilize self-supervised learning (SSL) to extract meaningful features from oral cavity images.
- Fine-tune the SSL model using limited labeled data.
- Compare performance with standard supervised learning approaches.

---

## 📂 Dataset

- **Source**: (https://www.kaggle.com/datasets/obulisainaren/multi-cancer)
- **Image Type**: [Clinical RGB images]
- **Preprocessing**:
  - Resizing to 224x224
  - Normalization
  - Augmentation (horizontal flip, color jitter, etc.)

> **Note**: If your dataset is private, please mention that data access is restricted.

---

## 🧪 Methodology

### 🔄 Self-Supervised Pretraining
- **Framework**: [TBA]
- **Architecture**: [e.g., ResNet-50, Vision Transformer]
- **Task**: Learn representations from unlabeled images via contrastive or masked-image learning.

### 🎓 Supervised Fine-Tuning
- Fine-tune pretrained model on a small labeled subset.
- **Loss Function**: Cross-Entropy / Focal Loss
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, AUC

---

## 🧾 Project Structure

oral-cancer-ssl/
├── data/ # Raw and processed datasets
├── pretraining/ # Self-supervised learning scripts
├── finetuning/ # Supervised fine-tuning scripts
├── models/ # Model architectures
├── notebooks/ # Jupyter notebooks for experiments
├── utils/ # Utility scripts
├── results/ # Metrics, plots, and outputs
└── README.md # Project overview

## 🤝 Acknowledgements

I would like to express my sincere gratitude to my supervisor:

**[Dr. Raihan Ul Islam](https://scholar.google.com/citations?user=mjWULyIAAAAJ&hl=en)**  
Associate Professor  
Department of Computer Science & Engineering  
📧 raihan.islam@ewubd.edu

---

Special thanks to the developers and maintainers of open-source self-supervised learning libraries and publicly available medical imaging datasets that made this research possible.

**Libraries/Frameworks Used:**
- PyTorch
- PyTorch Lightning
- scikit-learn
- OpenCV
- matplotlib


