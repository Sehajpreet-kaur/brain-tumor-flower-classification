# Brain Tumor Detection and Flower Classification using CNN-based Transfer Learning.

# Deep Learning Project Summaries

This repository presents high-level summaries and evaluation results of two deep learning projects:

1. **Brain Tumor Detection using Transfer Learning**
2. **Five-Class Flower Classification using CNNs**

> **Note**: This repository contains **only project descriptions, performance metrics, and result summaries**. No source code or datasets are included.

---

## Project 1: Brain Tumor Detection Using Deep Learning

### Objective
To classify brain MRI scans into four categories: **Glioma**, **Meningioma**, **Pituitary Tumor**, and **No Tumor**, using pre-trained deep learning models through **transfer learning**.

### Models Evaluated
- VGG16 (Best performer)
- VGG19
- DenseNet169
- DenseNet201
- InceptionV3

### Results (Overall)

| Model         | Accuracy (%) | Precision (%) | Recall (%) | F1 Score (%) | MCC (%)   |
|---------------|--------------|----------------|-------------|---------------|-----------|
| **VGG16**     | **99.91**    | **99.91**      | **99.91**   | **99.91**     | **99.87** |
| DenseNet169   | 99.83        | 99.83          | 99.83       | 99.83         | 99.77     |
| DenseNet201   | 99.77        | 99.77          | 99.77       | 99.77         | 99.69     |
| InceptionV3   | 99.76        | 99.76          | 99.76       | 99.76         | 99.67     |
| VGG19         | 99.30        | 99.31          | 99.30       | 99.30         | 99.07     |

### Class-wise Insights
- **VGG16** achieved 100% precision and recall on Glioma.
- **DenseNet169** showed perfect detection for non-tumor scans.
- **All models** achieved >99% on average for all metrics.

### Additional Highlights
- Visualizations include: training/validation curves, confusion matrix, and ROC-AUC scores.
- ROC-AUC for best model (VGG16): ~1.0 across all classes.
- Compared with prior literature, this approach demonstrated **state-of-the-art results**.

---

## Project 2: 5 Flower Classification Using CNNs

### 📋 Objective
To classify images of five flower types—**Tulip, Lily, Lotus, Sunflower, Orchid**—using pre-trained convolutional models.

### 🔧 Models Evaluated
- ResNet101 (Best performer)
- DenseNet169
- DenseNet201
- ResNet50
- InceptionV3

### 📊 Results (Overall)

| Model         | Accuracy (%) | Precision (%) | Recall (%) | F1 Score (%) | MCC (%)  |
|---------------|--------------|----------------|-------------|---------------|----------|
| **ResNet101** | **96.40**    | **96.44**      | **96.40**   | **96.41**     | **95.50**|
| DenseNet169   | 95.72        | 96.02          | 95.72       | 95.76         | 94.71    |
| DenseNet201   | 95.37        | 95.72          | 95.72       | 95.37         | 94.30    |
| InceptionV3   | 95.24        | 95.40          | 95.24       | 95.25         | 94.08    |
| ResNet50      | 93.95        | 94.33          | 93.95       | 93.97         | 92.52    |

### 🔍 Class-wise Insights
- **ResNet101** was most consistent across all flower types.
- **DenseNet169** excelled in Tulip and Orchid detection.
- AUC scores for all classes were above 0.99, indicating high reliability.

---

## 🔎 Why No Code?

This repository is intended as a **documentation and evaluation showcase** only. The focus is on presenting:
- Research goals
- Model architectures used
- Performance benchmarks
- Comparative analysis with related studies

The full implementation, dataset handling, and training pipeline are **not shared** to maintain academic and data policy compliance.

---

## 📄 Additional Files

- 📑 `requirements.txt` – lists Python libraries used (for reproducibility).
- 🖼️ Images & figures (optional) – model performance charts (if added).

---

## 📬 Contact

For academic collaboration or inquiries about the methodology, feel free to connect via GitHub Issues or email (if applicable).
