# 🎨 Indonesian Batik Classification

Classifying traditional Indonesian **batik** patterns from images — comparing a **CNN trained from scratch** against **transfer learning with DenseNet121**.

🎥 **Demo video:** https://youtu.be/j7sQkDjdd-w

---

## 🎯 Goal

Batik motifs are visually intricate and easy to confuse. This project measures how much **transfer learning** helps on a small batik dataset versus training a convolutional network from the ground up.

## 🧪 Approach

1. **CNN from scratch** — a custom convolutional architecture trained directly on the batik images.
2. **Transfer learning** — **DenseNet121** pretrained on ImageNet, fine-tuned on the batik classes.

## 📊 Results

| Model | Best Validation Accuracy | Test Accuracy |
| --- | --- | --- |
| CNN from scratch | ~60% | — |
| **DenseNet121 (transfer learning)** | **~87%** | **80%** |

> Transfer learning gave a large accuracy jump over the from-scratch CNN on a limited dataset — confirming the value of pretrained visual features for fine-grained pattern recognition.

## 📁 Files

- `Scratch and DenseNet 121 .ipynb` — full training & evaluation notebook
- `Presentation deep learning AOL.pdf` — project presentation

## 🛠️ Tech stack

TensorFlow / Keras · DenseNet121 · NumPy · Matplotlib
