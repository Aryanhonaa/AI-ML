# Deep Learning Projects

This repository contains two separate deep learning projects:

1. **Text Classification on Movie Reviews** using RNN, LSTM and GloVe embeddings  
2. **Brain Tumor Image Classification** using Baseline CNN, Deeper CNN, and Transfer Learning (InceptionV3)

---

## 1. Text Classification on Movie Reviews

### Overview
This project focuses on classifying movie reviews as positive or negative by using different recurrent neural network architectures and pretrained word embeddings.

### Models Used
- **RNN (Recurrent Neural Network)**
- **LSTM (Long Short-Term Memory)**
- **GloVe Word Embeddings** for improved word representation

### Dataset
- Movie reviews dataset (e.g., IMDb or any standard movie review dataset)

### Features
- Text preprocessing (tokenization, padding)
- Embedding layer initialized with pretrained GloVe vectors
- Comparison of RNN vs LSTM performance


# Brain Tumor Image Classification

This project aims to classify brain MRI images into tumor categories using convolutional neural networks (CNNs) with increasing complexity, including transfer learning with the InceptionV3 model.

---

## 🧠 Project Overview

Brain tumor classification is critical for early diagnosis and treatment. This project implements multiple CNN architectures to classify brain tumor images:

- **Baseline CNN:** A simple convolutional network to establish baseline performance.  
- **Deep CNN:** A deeper architecture with more convolutional layers for better feature extraction.  
- **InceptionV3 Transfer Learning:** Utilizes a pretrained InceptionV3 model fine-tuned on the brain tumor dataset for improved accuracy.

---

## 📂 Dataset

- Public brain tumor MRI dataset 
- Dataset contains labeled MRI images of different brain tumor types and normal brains.

---

## ⚙️ Features

- Image preprocessing: resizing, normalization, and data augmentation (rotation, flipping, zoom)  
- Model training with early stopping and learning rate scheduling  
- Evaluation metrics: accuracy, confusion matrix, classification report  
- Comparison of baseline, deep CNN, and transfer learning results

---
