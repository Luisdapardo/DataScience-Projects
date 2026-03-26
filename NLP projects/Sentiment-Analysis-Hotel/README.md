# Sentiment Analysis for Hotel Reviews

## Project Overview
This project applies Natural Language Processing (NLP) techniques to classify hotel reviews as positive or negative.

The goal is to analyze customer feedback and extract sentiment information to better understand customer satisfaction in the hospitality industry.

---

## Approach

- Text preprocessing (cleaning, tokenization, normalization)
- Conversion of text into numerical features (e.g., TF-IDF / vectorization)
- Training machine learning models for sentiment classification

---

## Methodology

- Data loading and preprocessing  
- Feature extraction from textual data  
- Model training for binary classification  
- Model evaluation using standard metrics  

---

## Results

- The model successfully classifies hotel reviews into sentiment categories  
- Demonstrates the effectiveness of machine learning for text classification tasks
- The model has an easy time when predicting positive sentiments from reviews (F1 score of 92%).
- In the case of Negative sentiments the model does not perform as well as with the previous category but still manages to deliver a great level of performance (F1 score of 75%).

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLP techniques  

---

## Repository Structure

```text
Sentiment-Analysis-Hotel/
├── README.md
├── sentiment_analysis_model.ipynb
