# 🌍 Language Detection using NLP

This project demonstrates how to detect the **language of a given text** using machine learning and natural language processing (NLP) techniques. Implemented using Python in **Google Colab**, it leverages TF-IDF vectorization and a classification model to identify the language.

[🔗 Open in Colab](https://colab.research.google.com/github/joshikaselvam/Language-Detection-using-NLP/blob/main/Language_detection.ipynb)


---

## 📌 Project Overview

- 🔤 **Objective**: Identify the language of short text snippets (English, French, Spanish, etc.)
- 🧠 **ML Model**: Multinomial Naive Bayes
- 📚 **Tech Stack**: Python, Scikit-learn, Pandas, Google Colab
- 📊 **Features**: 
  - Text preprocessing
  - Count vectorization
  - Model training and testing
  - Evaluation using accuracy and confusion matrix

---

## 🛠️ How It Works

1. **Preprocessing**  
   Clean and normalize the text (lowercasing, removing punctuation, etc.)

2. **Feature Extraction**  
   Use Count Vectorizer  to convert text to numeric features

3. **Model Training**  
   Train a Multinomial Naive Bayes classifier on labeled multilingual data

4. **Evaluation**  
   Accuracy and confusion matrix are used to evaluate the model

---

## 📈 Sample Output

| Input Text              | Predicted Language |
|-------------------------|--------------------|
| Hello, how are you?     | English            |
| Bonjour tout le monde   | French             |
| Hola, ¿cómo estás?      | Spanish            |

---

## 📂 Dataset

- Synthetic or real multilingual sentence samples
- Labeled by language codes (en, fr, es, etc.)
- You can expand it using open datasets from [Kaggle](https://www.kaggle.com) or [HuggingFace Datasets](https://huggingface.co/datasets)

---

## 📦 Requirements

Install the dependencies with:

```bash
pip install pandas scikit-learn matplotlib


 👩‍💻 Author

Joshika Selvam
* 🌐 [GitHub Profile](https://github.com/joshikaselvam)

