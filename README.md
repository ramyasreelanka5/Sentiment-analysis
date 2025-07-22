# Sentiment Analysis of 2019 Indian General Elections Tweets

This project analyzes public sentiment from over 46,000 tweets during the 2019 Indian General Elections. It includes data cleaning, preprocessing, sentiment classification, and geo-spatial visualization of sentiment trends across Indian states.

---

## Overview

The goal is to evaluate public opinion during the 2019 Indian General Elections by mining Twitter data. The project uses NLP techniques to preprocess tweets, classify sentiment, and visualize sentiment trends geographically and over time.

---

## Features

- Data cleaning (removal of noise, special characters, URLs)
- Text preprocessing (tokenization, stopword removal, stemming/lemmatization)
- Sentiment classification (positive, negative, neutral)
- Geo-spatial mapping of sentiment across Indian states
- Time-based plots of sentiment trends

---

## Data

- **Source**: 46,000+ tweets related to 2019 Indian General Elections
- **Fields**:
  - Tweet text
  - Timestamp
  - User location (if available)
  - Derived sentiment label

*Note: Dataset is not included due to privacy and API terms.*

---

## Pipeline

1. **Data Cleaning**
   - Remove duplicates
   - Filter noise (hashtags, mentions, URLs)
   - Lowercase conversion

2. **Preprocessing**
   - Tokenization
   - Stopword removal
   - Stemming/Lemmatization

3. **Sentiment Analysis**
   - Rule-based or ML classifier (e.g., VADER, TextBlob, custom model)

4. **Geo-Spatial Visualization**
   - Map sentiment scores to Indian states
   - Plot choropleth maps

---
## 📊 Technologies Used

- **Python**
- **Data Handling:** `Pandas`, `NumPy`
- **Machine Learning:** `scikit-learn`
- **Visualization:** `Matplotlib`, `Seaborn`  
  *(Optional: `WordCloud`, `Plotly` for enhanced visuals)*
- **Sentiment Analysis:** `NLTK`, `TextBlob`

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/political-sentiment-analysis.git
   cd political-sentiment-analysis
   ```

2. **Install required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the notebook:**
   ```bash
   jupyter notebook "Sentiment analysis.ipynb"
   ```

---

## 📈 Sample Analyses

- 📅 Sentiment over time  
- 🗣️ Most popular tweets by sentiment  
- 🧾 Party-wise tweet distribution  
- 🔥 Influencer or viral tweet detection  


5. **Time Series Visualization**
   - Aggregate sentiment over time
   - Visualize mood shifts

---
