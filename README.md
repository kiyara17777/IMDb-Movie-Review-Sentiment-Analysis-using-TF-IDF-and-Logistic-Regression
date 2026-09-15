# IMDb Movie Review Sentiment Analysis

A Natural Language Processing (NLP) project that classifies movie reviews as **Positive** or **Negative** using **TF-IDF feature extraction** and **Logistic Regression**.

## 📌 Overview

Sentiment analysis is a Natural Language Processing task used to determine the emotional polarity of textual data.

In this project, a machine learning model is trained on IMDb movie reviews to learn patterns associated with positive and negative sentiment and classify previously unseen reviews.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Kaggle Dataset

## 📂 Dataset

The project uses the **IMDb Dataset of 50K Movie Reviews**.

The dataset contains:

- `review` — Movie review text
- `sentiment` — `positive` or `negative`

The dataset contains approximately **50,000 labeled movie reviews** with a balanced distribution of positive and negative reviews.

The dataset is downloaded from Kaggle and is not included in this repository.

## 🔄 Methodology

The project follows this pipeline:

```text
IMDb Movie Reviews
        ↓
Data Exploration
        ↓
Duplicate & Missing Value Check
        ↓
Text Preprocessing
        ↓
Train-Test Split
        ↓
TF-IDF Feature Extraction
        ↓
Logistic Regression
        ↓
Sentiment Prediction
        ↓
Model Evaluation
```

## 🧹 Text Preprocessing

The reviews are cleaned before feature extraction by:

- Converting text to lowercase
- Removing HTML tags
- Removing special characters
- Removing unnecessary spaces

## 🧠 Feature Extraction

### TF-IDF

Term Frequency-Inverse Document Frequency (TF-IDF) is used to transform movie review text into numerical feature vectors.

This allows the machine learning model to identify patterns in the words used in positive and negative reviews.

## 🤖 Machine Learning Model

### Logistic Regression

Logistic Regression is used for binary sentiment classification.

The model predicts:

```text
0 → Negative
1 → Positive
```

## 📊 Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The notebook also demonstrates sentiment prediction on new movie reviews that were not part of the training dataset.

## 🔍 Example

Given a review such as:

```text
"This movie was absolutely amazing. The acting was brilliant and the story was very interesting."
```

The model predicts:

```text
Sentiment: POSITIVE
```

Similarly, a review describing a boring story and poor acting may be classified as:

```text
Sentiment: NEGATIVE
```

## 📓 Notebook

The complete implementation is available in:

`IMDb_Sentiment_Analysis.ipynb`

The notebook contains the complete workflow including data exploration, preprocessing, TF-IDF feature extraction, model training, evaluation, and prediction on new reviews.

## 🚀 How to Run

### Option 1 — Google Colab

Open the notebook in Google Colab and execute the cells sequentially.

### Option 2 — Local Environment

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
```

Then open the notebook using Jupyter Notebook or JupyterLab.

## ⚠️ Dataset Note

The IMDb dataset is a standard benchmark dataset for sentiment classification. This project uses it for educational purposes to demonstrate a traditional machine-learning approach to NLP.

## 🎯 Learning Outcomes

This project demonstrates:

- Natural Language Processing
- Text preprocessing
- Sentiment classification
- TF-IDF feature extraction
- Logistic Regression
- Train-test splitting
- Model evaluation
- Confusion matrix analysis
- Prediction on unseen reviews

## 👩‍💻 Author

**Kiyara Chandrawat**  
B.Tech Computer Science & Engineering  
Indira Gandhi Delhi Technical University for Women (IGDTUW)
