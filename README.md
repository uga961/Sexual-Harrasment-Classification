
# Sexual Harassment Classification (Multi-Class)

This project is part of an **Interdisciplinary Research Initiative** at **Sathyabama Institute of Science and Technology**, aiming to use Artificial Intelligence for detecting and classifying different types of sexual harassment based on textual reports.

## 🧠 Objective

To classify instances of sexual harassment into one of the following categories based on the text:
- **Commenting**: Inappropriate or offensive verbal remarks.
- **Staring**: Uncomfortable gazing or leering.
- **Touching**: Unwanted or inappropriate physical contact.

## 📁 Dataset

The model is trained and tested on two datasets:

- `train.csv`: Contains labeled training data with categories: `commenting`, `staring`, and `touching`.  
- `test.csv`: Contains unlabeled or partially labeled test data used to evaluate model performance.

Each entry includes:
- `text`: Description of the incident  
- `label`: Type of harassment (`commenting`, `staring`, `touching`)

> 🔐 The dataset is anonymized and filtered to maintain privacy and adhere to ethical standards.

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: pandas, NumPy, scikit-learn, NLTK / spaCy  
- **Models**: Multiclass classification using Logistic Regression, SVM, or Random Forest  
- **Preprocessing**: Text cleaning, tokenization, stopword removal, lemmatization, and TF-IDF vectorization  


## 📊 Evaluation Metrics

- Accuracy
- Precision, Recall, and F1-score (for each class)
- Confusion Matrix

## ⚖️ Ethics and Responsibility

This model is developed **strictly for academic research**. We recognize the sensitivity of the topic and commit to ensuring responsible use of this technology.


## 📌 Disclaimer

The model is in a prototype stage and should not be used for real-world decisions without expert validation and further testing on larger datasets.

---
