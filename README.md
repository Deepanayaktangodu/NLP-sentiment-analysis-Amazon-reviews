# NLP-Based Sentiment Analysis on Consumer Food Feedback

This project applies Natural Language Processing (NLP) to analyze customer sentiment from the Amazon Fine Food Reviews dataset. Using polarity scoring and emotion detection techniques, the project aims to uncover key insights into consumer experiences with food products.

---

## 📦 Dataset

The full dataset contains over 568,000 Amazon food product reviews. Due to file size limitations, only a sample of the data is included in this repository.

🔗 **Download Full Dataset**: [Amazon Fine Food Reviews on Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

---

## 🧰 Tools & Libraries Used

- Python  
- Pandas, NumPy  
- NLTK, TextBlob  
- VADER SentimentIntensityAnalyzer  
- WordCloud  
- Seaborn, Matplotlib  
- Jupyter Notebook

---

## 🔍 Project Workflow

1. **Data Loading & Cleaning**  
   - Removed duplicates, handled missing values  
   - Standardized text (lowercasing, punctuation, stopword removal)

2. **Sentiment Classification (TextBlob)**  
   - Labeled reviews as Positive or Negative using polarity scores

3. **Exploratory Sentiment Analysis**  
   - Distribution plots, polarity histograms, word frequency charts  
   - WordClouds for each sentiment group

4. **Emotion Detection (VADER)**  
   - Compound score analysis  
   - Classified into Positive, Negative, Neutral

5. **Visualization & Interpretation**  
   - Bar charts, sentiment breakdowns  
   - Word patterns and polarity distribution

---

## 📊 Key Insights

- Over **84%** of the reviews were positive  
- Positive reviews highlight terms like "love", "taste", "coffee", "great"  
- Negative reviews focus on "bad", "disappointed", "waste", "poor taste"  
- VADER confirmed sentiment trends with slightly broader classification  
- Most polarity scores ranged from **0.1 to 0.5**, indicating mild positivity

---

## 💡 Business Value

- Identify key drivers of customer satisfaction and dissatisfaction  
- Improve product quality and messaging using sentiment signals  
- Monitor emotion trends to support customer loyalty and product feedback loops

---

## ▶️ How to Run

1. Clone this repo  
2. Open `Amazon_Reviews_Analysis.ipynb` in Jupyter Notebook  
3. Install required libraries with:
   ```bash
   pip install -r requirements.txt
Follow the notebook to reproduce the analysis

🧾 Credits
Dataset: Kaggle - Amazon Fine Food Reviews

Analysis & Reporting by: Deepa Nayak

📌 Project Status: Completed ✅

---
