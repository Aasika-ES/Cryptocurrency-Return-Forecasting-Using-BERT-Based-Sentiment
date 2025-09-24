# Cryptocurrency Return Prediction Using BERT-Based Sentiment Analysis

**Master’s Thesis Project – M.Sc. Data Science / Finance Applications**

This project presents an **end-to-end framework for predicting cryptocurrency returns** by leveraging **investor sentiment extracted from financial news, Reddit posts, and Tweets** using **BERT-based NLP models**. The pipeline combines **natural language processing, machine learning, and quantitative financial modeling**, and includes trading simulations to evaluate predictive performance.

---

## Project Overview

The project is divided into two main parts:

### **Part 1: BERT-Based Sentiment Classification**
- **Data Collection:** Scraped historical price data for Bitcoin and Ethereum, as well as financial news, Reddit posts, and Tweets.  
- **Sentiment Labeling:** Used a weak-label approach with the Financial Phrasebank dataset and a zero-shot BART classifier to generate pseudo-labels.  
- **BERT Model Training:** Fine-tuned BERT-based classifiers (BERT-Frozen, BERT-Unfrozen, BERT-Context) with hyperparameter optimization for sentiment prediction.  
- **Data Integration:** Combined price and sentiment data into a single dataset, assigning predicted sentiment labels for further analysis.

### **Part 2: Return Prediction and Trading Simulation**
- **Feature Engineering:** Added price, macroeconomic, blockchain, technical indicators, and lagged variables to prepare data for financial models.  
- **Prediction Modeling:** Applied Bayesian hyperparameter optimization to train multiple models and analyzed the contribution of sentiment features using variance inflation factor analysis.  
- **RNN and LSTM Models:** Implemented recurrent neural networks (RNNs) and LSTM models to enhance time-series forecasting.  
- **Trading Simulation:** Conducted backtesting over multiple periods to evaluate model predictions and simulated trading strategies, generating detailed performance metrics.

---

## Tools & Technologies
- **Programming & Analysis:** Python, pandas, NumPy, scikit-learn  
- **Machine Learning & NLP:** BERT, FinBERT, BART, Transformers, Bayesian Optimization  
- **Deep Learning:** RNN, LSTM  
- **Financial Modeling:** Trading simulation frameworks, technical indicators  

---

## Key Outcomes
- Developed a robust pipeline that demonstrates how **investor sentiment can improve cryptocurrency return predictions**.  
- Generated actionable insights for quantitative trading strategies and risk assessment in crypto markets.  
- Showcased the integration of **NLP and financial modeling** for research-oriented applications.  

---

## Repository Structure

