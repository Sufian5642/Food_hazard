# 🍽️ Food Hazard Detection using BERT

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 📌 Project Overview

Food safety plays a crucial role in public health. This project leverages **BERT (Bidirectional Encoder Representations from Transformers)** and **deep learning models** to **classify food hazard data** into **4 main classes**, each containing **10+ labels**, enabling improved **hazard detection and safety analytics**.

Using **state-of-the-art NLP techniques**, the model processes text-based hazard data and identifies potential risks, aiding **early detection and decision-making in the food industry**.  

---

## 🚀 Key Features

- ✅ **Multi-class, multi-label classification**: Detects hazards across **4 classes** with **10+ labels each**.  
- ✅ **BERT-based embeddings** for high-quality text representation.  
- ✅ **Fine-tuned BERT model**, achieving **>70% accuracy** across all hazard classes.  
- ✅ **LSTM and RNN models** trained on BERT embeddings for comparison.  
- ✅ **Matplotlib visualizations** for model evaluation and results analysis.  

---

## 🛠️ Tech Stack

- **Programming Language:** Python 🐍  
- **Libraries Used:**  
  - 🤗 [Hugging Face Transformers](https://huggingface.co/transformers/)  
  - 📊 [Scikit-learn](https://scikit-learn.org/)  
  - 🐼 [Pandas](https://pandas.pydata.org/)  
  - 📈 [Matplotlib](https://matplotlib.org/)  
- **Models:**  
  - BERT (fine-tuned)  
  - LSTM  
  - RNN  

---

## 📂 Dataset

- **Text-based hazard data**, categorized into:
  - **4 main hazard classes** (e.g., Biological, Chemical, Physical, Other).  
  - **10+ sub-labels** per class.  

### Preprocessing Steps:
- Data cleaning and normalization  
- BERT-compatible tokenization  
- Train-test splitting  

---

## ⚙️ Workflow

1. **Data Preprocessing**  
   - Text cleaning, tokenization, and embedding extraction.

2. **Feature Extraction**  
   - Generated **BERT embeddings** for semantic representation.

3. **Model Training**  
   - Fine-tuned **BERT** for classification.  
   - Trained **LSTM and RNN models** for comparison.

4. **Evaluation**  
   - Metrics: Accuracy, F1-score, Confusion Matrix.  
   - Achieved **70%+ accuracy** on all hazard classes.

5. **Visualization**  
   - Plots for **model performance comparison**.

---

## 📊 Results

- **Fine-tuned BERT model** achieved the highest accuracy (>70%).  
- **LSTM and RNN** provided baseline comparisons.  
- Visualizations showed **clear hazard class separation**.

---
