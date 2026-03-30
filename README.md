# 📰 ADNE Fake News Classifier
Comparative study of Machine Learning, Deep Learning, and Transformer-based models for fake news text classification. he repository benchmarks and compares a range of approaches — from classical ML baselines to transformer-based models — to classify news articles as real or fake.

---
 
## 🧠 Models & Approaches
 
| Approach | Examples |
|---|---|
| **Classical ML** | Logistic Regression |
| **Deep Learning** | LSTM neural network |
| **Transformers** | BERT and/or fine-tuned variants |
| **Generation** | GAN, Markov Chains |
 
Each approach is implemented as a self-contained Python script, making it easy to run and compare results independently.

---
 
## 📁 Project Structure
 
```
ADNE-Fake-News-Classifier/
│
├── data/                   # Dataset files (or download instructions)
├── models/                 # Model definitions and training scripts
├── utils/                  # Preprocessing, EDA
└── requirements.txt        # Python dependencies
```
---
 
## ⚙️ Setup
 
### Prerequisites
 
- Python 3.8+
- pip
 
### Install dependencies
 
```bash
pip install -r requirements.txt
```
 
> For transformer models, a GPU is strongly recommended. The project uses T4 GPU (offered by Google Colab) for BERT-based fine-tuning.
 
---

## 📊 Results
 
---

## 📦 Dataset
 
This project uses a labeled fake news dataset (https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset). Refer to the `data/` directory or the script headers for the exact source and download instructions.
 
---

## 📚 Course Context
 
This project was submitted as part of the **ADNE** course. It serves as a practical exploration of NLP model selection, text preprocessing, and evaluation methodology in the context of a real-world classification problem.
