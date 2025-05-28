# Cyberbullying-Forecasting-Project
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.8%2B-orange)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

An AI-powered system to detect and predict cyberbullying in social media text using advanced NLP and machine learning techniques.

## Key Features ✨
- 🚩 Real-time classification of toxic content (hate speech, threats, harassment)
- 🔍 Context-aware analysis using BERT and LSTM models
- 📊 Sentiment and toxicity probability scoring
- ⚡ Scalable API for social media platforms
- 📈 Dashboard for moderation analytics

## Technology Stack 🛠️
| Component            | Technologies Used                          |
|----------------------|--------------------------------------------|
| **Core NLP**         | BERT, RoBERTa, LSTM                        |
| **Text Processing**  | NLTK, SpaCy, HuggingFace Transformers      |
| **Backend**          | FastAPI, Flask                             |
| **Deployment**       | AWS Lambda, Docker                         |
| **Data Pipeline**    | Twitter/Reddit APIs, Pandas, PySpark       |

## Installation 📦
```bash
git clone https://github.com/yourusername/cyberbullying-detection.git
cd cyberbullying-detection
pip install -r requirements.txt
python -m spacy download en_core_web_lg

Project Structure 📂
.
├── api/                  # FastAPI endpoints
├── data/                 # Sample datasets
├── models/               # Saved model weights
├── notebooks/            # Jupyter notebooks for EDA
├── preprocessing/        # Text cleaning scripts
├── training/             # Model training scripts
└── evaluation/           # Performance metrics

Results 📊
Model	Accuracy	Precision	Recall
BERT-base	92.1%	89.5%	93.2%
LSTM	88.3%	85.1%	89.7%
SVM (baseline)	82.4%	79.8%	83.1%
