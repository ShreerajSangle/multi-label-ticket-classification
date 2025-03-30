# multi-label-ticket-classification
Modular AI System for Multi-Label Email Classification using Chained and Hierarchical Modeling
# 🧠 Modular AI System for Multi-Label Email Classification

This repository contains the complete implementation and evaluation of a **Modular AI System** designed for classifying customer support tickets using **Chained Multi-Output Classification** and **Hierarchical Modeling** approaches.

## 📂 Project Overview

In this project, we tackled a real-world **multi-label classification problem** using customer support ticket data. The objective was to categorize each ticket across three dependent dimensions:

- **Type 2 (T2)** – Ticket Category  
- **Type 3 (T3)** – Subcategory  
- **Type 4 (T4)** – Priority or Final Resolution  

The system is implemented with a strong focus on **modular architecture**, separation of concerns, and clean evaluation of both modeling strategies.

---

## 📌 Main File

The core implementation is available in:

### 👉 [`Full_Integrated_Pipeline_Notebook.ipynb`](./notebooks/Full_Integrated_Pipeline_Notebook.ipynb)

This notebook contains:
- Data preprocessing
- TF-IDF vectorization
- Model training (Chained + Hierarchical)
- Evaluation metrics and summaries
- Output predictions

---

 Dataset

- `AppGallery.csv`  
- `Purchasing.csv`

These are cleaned customer support ticket datasets merged and used to train the classification models.




