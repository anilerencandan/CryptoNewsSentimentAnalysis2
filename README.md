# Cryptocurrency News Sentiment Analysis with Transformer Models

## 🎯 Project Goals
This project aims to analyze cryptocurrency market sentiment through news articles using state-of-the-art transformer models. The main objectives include:

- **Accurate Sentiment Classification**: Classifying cryptocurrency news into Positive, Negative, or Neutral sentiment categories.
- **Multilingual Analysis**: Translating Turkish cryptocurrency news into English for a broader analysis.
- **Model Performance Comparison**: Evaluating and comparing the performance of various transformer models.
- **Robust Sentiment Analysis Pipeline**: Building a reusable and scalable sentiment analysis framework.

---

## 🔄 Workflow

### **1. Data Collection & Preparation**
- Gathered cryptocurrency news articles from various sources.
- Cleaned and preprocessed text data, including tokenization, stemming, and lemmatization.
- Translated Turkish news articles to English for multilingual analysis.
- Created balanced datasets by generating synthetic data using GPT for class imbalance correction.

### **2. Model Implementation**
Six different transformer models were implemented and fine-tuned:
- **BERT**: Used as a baseline model for comparison.
- **ALBERT**: Lightweight and optimized alternative to BERT.
- **DeBERTa**: Focused on enhanced attention mechanisms.
- **DistilBERT**: A faster and more compressed version of BERT.
- **FinBERT**: Designed specifically for financial text analysis.
- **GPT**: Used for generative sentiment analysis and synthetic data generation.

### **3. Analysis Process**
- Each model was trained on the prepared dataset.
- Sentiment classification was performed across three classes: Positive, Negative, Neutral.
- Evaluated performance using metrics such as:
  - Accuracy
  - Precision
  - Recall
  - F1 Score

---

## 📊 Results Overview
- Successfully processed and analyzed over **5000+ news articles**.
- Implemented **multilingual sentiment analysis** (Turkish-English).
- Compared the performance of different transformer architectures.
- Created a robust and reusable pipeline for future sentiment analysis tasks.

---

## 🛠️ Technical Implementation

### **Libraries Used**
- 🤗 Transformers
- PyTorch
- Pandas
- NLTK
- Scikit-learn

### **Key Features**
- Custom data preprocessing pipeline for text cleaning and tokenization.
- Fine-tuning capabilities for transformer models.
- Cross-validation for performance validation.
- Metrics tracking for accuracy, precision, recall, and F1 scores.

---

## 💡 Insights & Findings
- Different transformer models exhibit varying performance on cryptocurrency news.
- **FinBERT** shows strong performance on financial terminology.
- Translation quality directly impacts sentiment analysis accuracy.
- Real-time analysis introduces unique challenges such as computational overhead.

---

## 🔍 Use Cases
- **Market Sentiment Analysis**: Gaining insights into market trends based on news sentiment.
- **Trading Signal Generation**: Identifying potential buy/sell signals from market sentiment.
- **News Monitoring and Alerting**: Tracking sentiment shifts in real-time.
- **Trend Analysis and Prediction**: Predicting market movements based on aggregated sentiment.

---

## 📈 Conclusion
This project highlights the power of transformer models in understanding cryptocurrency market sentiment through news analysis. By leveraging state-of-the-art NLP techniques, the pipeline provides valuable insights for traders and researchers alike.

---

## 🚀 How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/anilerencandan/CryptoNewsSentimentAnalysis2.git
