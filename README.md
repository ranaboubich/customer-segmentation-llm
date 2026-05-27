# Customer Segmentation & LLM-Powered Recommendations

## Description
An end-to-end machine learning project that segments customers based on 
purchasing behavior and generates personalized product recommendations 
using a large language model.

## Features
- Full data cleaning pipeline on 540K+ transactions
- RFM-inspired feature engineering
- K-Means clustering validated by 4 metrics (Elbow, Silhouette, 
  Davies-Bouldin, Calinski-Harabasz)
- LLM-powered recommendation system using Llama 3.3-70B via Groq API
- Personalized, explainable product suggestions per customer segment

## Tools & Technologies
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Groq API, Kaggle

## Dataset
UCI Online Retail Dataset — 540K+ transactions from a UK-based retailer

## How to Run
1. Download `CustomerSegmentation.ipynb` from this repository
2. Upload it to Kaggle or any Jupyter environment
3. Add your Groq API key in Kaggle Secrets under the name `GROQ_API_KEY`
4. Run all cells
