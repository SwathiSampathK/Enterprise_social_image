# Influence of an Enterprise’s Social Image on The Stock Market – A Correlative Analysis

This project explores the correlation between a company’s social image captured through social media sentiment and its impact on stock market behavior. Using a combination of **Natural Language Processing (NLP)** and **Knowledge Graphs**, the study goes beyond traditional sentiment analysis to include the influence of associated collaborators, dependents, and competitors.

---

## Objective

To enhance the prediction of stock market trends by incorporating:

- Real-time sentiment analysis from social media platforms (e.g., Twitter)
- Relationship mapping through knowledge graphs
- Predictive modeling with machine learning techniques

---

## Methodology

### 1. **Data Collection**
- **Tweets** using Tweepy API based on company and related keywords
- **News articles** using Google News API
- **Stock market data** from Alpha Vantage API

### 2. **Sentiment Analysis**
- Preprocessing (cleaning, tokenizing)
- Sentiment scoring using **VADER**
- Aggregation of daily sentiment values

### 3. **Knowledge Graph Construction**
- Entity and relationship extraction from news using **REBEL**
- Graph creation and visualization using **PyVis**
- Analysis of inter-company influence

### 4. **Stock Prediction**
- Features: Merged sentiment + stock data
- Models used:
  - KNN
  - SVM
  - Decision Tree
  - Random Forest
  - Logistic Regression
  - ANN (Neural Network)
- Target: Buy/Sell signal prediction
- 
![Workflow](images/Fig%205.1%20Sentiment%20analysis%20and%20prediction%20with%20twitter%20data.png)

---

## Results

- The social sentiment of **OpenAI** was found to significantly impact the stock trends of **Microsoft** (collaborator) and **Nvidia** (hardware partner).
- Machine learning models trained on combined sentiment and stock data yielded improved prediction accuracy.
- Network-wide sentiment (from collaborators/competitors) enhanced the model’s context-awareness.

![Predicted Trend](images/Fig%206.8%20Machine%20learning%20models%20predicted%20trend%20of%20sentiment%20of%20OpenAI%20vs%20stock%20of%20Microsoft.png)
---

## Tech Stack

- **Python 3.10**
- **Tweepy** for Twitter data
- **GoogleNews** for news scraping
- **VADER / TextBlob** for sentiment analysis
- **REBEL + BERT** for entity/relation extraction
- **scikit-learn, TensorFlow** for modeling
- **Matplotlib / Seaborn / PyVis** for visualization

---

## Citation

If you use this work, please cite:



Swathi S., Siji Rani S. (2025). "Influence of an Enterprise’s Social Image on The Stock Market – A Correlative Analysis"

---

## Authors

- [Swathi S](mailto:swathisampath18@gmail.com)
- [Siji Rani S](mailto:sijiranis@am.amrita.edu)

---

## Tech Stack

- **Python 3.10**
- **Tweepy** for Twitter data
- **GoogleNews** for news scraping
- **VADER / TextBlob** for sentiment analysis
- **REBEL + BERT** for entity/relation extraction
- **scikit-learn, TensorFlow** for modeling
- **Matplotlib / Seaborn / PyVis** for visualization

---

## Citation

If you use this work, please cite:



