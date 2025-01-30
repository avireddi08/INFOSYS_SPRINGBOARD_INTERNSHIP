# INFOSYS_SPRINGBOARD_INTERNSHIP

# Project: AI-Driven Patient Follow-Up and Health Outcome Prediction System for Telemedicine

This repository contains multiple AI-driven projects designed to aid in the medical field. The goal of these projects is to assist healthcare professionals by automating tasks related to patient follow-ups, health outcome predictions, medical conversations, and summaries. Below is a brief description of each project in this repository.

1. Lung_Cancer_Level_Prediction:
   
This project predicts the severity or stage of lung cancer based on patient data using machine learning models. It utilizes K-Nearest Neighbors (KNN) and Random Forest Classifier to analyze key medical attributes such as age, air pollution exposure, genetic risk, smoking history, etc. and symptoms to assess cancer progression. The dataset used for project consists of 1000 patient records with 25 features. Data preprocessing includes handling missing values, encoding categorical variables, and normalizing numerical features. Model performance is evaluated using accuracy scores, confusion matrix, and classification reports.

Results:

KNN: 99.67% accuracy
Random Forest: 100% accuracy

This project provides valuable insights into lung cancer risk assessment and can aid in early diagnosis and treatment planning.

2. Medical_Conversation_Analysis:
This project analyzes doctor-patient conversations to extract insights such as predicting patient conditions, identifying medical terms, and detecting sentiment. It uses Natural Language Processing (NLP) techniques for text preprocessing, age and gender extraction, and sentiment analysis. Conversations are classified into severity levels (High, Medium, Low, Normal) based on medical keywords, and sentiment polarity is analyzed to understand emotional trends. The processed data is stored for further use and analysis.

3. Medical_Conversation_Dashboard:
This project implements a dashboard that provides interactive visualizations and insights from medical conversation data. The dashboard includes various metrics such as sentiment distribution, condition severity, and conversation analysis. The goal is to provide healthcare professionals with a quick overview of patient interactions.

4. Medical_Summary_Generator:
This project generates concise medical summaries from patient conversations or records. It processes medical texts, extracts key information, and produces summaries that can be used by healthcare providers for quick patient reference or decision-making.

5. Patient_FollowUp_Scheduler:
This project automates patient follow-up scheduling using Cal.com's API. It schedules appointments based on patient severity levels (e.g., high-risk patients) and sends reminders to doctors or support staff. The system helps ensure timely follow-up care for patients, improving healthcare management and patient outcomes.

