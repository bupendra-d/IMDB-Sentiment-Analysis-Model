# 🎬 IMDB Sentiment Analysis Model

This project is a **Natural Language Processing (NLP)** based machine learning model that predicts the sentiment (Positive or Negative) of IMDB movie reviews. It uses **TF-IDF vectorization** for text feature extraction and a **Logistic Regression** model for classification.

---

# 📂 Project Structure

IMDB-Sentiment-Analysis-Model/
│
├── imdb_model.pkl             # Trained Logistic Regression model
├── imdb_pipeline.pkl          # TF-IDF + Model pipeline
├── IMDB_dataset.csv           # Original dataset
├── input.csv                  # Test data for inference
├── output.csv                 # Model predictions
├── sentiment_analysis.py      # Main Python script (your code)
├── requirements.txt           # Dependencies
└── README.md                  # Project documentation


# ⚙️ Features
- Text preprocessing using **TF-IDF Vectorizer**
- Binary classification using **Logistic Regression**
- Automated data cleaning and encoding
- Pipeline saving and reloading using **Joblib**
- Easy inference on new data (`input.csv` → `output.csv`)


# 🚀 How to Run

# 1. Clone the repository
```bash
git clone https://github.com/bupendra-d/IMDB-Sentiment-Analysis-Model.git
cd IMDB-Sentiment-Analysis-Model
