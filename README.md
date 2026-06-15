# 🎬 IMDb Movie Review Sentiment Analysis using NLP
   
## 📌 Project Overview

This project focuses on **Sentiment Analysis** using **Natural Language Processing (NLP)** techniques on the IMDb Movie Review dataset.
The goal of this project is to classify movie reviews as either **Positive** or **Negative** using Machine Learning.

The project demonstrates the complete NLP workflow including:

* Text preprocessing 
* Data cleaning
* TF-IDF vectorization
* Logistic Regression model training
* Sentiment prediction
* Model evaluation    

---
      
# 🚀 Technologies Used

* Python
* Pandas
* NumPy  
* Matplotlib
* Seaborn
* NLTK
* Scikit-learn
* Regular Expressions (re)

---

# 📂 Dataset

Dataset Used: **IMDb Movie Review Dataset**

The dataset contains:

* Movie reviews
* Sentiment labels (Positive / Negative)

---

# 🧠 NLP Concepts Used

## ✔ Text Preprocessing

The review text was cleaned using:

* Lowercase conversion
* HTML tag removal
* Punctuation removal
* Number removal
* Stopword removal
* Tokenization
* Stemming
* Lemmatization

---

## ✔ Feature Engineering

Used **TF-IDF Vectorization** with:

* Maximum Features: 5000
* N-grams: Unigrams & Bigrams

---

## ✔ Machine Learning Model

Model Used:

* Logistic Regression

The model was trained to classify movie reviews into:

* Positive Sentiment
* Negative Sentiment

---

# 📊 Model Evaluation

The model performance was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

Visualization:

* Heatmap using Seaborn

---

# 🔍 Project Workflow

```text
Dataset Collection
        ↓
Data Cleaning
        ↓
Text Preprocessing
        ↓
TF-IDF Vectorization
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Prediction & Evaluation
        ↓
Sentiment Prediction
```

---

# 📁 Project Structure

```text
IMDb-Sentiment-Analysis/
│
├── imdb_project.ipynb
├── IMDB Dataset.csv
├── README.md
└── requirements.txt
```

---

# 📌 Sample Prediction

```python
sample = "A wonderful little production"
print(predict_sentiments(sample))
```

### Output

```text
positive
```

---

# 📈 Key Learning Outcomes

Through this project, I learned:

* NLP preprocessing techniques
* Text vectorization using TF-IDF
* Sentiment classification using Machine Learning
* Model evaluation techniques
* Data visualization using Seaborn & Matplotlib

---

# 💡 Future Improvements

Possible future enhancements:

* Try Deep Learning models (LSTM / GRU)
* Deploy using Streamlit or Flask
* Hyperparameter tuning
* Add more advanced NLP techniques
* Use Word Embeddings (Word2Vec / GloVe)

---

# 📷 Output Visualization

The project also includes:

* Confusion Matrix Heatmap
* Prediction outputs
* Top positive and negative words

---

# 🤝 Contribution

Contributions and suggestions are welcome.
Feel free to fork this repository and improve the project.

---

# 📜 License

This project is for educational and learning purposes.

---

# 👨‍💻 Author

Sriram Ravichandran
