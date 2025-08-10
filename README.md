# 🛒 Amazon Product Reviews – LSTM Sentiment Analysis  

## 📌 Overview  
This project uses a **Long Short-Term Memory (LSTM)** deep learning model to analyze **Amazon product reviews** and classify them as **positive, negative, or neutral**.  
It demonstrates how deep learning can be applied to **Natural Language Processing (NLP)** for sentiment analysis.  

---

## 🚀 Features  
- Cleans and preprocesses raw Amazon review text (removes punctuation, stopwords, and special characters).  
- Tokenizes and pads sequences for LSTM compatibility.  
- Trains an **LSTM** model to capture long-term dependencies in text.  
- Predicts sentiment and outputs **confidence scores**.  
- Visualizes training metrics (accuracy, loss curves).  

---

## 🛠 Tech Stack  
- **Python 3.8+**  
- **TensorFlow / Keras** – Deep learning framework  
- **NumPy, Pandas** – Data manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Metrics, preprocessing  

---

##  Result
- **Source:** [Amazon Product Reviews Dataset](https://nijianmo.github.io/amazon/index.html)  
- **Format:** CSV/JSON with `reviewText` and `overall` rating.  
- **Sentiment Mapping:**  
  - 1–2 ⭐ → Negative  
  - 3 ⭐ → Neutral  
  - 4–5 ⭐ → Positive  

---



