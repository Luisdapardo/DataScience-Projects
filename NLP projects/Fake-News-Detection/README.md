# Fake News Detection using Writing Style and Text Features

## Project Overview
This project addresses the fake news detection problem using two different approaches:

- A traditional word-based model (TF-IDF)
- A lightweight writing-style-based model using linguistic features such as sentence length, capitalization ratio, punctuation density, and sentiment score

The objective is to evaluate whether a computationally simpler model can achieve competitive performance compared to traditional NLP techniques.

---
## Approaches

### 1. Writing Style Model
- Feature extraction based on writing style characteristics
- Includes structural and linguistic patterns (e.g., sentence structure, punctuation usage, text complexity)
- Focus on how something is written rather than what is written

📄 Notebook: `writing_style_model.ipynb`

---

### 2. Word Importance Model
- Feature extraction using text-based representations (e.g., Bag of Words / TF-IDF)
- Focus on word frequency and importance
- Traditional NLP classification approach

📄 Notebook: `word_importance_model.ipynb`

---

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- NLP techniques (tokenization, feature extraction)

## Results & Key Insights

- Word-based model (TF-IDF): F1-score ≈ 0.99  
- Writing-style model: F1-score ≈ 0.92  

While the word-based model achieves higher accuracy, the writing-style model offers:

- Significantly lower computational cost  
- Faster training time  
- Reduced feature complexity (5 vs. 5000 features)

This highlights a trade-off between performance and efficiency, making writing-style approaches a promising alternative in resource-constrained environments.

---

## Conclusion

The results show that while traditional word-based approaches achieve higher accuracy, writing-style features provide a lightweight and 
computationally efficient alternative. Combining both approaches could further improve fake news detection systems.

---

## Repository Structure

Fake-news-detection/
│

├── README.md

├── writing_style_model.ipynb

├── word_importance_model.ipynb
