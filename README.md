# 📰 Fake News Detection - TruthCheck 🧠

Fake news has become a major threat to accurate public information. This machine learning project, **TruthCheck**, aims to classify news articles as **fake** or **real** using supervised learning models trained on a labeled dataset of news headlines and content.

---

## 🚀 Features

- Detects fake vs real news articles
- Preprocessing using NLTK, stopword removal, and TF-IDF vectorization
- Multiple ML models (Logistic Regression, Random Forest, Decision Tree, Gradient Boosting)
- Accuracy and performance evaluation
- Jupyter Notebook format – ready to run on Google Colab

---

## 🧠 Machine Learning Models Used

- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- Gradient Boosting Classifier

---

## 📁 Dataset

- **Source**: [Kaggle - Fake News Detection](https://www.kaggle.com/datasets/jainpooja/fake-news-detection)
- Contains two CSV files:
  - `Fake.csv` — Fake news articles
  - `True.csv` — Real news articles

---

## ⚙️ How to Run (Google Colab Recommended)

1. Upload your `kaggle.json` (API token) and authenticate:
    ```python
    from google.colab import files
    files.upload()  # Upload kaggle.json
    !mkdir -p ~/.kaggle
    !cp kaggle.json ~/.kaggle/
    !chmod 600 ~/.kaggle/kaggle.json
    ```

2. Download dataset:
    ```python
    !kaggle datasets download -d jainpooja/fake-news-detection
    !unzip fake-news-detection.zip -d data
    ```

3. Run all cells to:
    - Load and explore data
    - Preprocess the text
    - Train multiple ML models
    - Evaluate accuracy and confusion matrix

---

## 📊 Results

| Model                 | Accuracy |
|----------------------|----------|
| Logistic Regression  | 96.4%    |
| Random Forest        | 97.1%    |
| Decision Tree        | 95.2%    |
| Gradient Boosting    | 97.3%    |

*Note: Accuracy may vary slightly depending on train-test split and random seed.*

---

## 📦 Libraries Used

- `pandas`, `numpy`
- `scikit-learn`
- `nltk`
- `matplotlib`, `seaborn`
- `kaggle` API (for dataset import)

---

## 📌 Project Structure

```
📁 fake-news-detection/
│
├── fake_news_detection.ipynb          # Main notebook (Colab compatible)
└── README.md                 # Project documentation
```

---


## 👨‍💻 Author

**Ayush Sareen**  
[GitHub](https://github.com/Ayush-Sareen) | [Portfolio](https://ayushsareen.netlify.app) | [LinkedIn](https://linkedin.com/in/ayush-sareen)

