# liverpool_KoBERT
Lee, Hocheol_DISSERTATION python code 

# Sentiment Analysis of Cardiovascular and Cerebrovascular Diseases Patients Using the KoBERT Modeling

This repository contains the full implementation of a master's dissertation project submitted to the University of Liverpool, focusing on sentiment analysis using a Korean BERT-based model (KoBERT). The study leverages public web data to classify emotional experiences of patients after undergoing cardiovascular or cerebrovascular surgery in South Korea.

## 📘 Dissertation Information

- **Dissertation Title**: Sentiment Analysis of Cardiovascular and Cerebrovascular Diseases Patients Using the KoBERT Modeling
- **Author**: Hocheol Lee (이호철)
- **Degree**: Master of Science (MSc) in Data Science and Artificial Intelligence  
- **Institution**: University of Liverpool  
- **Supervisors**:  
  - Dr. Kathleen M. Kelm  
  - Dr. Hisham AbouGrad  
- **Submission Date**: June 30, 2025  
- **Ethics Statement**: No personally identifiable data was used. All data sources are publicly accessible.

## 🧠 Project Overview

Postoperative care for patients with cardiovascular and cerebrovascular diseases often lacks structured emotional support, especially during the transition from inpatient to outpatient care. This project uses artificial intelligence and natural language processing (NLP) to classify Korean patient sentiments and map them onto the **Transitional Care Model (TCM)**.

### Objectives

1. Collect patient-authored narratives using Naver Blog API
2. Preprocess and clean Korean-language textual data
3. Train a sentiment classifier using **KoBERT**
4. Categorise emotions into **TCM** dimensions:  
   - Health Status  
   - Care Resources  
   - Care Demand  
   - Interaction with Healthcare Professionals  
   - Mental State
5. Evaluate and visualise the results using statistical tools and word clouds

## 🛠️ Installation

This repository was developed in **Google Colab** and requires the following packages:

```bash
pip install torch transformers gluonnlp konlpy mecab-python sentencepiece wordcloud matplotlib
