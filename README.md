# Mental Health NLP — Sentiment & Emotion Analysis

A lightweight NLP project analyzing a Mental Health Conversations dataset using classical NLP sentiment methods (TextBlob + VADER) and a rule-based emotion classifier.

This project performs:
- Exploratory Data Analysis (EDA)
- Sentiment Analysis (polarity, subjectivity, VADER compound)
- Emotion Tagging (sadness, joy, anger, fear, neutral, high-risk)
- Cleaned, safe processed outputs (raw data excluded)

## Structure
Mental-Health-Nlp/
│
├── Data/
│ ├── raw/ # (contains original dataset)
│ └── processed/ # Final outputs
│
├── notebooks/
│ └── 01_EDA.ipynb # Analysis notebook
│
├── src/
│ └── process_lightweight.py # Reproducible processing script 
│
├── requirements.txt # Dependencies
├── README.md # Project documentation
├── .gitignore # Raw data excluded

## Quickstart
```bash
pip install -r requirements.txt


cat > requirements.txt << 'EOF'
pandas
numpy
scikit-learn
nltk
matplotlib
seaborn
streamlit
