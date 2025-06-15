# sentiment-insights-dashboard
Analyze and visualize e-commerce sentiment reviews using  Python, and Excel
## 📌 Project Overview

This repository hosts the full workflow and analysis of my MBA dissertation titled:

**"A Sentiment-Based Framework for Product Recommendation and Price-Quality Perception in E-Commerce Reviews"**

This study explores how sentiment analysis—powered by BERT (Bidirectional Encoder Representations from Transformers)—can be used to quantify consumer perception from product reviews, particularly in the **headphone** category. It also investigates whether sentiment correlates with product pricing and how such data can aid **product recommendations and market decisions**.

---

## 📂 Repository Structure

.
├── 📁 CleanedFiles/
│ ├── Cleaned_Reviews.csv
│ ├── Updated_Reviews_with_Prices.csv
├── 📁 SampledData/
│ ├── Sampled_ProductReviews.csv
├── 📁 SentimentResults/
│ ├── bert_sentiment_output.xlsx
│ └── Weight_score_sentiment.xlsx
├── 📁 Scripts/
│ ├── 01_data_cleaning.py
│ ├── 02_sampling.py
│ ├── 03_sentiment_analysis_colab.ipynb
│ ├── 04_anova_test.py
│ ├── 05_regression_analysis.ipynb
├── 📄 Sentiment Framework.pdf
└── 📄 README.md

yaml
Copy
Edit

---

## 🧠 Key Research Questions

1. **Can companies recommend products based on sentiment scores?**
2. **Is there a significant correlation between product price and sentiment score?**



## 🧪 Environment Setup

- **Python 3.9+**
- **Libraries**: `pandas`, `numpy`, `transformers`, `scipy`, `matplotlib`, `seaborn`, `plotly`, `statsmodels`
- **Notebook Execution**: Google Colab preferred (for BERT and interactive plots)

---

