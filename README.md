# 🍽️ Zomato Restaurant Review Analysis & Clustering

This project analyzes and visualizes restaurant review data from Zomato using Natural Language Processing (NLP), Clustering, and Sentiment Analysis techniques to uncover valuable business insights and restaurant performance patterns.

---

## 📁 Project Structure

- **Data Source:** Two CSV files (`zomato_restaurants.csv`, `zomato_reviews.csv`)
- **Dataset link:** https://drive.google.com/drive/folders/1Ttkgv-QboSnPlTQipLwM4vR6AM3IWwJC?usp=sharing
- **Platform:** Google Colab
- **Project Type:** EDA + Unsupervised Learning + NLP
- **Goal:** Merge review and restaurant data, extract sentiments, cluster restaurants by quality/value, and uncover actionable insights.

---

## 📌 Key Features

- ✅ Clean merge of restaurant and review datasets using a unique `Restaurant Key`
- ✅ Text preprocessing, cleaning, and lemmatization
- ✅ Sentiment analysis using `TextBlob`
- ✅ Restaurant clustering based on rating, cost, and sentiment score using `KMeans`
- ✅ Elbow method + Dendrogram to determine optimal cluster count
- ✅ Feature engineering: `value_score` metric
- ✅ Word cloud visualizations for sentiment words
- ✅ Business insights for each cluster to guide decision-making

---

## 🛠️ Tools & Libraries

- **Pandas, NumPy, Matplotlib, Seaborn** – Data analysis and visualization
- **NLTK, TextBlob, WordCloud** – Natural Language Processing and Sentiment Analysis
- **scikit-learn** – Clustering, scaling, feature engineering
- **SciPy** – Hierarchical clustering (Dendrogram)

---

## 📊 Business Questions Answered

1. Which restaurants offer the best value for money?
2. What do customers say most positively about in reviews?
3. How can we segment restaurants into performance-based clusters?
4. Can we predict poor-performing restaurants based on sentiment?
5. Which clusters should Zomato prioritize for promotions or improvements?

---

## 📈 Charts & Insights

- 📌 Elbow and Dendrogram to determine ideal cluster size
- 📌 Scatter plots of clusters based on sentiment, cost, and rating
- 📌 Word clouds for positive, negative review terms

---

## 🧠 ML & Clustering Summary

| Model       | Features Used              | Clusters | Evaluation |
|-------------|----------------------------|----------|------------|
| KMeans      | Rating, Cost, Sentiment    | 3        | Elbow & Interpretation |

---

## 🚀 Future Improvements

- Integrate restaurant location for geo-based insights
- Deploy as a Streamlit dashboard
- Include supervised models for review classification

---

## 📝 How to Run

1. Open `Google Colab`
2. Mount your Google Drive
3. Place both CSVs inside `/MyDrive/zomato/`
4. Run the notebook from top to bottom (no errors expected – deployment-ready)

---

## 🙌 Acknowledgements

- Zomato for dataset inspiration
- NLTK, TextBlob for NLP capabilities
- Scikit-learn and SciPy for robust clustering


