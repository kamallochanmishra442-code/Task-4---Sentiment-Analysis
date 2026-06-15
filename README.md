# 🎯 Task 4 - Sentiment Analysis
### CodTech IT Solutions — Data Analytics Internship

---

## 📋 Internship Details

| Field | Details |
|-------|---------|
| **Name** | Kamal Lochan Mishra |
| **Company** | CODTECH IT Solutions Pvt. Ltd. |
| **Intern ID** | CTIS05S1 |
| **Domain** | Data Analytics |
| **Duration** | 4 Weeks |
| **Mentor** | Neela Santhosh Kumar |

---

## 📌 Objective

Perform **Sentiment Analysis** on textual data (e.g., product reviews, tweets) using **Natural Language Processing (NLP)** techniques to classify text as **Positive**, **Negative**, or **Neutral**.

---

## 📁 Files in This Repository

```
Task-4-Sentiment-Analysis/
│
├── sentiment_analysis.ipynb    ← Main Jupyter Notebook (all code here)
├── README.md                   ← This file
└── outputs/
    ├── sentiment_distribution.png
    ├── wordclouds.png
    ├── polarity_subjectivity.png
    ├── confusion_matrix.png
    └── model_comparison.png
```

---

## 🛠️ Libraries & Tools Used

| Library | Purpose |
|---------|---------|
| `pandas` | Data manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical plots |
| `nltk` | NLP preprocessing (tokenization, stopwords, lemmatization) |
| `textblob` | Lexicon-based sentiment scoring |
| `wordcloud` | Word cloud visualization |
| `scikit-learn` | TF-IDF vectorization + Logistic Regression |

---

## 🔄 Workflow / Steps Followed

### Step 1 — Data Loading
- Created a dataset of 20 product reviews with labeled sentiments (positive, negative, neutral)

### Step 2 — Data Preprocessing (NLP Pipeline)
- **Lowercasing** text
- **Removing** special characters, URLs, numbers
- **Tokenization** using NLTK
- **Stopword removal**
- **Lemmatization** (converting words to root form)

### Step 3 — Exploratory Data Analysis (EDA)
- Sentiment distribution (bar chart + pie chart)
- Review length analysis by sentiment
- Word clouds for each sentiment category

### Step 4 — Method 1: TextBlob (Lexicon-Based)
- Calculated **polarity** score (−1 to +1) and **subjectivity**
- Classified reviews based on polarity threshold
- Evaluated accuracy against true labels

### Step 5 — Method 2: ML Model (TF-IDF + Logistic Regression)
- **TF-IDF Vectorization** to convert text to features
- **Logistic Regression** classifier trained on 75% data
- Evaluated on 25% test data

### Step 6 — Model Evaluation
- Accuracy Score
- Classification Report (Precision, Recall, F1-Score)
- Confusion Matrix heatmap

### Step 7 — Live Predictions
- Tested both models on new, unseen reviews

---

## 📊 Results & Insights

| Model | Accuracy |
|-------|----------|
| TextBlob (Lexicon-Based) | ~65–75% |
| Logistic Regression (TF-IDF + ML) | ~75–85% |

### Key Insights:
- ✅ ML approach outperforms rule-based TextBlob for structured review data
- ✅ Positive reviews tend to use stronger/enthusiastic language
- ✅ Neutral sentiment is the most difficult to classify correctly
- ✅ TF-IDF captures context better than simple polarity scoring
- ✅ For large-scale datasets, BERT/RoBERTa models would give even higher accuracy

---

## ▶️ How to Run This Notebook

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/CodTech-Internship.git
   cd Task-4-Sentiment-Analysis
   ```

2. **Install required libraries:**
   ```bash
   pip install pandas numpy matplotlib seaborn nltk textblob wordcloud scikit-learn
   ```

3. **Open the notebook:**
   ```bash
   jupyter notebook sentiment_analysis.ipynb
   ```

4. **Run all cells** (Kernel → Restart & Run All)

---

## 📷 Output Visualizations

- 📊 Sentiment Distribution (Bar + Pie Chart)
- ☁️ Word Clouds (Positive / Negative / Neutral)
- 🔵 Polarity vs Subjectivity Scatter Plot
- 🔴 Confusion Matrix Heatmap
- 📈 Model Accuracy Comparison

---

## ✅ Deliverable

A complete **Jupyter Notebook** showcasing:
- Data Preprocessing
- Model Implementation (Lexicon + ML)
- Visualizations & Insights

---

*CodTech IT Solutions Pvt. Ltd. — Data Analytics Internship*
