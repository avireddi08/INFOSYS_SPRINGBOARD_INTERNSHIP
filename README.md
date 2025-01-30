# INFOSYS_SPRINGBOARD_INTERNSHIP

# Project: AI-Driven Patient Follow-Up and Health Outcome Prediction System for Telemedicine

This repository contains multiple AI-driven projects designed to aid in the medical field. The goal of these projects is to assist healthcare professionals by automating tasks related to patient follow-ups, health outcome predictions, medical conversations, and summaries. Below is a brief description of each project in this repository.

# 1. Lung_Cancer_Level_Prediction:

This project predicts the severity or stage of lung cancer based on patient data using machine learning models. It utilizes K-Nearest Neighbors (KNN) and Random Forest Classifier to analyze key medical            attributes such as age, air pollution exposure, genetic risk, smoking history, etc. and symptoms to assess cancer progression. The dataset used for project consists of 1000 patient records with 25 features.       Data preprocessing includes handling missing values, encoding categorical variables, and normalizing numerical features. Model performance is evaluated using accuracy scores, confusion matrix, and                 classification reports.
      
Results:
      
KNN: 99.67% accuracy
      
Random Forest: 100% accuracy
      
This project provides valuable insights into lung cancer risk assessment and can aid in early diagnosis and treatment planning.
 
# 2. Medical_Conversation_Analysis:
   
This project analyzes doctor-patient conversations to extract insights such as predicting patient conditions, identifying medical terms, and detecting sentiment. It uses Natural Language Processing (NLP) techniques, including tokenization, stopword removal, stemming, lemmatization for text preprocessing. Regular expressions and machine learning models are used for age and gender extraction, while TextBlob applied for sentiment analysis. Conversations are classified into severity levels (High, Medium, Low, Normal) based on medical keywords, and sentiment polarity is analyzed to understand emotional trends. The project is implemented using Python, with libraries such as NLTK, Pandas, Matplotlib, and Seaborn for data processing, visualization, and analysis. The processed data is stored as csv file for further use and analysis

# 3. Medical_Conversation_Dashboard:
   
This project implements a dashboard that provides interactive visualizations and insights from medical conversation data. The dashboard includes various metrics such as sentiment distribution, condition severity, and conversation analysis. The goal is to provide healthcare professionals with a quick overview of patient interactions. The project is built using Python, with Streamlit for dashboard development, Pandas and NumPy for data processing, NLTK for NLP tasks, TextBlob for sentiment analysis, and Matplotlib, Seaborn, and Plotly for visualizations.

Dashboard Demo: https://github.com/Medical_Dashboard_Demo

# 4. Medical_Summary_Generator:
   
This project focuses on automatically generating concise and informative medical summaries from patient conversations or medical records. It processes unstructured medical text, extracts key details and generates structured summaries that can assist healthcare providers in quick decision-making and patient management. The system utilizes Natural Language Processing (NLP) techniques, including text summarization algorithm (abstractive summarization), and keyword extraction method to highlight the most relevant information. The project is implemented using Python, with NLTK for text processing, T5-based transformer model for advanced summarization, and Pandas for handling structured data.

# 5. Patient_FollowUp_Scheduler:
   
This project automates patient follow-up scheduling using Cal.com's API, ensuring timely and efficient appointment management based on patient severity levels. The system prioritizes high-risk patients by scheduling follow-ups at shorter intervals while assigning standard follow-ups for lower-risk cases. The project is implemented using Python, with Cal.com API for scheduling. This system enhances healthcare management by ensuring prompt follow-ups and improving patient outcomes.

