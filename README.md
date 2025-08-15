# Sentiment Analysis on Tweets/Reviews using NLP

## 📌 Project Overview
This project performs **sentiment analysis** on short text data such as tweets or product reviews.  
It uses **Natural Language Processing (NLP)** techniques to classify text into:
- **Positive**
- **Negative**
- **Neutral**

The implementation includes:
- Data preprocessing with **TF-IDF vectorization**
- **Logistic Regression** classifier for multi-class prediction
- Model evaluation using accuracy, precision, recall, and F1-score
- Visualization of results (Confusion Matrix)
- Extraction of most informative features for each sentiment class

---

## 📂 Project Structure
```
sentiment_analysis_nlp.ipynb   # Jupyter Notebook with code and results
README.md                      # Project description and usage
```

---

## ⚙️ Features
- Synthetic dataset creation with **emojis and slang words**
- Text preprocessing (stopword removal, n-grams)
- Train/Test split with stratified sampling
- Model training using scikit-learn pipeline
- Performance metrics and insights
- Confusion matrix visualization
- Example predictions for new texts

---

## 🛠️ Installation
Make sure you have Python 3.8+ installed.  
Install the required libraries:
```bash
pip install numpy pandas scikit-learn matplotlib
```

---

## 🚀 Usage

### Option 1: Run Locally
1. Clone the repository or download the `.ipynb` file.
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Run all cells in `sentiment_analysis_nlp.ipynb`.

### Option 2: Run in Google Colab
1. Go to [Google Colab](https://colab.research.google.com).
2. Upload `sentiment_analysis_nlp.ipynb`.
3. Run all cells.

---

## 📊 Example Output
**Classification Report:**
```
              precision    recall  f1-score   support

    negative       0.79      0.73      0.76
     neutral       0.87      0.87      0.87
    positive       0.81      0.87      0.84

    accuracy                           0.82
```

**Confusion Matrix:**
- Rows: Actual labels
- Columns: Predicted labels

---

## 📌 Future Improvements
- Use a real dataset from Twitter API or review sites
- Try advanced NLP models (BERT, RoBERTa)
- Implement emoji-aware tokenization
- Deploy as a web app using Flask/Streamlit

---

## 📜 License
This project is for educational purposes.
