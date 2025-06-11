# YouTube Comment Sentiment Analysis 🎯

This project performs sentiment analysis on YouTube comments using Natural Language Processing (NLP) and several Machine Learning classifiers. It focuses on categorizing comments as **positive**, **negative**, or **neutral** using text preprocessing and classification models.

---

## 📁 Dataset

The dataset is expected in a CSV format with YouTube comments and their corresponding sentiment labels.

### Example columns:
- `Comment`: The YouTube comment text
- `Sentiment`: Label as 0 (negative), 1 (neutral), or 2 (positive)

---

## 🔧 Dependencies

Install the required libraries:

```bash
pip install pandas numpy sklearn nltk 
```

Also, run this once for NLTK stopwords:

```python
import nltk
nltk.download('stopwords')
```

---

## 📌 Features

### ✅ Text Preprocessing
- Removing punctuation and special characters
- Lowercasing
- Tokenization
- Stopword removal
- Word stemming using `PorterStemmer`
  
### ✅ Model Training
Trains and evaluates the following models:
- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- SVC


## 🚀 Usage

1. Clone the repository.
2. Place your YouTube comment CSV file in the root folder.
3. Run the Jupyter Notebook:

```bash
jupyter notebook YoutubeCommentAnalysis.ipynb
```

4. Review the model performance and analysis outputs.

---

## ✍️ Author

Made with ♥ by [seika-afk]
