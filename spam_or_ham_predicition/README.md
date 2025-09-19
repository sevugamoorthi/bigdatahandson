# 📧 Spam or Ham Prediction using Naive Bayes and NLTK

## 📌 Overview
This project classifies emails/messages as **Spam (unwanted)** or **Ham (legitimate)** using **Natural Language Processing (NLP)** techniques.  
By applying text preprocessing and the **Naive Bayes classifier**, the model learns patterns in word usage and determines whether a message is spam or not.  

### Why this project is important?
- Helps in **email filtering systems** to automatically block spam messages.  
- Reduces risks of **phishing and scams** by detecting suspicious content.  
- Demonstrates the application of **NLP + Machine Learning** in real-world cybersecurity.  

### Techniques Used
- **Naive Bayes Classifier** (MultinomialNB from scikit-learn)  
- **NLTK (Natural Language Toolkit)** for text preprocessing  
  - Tokenization  
  - Stopword removal  
  - Stemming/Lemmatization  
- Feature extraction with **Bag of Words (BoW)** or **TF-IDF**  
- Model Training & Evaluation (Accuracy, Precision, Recall, F1-Score, Confusion Matrix)    

### Dataset
Get the dataset [here](https://www.kaggle.com/datasets/phangud/spamcsv).

# Clone the repository
git clone https://github.com/username/repo-name.git

# Navigate to the project folder
cd repo folder

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
python -m notebook