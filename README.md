# 📰 Fake News Detection using Machine Learning

## 📌 Project Overview

Fake news has become a major challenge in the digital era. This project uses **Machine Learning** and **Natural Language Processing (NLP)** techniques to classify news articles as **Fake** or **Real**.

The system preprocesses textual news data, converts it into numerical features using **TF-IDF Vectorization**, and evaluates multiple machine learning algorithms to identify the best-performing model.

---

## 🚀 Features

- Detects whether a news article is **Fake** or **Real**
- Text preprocessing and cleaning
- TF-IDF feature extraction
- Multiple Machine Learning models
- Performance evaluation using Accuracy, Precision, Recall and F1-Score
- Manual news prediction

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Regular Expressions (Regex)

---

## 📂 Dataset

The project uses two datasets:

- Fake.csv
- True.csv

The datasets contain news articles labeled as fake or real.

---

## ⚙️ Machine Learning Models

The following classifiers were trained and compared:

- Logistic Regression
- Decision Tree Classifier
- Gradient Boosting Classifier
- Random Forest Classifier

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 98.78% |
| Decision Tree | 99.52% |
| Gradient Boosting | 99.44% |
| Random Forest | 98.69% |

> **Best Performing Model:** Decision Tree Classifier

---

## 🧹 Text Preprocessing

The following preprocessing techniques were applied:

- Convert text to lowercase
- Remove URLs
- Remove punctuation
- Remove special characters
- Remove numbers
- Remove extra spaces

---

## 📈 Workflow

```text
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Text Preprocessing
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Train-Test Split
      │
      ▼
Machine Learning Models
      │
      ▼
Prediction
```

---

## 📁 Project Structure

```
Fake-News-Detection/
│
├── Fake News Detection using machine learning.ipynb
├── Datasets/
│   ├── Fake.csv
│   └── True.csv
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/Akshitha-1510/Fake-News-Detection.git
```

### Navigate to the project

```bash
cd Fake-News-Detection
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open the notebook in:

- Google Colab
- Jupyter Notebook
- VS Code

Run all cells to train and test the models.

---

## 📌 Future Improvements

- Deep Learning (LSTM/Bi-LSTM)
- BERT-based Fake News Detection
- Flask or Streamlit Web Application
- Real-time News URL Prediction
- Deployment on Render or Hugging Face Spaces

---

## 👩‍💻 Author

**Akshitha Kalidindi**

- GitHub: https://github.com/Akshitha-1510

---

## ⭐ If you found this project useful, consider giving it a star!
