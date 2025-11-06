💹 CryptoPulse: Sentiment Forecasting on Bitcoin Tweets

🧠 Project Overview

CryptoPulse is a Data Science project that analyzes public sentiment on Bitcoin using Twitter data.
By applying Natural Language Processing (NLP) and Machine Learning (Logistic Regression), it classifies tweets as Positive, Negative, or Neutral and visualizes market mood patterns.
The project helps forecast how public opinion correlates with cryptocurrency trends and investor confidence.


---

🎯 Project Purpose

> To analyze and forecast public sentiment toward Bitcoin and understand how social media opinions influence crypto market behavior.




---

🧩 Key Features

✅ Data Cleaning & Preprocessing — Removal of URLs, hashtags, mentions, and special characters.
✅ NLP-Based Sentiment Analysis — Used TF-IDF Vectorization and Logistic Regression for classification.
✅ Machine Learning Pipeline — Built and saved a predictive model for tweet sentiment detection.
✅ 10 Advanced Visualizations — Representing trends, distributions, correlations, and frequent terms.
✅ Compact Dataset — Optimized to 800 tweets for faster execution and better GitHub display.
✅ Forecasting Insight — Sentiment trend visualization to monitor changing crypto mood over time.


---

📊 Visualizations Included

#	Visualization	Description

1️⃣	Sentiment Distribution	Count of positive, negative, and neutral tweets
2️⃣	Confusion Matrix	Model prediction performance
3️⃣	Positive Word Cloud	Most frequent words in positive tweets
4️⃣	Negative Word Cloud	Frequent words in negative tweets
5️⃣	TF-IDF Top Features	Most influential words in classification
6️⃣	Sentiment Pie Chart	Percentage distribution of sentiment types
7️⃣	Sentiment Trend Over Time	Monthly variation in tweet sentiment
8️⃣	Average Tweet Length	Comparison of text size per sentiment
9️⃣	Common Words per Sentiment	Most used words per mood
🔟	Correlation Heatmap	Relationship between sentiment and tweet length



---

⚙ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, WordCloud, Regex

Machine Learning Model: Logistic Regression

IDE: Jupyter Notebook / Anaconda

Version Control: Git & GitHub



---

📂 Folder Structure

📁 crypto-sentiment-analysis
 ┣ 📄 Crypto_Sentiment_Analysis.ipynb
 ┣ 📄 bitcoin_tweets_sample.csv
 ┣ 📄 crypto_sentiment_model.pkl
 ┗ 📄 README.md


---

🚀 Steps to Run the Project

1. Clone Repository:

git clone https://github.com/your-username/crypto-sentiment-analysis.git
cd crypto-sentiment-analysis


2. Install Dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn wordcloud


3. Open Jupyter Notebook:

jupyter notebook


4. Run All Cells in Crypto_Sentiment_Analysis.ipynb




---

🔍 Model Accuracy & Output

Accuracy: ~85% (depends on dataset variation)

Classification Report: Precision, Recall, F1-score per sentiment

Output Visuals: Heatmaps, Word Clouds, Trend Graphs, TF-IDF plots



---

🌐 Insights

Positive tweets often coincide with rising Bitcoin trends.

Negative sentiment spikes during market drops or volatility.

Word frequency and length reveal emotional intensity in crypto discussions.



---

🔮 Future Enhancements

🚀 Integrate Live Twitter API for real-time data collection.
🧠 Experiment with Deep Learning Models like LSTM or BERT for higher accuracy.
📈 Correlate sentiment with actual Bitcoin market prices for predictive analytics.
🌍 Expand beyond Bitcoin — include Ethereum, Dogecoin, or other trending coins.
🎨 Build a dashboard (Streamlit/Plotly) for live visualization of crypto sentiment.


---

🏁 Conclusion

This project bridges social media analytics and financial forecasting by uncovering how collective emotions drive cryptocurrency movements.
It demonstrates the power of combining NLP, ML, and Data Visualization in understanding digital market trends.
