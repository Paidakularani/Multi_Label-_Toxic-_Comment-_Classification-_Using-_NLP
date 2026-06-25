# Multi Label Toxic Comment Classification Using NLP
Social media users often face abusive and toxic comments that discourage them from expressing their opinions and engaging in discussions. This project uses NLP and Machine Learning to detect and classify toxic comments into multiple categories and predict toxicity probabilities to help create safer online communication

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- Matplotlib
- Seaborn
  
## 🔄 Project Workflow

### 1. Data Preprocessing
- Removed special characters
- Converted text to lowercase
- Removed stopwords
- Applied stemming

### 2. Feature Extraction
- TF-IDF Vectorization

### 3. Model Building
- Multinomial Naive Bayes
- Logistic Regression
- OneVsRest Classifier for Multi-Label Classification

### 4. Model Evaluation
- Accuracy Score
- Hamming Loss
- ROC-AUC Score
  
## 📈 Key Features

✔ Text Cleaning and Preprocessing

✔ TF-IDF Feature Engineering

✔ Multi-Label Classification

✔ Toxic Comment Detection

## 🎯 Results

The model successfully classifies comments into multiple toxicity categories and helps automate content moderation for online platforms.

## 🔗 Dataset Link
https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data?select=train.csv.zip
