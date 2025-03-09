# 🩺 Multi-Modal AI for Chest X-Ray Diagnosis (CheXpert)

## 📌 Project Overview
This project develops a **multimodal AI** for **chest X-ray classification** by integrating **image features (CNN/Vision Transformers)** with **radiology reports (BERT/BioBERT)**. Inspired by **generalized zero-shot learning (GZSL)**, we use **feature disentanglement** to separate visual and textual domain knowledge, improving **multi-label disease classification** on the **CheXpert dataset**.

## 🔥 Key Features
- **🔗 Multi-Modal AI** → Combines **chest X-ray images** with **radiology reports**.
- **🖼️ Vision Backbone** → CNN, Vision Transformers (ViTs), Swin-Transformer.
- **📜 Language Backbone** → BERT, BioBERT, or ClinicalBERT for **radiology text embeddings**.
- **🆕 Zero-Shot & Few-Shot Learning** → Classifies unseen diseases without labeled samples.
- **🧠 Feature Disentanglement** → Learns **separate latent spaces** for images & text.
- **⚡ Contrastive Learning** → Uses **CLIP-like contrastive loss** for vision-text alignment.
- **📊 Explainability** → Visualizes model decisions with **GradCAM & Attention Maps**.

## 📂 Dataset
We use the **[CheXpert Dataset](https://stanfordmlgroup.github.io/competitions/chexpert/)**, which contains **chest X-rays and corresponding radiology reports** for multi-label classification.

## 📦 Installation
### 1️⃣ Clone the repository:
```bash
git clone https://github.com/yourusername/MultiModal-CheXpert.git
cd MultiModal-CheXpert
