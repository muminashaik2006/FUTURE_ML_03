# Resume Screening System

## Overview

This project automates the resume screening process using Machine Learning and Natural Language Processing (NLP). The system analyzes resume content and predicts the most suitable job category based on the candidate's skills, experience, and qualifications.

The objective is to help recruiters quickly identify relevant candidates and reduce manual screening effort.

## Features

* Resume text preprocessing
* NLP-based feature extraction using TF-IDF
* Automatic resume classification
* Machine Learning model training and evaluation
* Predicts job category from resume text
* Easy to extend for recruitment applications

## Dataset

The dataset contains resumes belonging to multiple job categories such as:

* Data Science
* Web Designing
* HR
* Java Developer
* Python Developer
* Testing
* DevOps Engineer
* Network Security Engineer
* Business Analyst

Each record includes:

* Resume Text
* Job Category

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLP
* Matplotlib
* Seaborn
* Jupyter Notebook

## Workflow

1. Load resume dataset.
2. Clean and preprocess resume text.
3. Convert text into numerical features using TF-IDF Vectorization.
4. Encode job categories.
5. Split dataset into training and testing sets.
6. Train Machine Learning classifier.
7. Evaluate model performance.
8. Predict job category for new resumes.

## Machine Learning Model

Algorithm Used:

* Multinomial Naive Bayes / Random Forest / Logistic Regression (depending on implementation)

Why NLP?

* Extracts meaningful information from resumes.
* Converts unstructured text into machine-readable format.
* Improves classification accuracy.

## Applications

* HR Recruitment Automation
* Talent Acquisition
* Candidate Shortlisting
* Resume Ranking Systems
* ATS (Applicant Tracking Systems)

## Results

The model successfully classifies resumes into their respective job categories based on textual content and skills mentioned in resumes.

## Future Enhancements

* Resume Ranking Feature
* Skill Extraction
* Job Matching System
* Deep Learning Models (BERT)
* Web Deployment using Streamlit

## Author

SHAIK MUMINA
