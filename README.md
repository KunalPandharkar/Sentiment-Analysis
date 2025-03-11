
## 📖 Project Overview
This project analyzes tweets to classify them as **Positive, Neutral, or Negative** using **Machine Learning & Natural Language Processing (NLP)** techniques. The system extracts live tweets, processes text data, trains classification models, and visualizes sentiment trends.

## 🚀 Features
✅ Extracts real-time tweets based on user-defined keywords.  
✅ Cleans and preprocesses text data (tokenization, stopword removal, stemming).  
✅ Performs sentiment analysis to classify tweets into three categories.  
✅ Trains ML models for sentiment prediction and optimizes accuracy.  
✅ Generates visualizations of sentiment distribution and frequent words.  

## 🛠 Installation & Setup
### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/KunalPandharkar/Sentiment-Analysis.git
cd twitter-sentiment-analysis
```
### 2️⃣ **Install Dependencies**
```bash
pip install pandas numpy seaborn matplotlib scikit-learn textblob nltk tweepy wordcloud
```
### 3️⃣ **Download NLTK Stopwords**
```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```

## 📊 Usage
### 4️⃣ **Run Sentiment Analysis on Twitter Data**
```python
python sentiment_analysis.py
```

## 📊 Results & Insights
- Achieved **high accuracy** in classifying tweet sentiments.  
- Visualized sentiment distribution and common words using **graphs & word clouds**.  
- Demonstrated effectiveness of ML models in real-world text classification.  

## 📩 Future Enhancements
🔹 Deploy the model as a **Flask API** for real-time sentiment analysis.  
🔹 Integrate with **streaming APIs** for continuous live tweet analysis.  
🔹 Improve accuracy with **advanced deep learning models (LSTMs, Transformers)**.  

---
