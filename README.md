# India 24K Gold Price Prediction using NLP

## Overview
This project builds a data science pipeline that combines real-time financial news sentiment with historical gold price data to analyze and predict movements in India's 24K gold price.The system automatically collects news headlines related to gold, performs Natural Language Processing (NLP) sentiment analysis, merges this information with gold price data, and produces analytical insights and predictive modeling outputs.

**Problem:** Traditional gold price models ignore news sentiment—a key driver of India's volatile 24K gold market (₹1,93,000+/10g), where financial headlines, festivals, and global events cause unpredictable swings missed by time-series alone.

**Solution:** NLP pipeline automating RSS news → sentiment analysis → gold price fusion → predictive modeling, delivering real-time insights for traders/researchers lacking sentiment-aware forecasting tools.

## Project Objectives
- Collect real-time gold-related news articles
- Perform NLP-based sentiment analysis
- Integrate sentiment signals with gold price data
- Build predictive models to analyze price movement
- Visualize insights for interpretation

## Pipeline Architecture

News Sources → Text Preprocessing → Sentiment Analysis → Gold Price Data Integration → Feature Engineering → Prediction Model → Visualization

## Technologies Used

**Language:** Python
**Libraries:** Pandas, NumPy, Scikit-learn, NLTK, Transformers, Matplotlib
**Sources:** Financial news RSS, gold price datasets
## How to Run the Project

1. Clone the repository

```
git clone [https://github.com/your-username/NLP-GoldTrend-India.git](https://github.com/your-username/NLP-GoldTrend-India.git)
cd NLP-GoldTrend-India
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Launch the notebook

```
jupyter notebook notebooks/gold_price_nlp_pipeline.ipynb
```

## Potential Improvements

- Integrate transformer-based financial sentiment models
- Add LSTM or Transformer time-series forecasting
- Deploy the model as a web dashboard
- Automate daily data ingestion

## License
This project is intended for academic and research purposes.
