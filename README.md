# SpamShield
Email Spam Detection is a machine learning project that identifies whether an email is spam (unwanted) or ham (legitimate). It analyzes the content of an email using Natural Language Processing (NLP) and predicts if it's spam based on patterns found in past emails.  

Working:
1.Data Collection – A dataset of emails (spam & ham) is used.
2.Preprocessing – Text is cleaned by removing stopwords, punctuation, and special characters.
3.Feature Extraction – Convert emails into numerical form using TF-IDF (Term Frequency-Inverse Document Frequency).
4.Model Training – Train a machine learning model (e.g., Naïve Bayes or Logistic Regression) to classify emails.
5.Prediction – When a new email is entered, the model predicts if it's spam or not spam.

Tools & Technologies Used:
 Python – Programming Language
 Pandas, NumPy – Data Processing
 NLTK – Text Cleaning
 Scikit-Learn – Machine Learning
 Streamlit – Web App for User Interface
 Google Colab – Runs everything in a browser
