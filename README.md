# ML-Based Sentiment Analyzer (Improved Version)


## Overview
This project is a medium-level **machine learning sentiment analyzer** made for the **Fundamentals of AI** practical.  
It classifies sentences into three categories:
1) Positive
2) Negative
3) Neutral


This improved version includes:

1) Model accuracy calculation
2) Probability scores for each class
3) Loop-based user input
4) Flowchart and architecture diagram
5) Clean Jupyter Notebook implementation



---


## Features (Updated)
1) Machine learning–based sentiment classification  
2) Uses **CountVectorizer (Bag of Words)**  
3) Uses **Multinomial Naive Bayes**  
4) Displays probabilities for all classes
5) Evaluates accuracy on a small test dataset
6) Easy, understandable logic for viva and external exam

---


## Dataset
A custom dataset containing 15 sentences:

- 5 Positive
- 5 Negative
- 5 Neutral



---


## Flow Diagram

  ┌────────────────────────┐ │ User Input │ │ (Sentence/Statement) │ └────────────┬───────────┘ │ ▼ ┌────────────────────────┐ │ Text Preprocessing │ │ - Lowercasing │ │ - Tokenization │ └────────────┬───────────┘ │ ▼ ┌────────────────────────┐ │ Feature Extraction │ │ CountVectorizer │ │ (Bag of Words Model) │ └────────────┬───────────┘ │ ▼ ┌─────────────────────────┐ │ ML Model Training │ │ Multinomial Naive Bayes │ └────────────┬────────────┘ │ ▼ ┌─────────────────────────┐ │ Prediction │ │ - Sentiment Label │ │ - Class Probabilities │ └────────────┬────────────┘ │ ▼ ┌──────────────────────────┐ │ Output │ │ Positive/Negative/Neutral│ │ + Probabilities │ └──────────────────────────┘


---


## Model Accuracy
A small test dataset was used to check accuracy:

Model accuracy on test set: XX.XX % True labels: [...] Predicted labels: [...]

---


## Example Output

Enter a sentence: I am happy today

Predicted Sentiment: positive Class probabilities: negative : 0.05 neutral  : 0.10 positive : 0.85

---

##  How to Run

### Install library

pip install scikit-learn

### Run the script

python sentiment_analyzer.py


---


## File Structure

ai-sentiment-analyzer/ │ ├── sentiment_analyzer.ipynb ├── sentiment_analyzer.py ├── requirements.txt └── README.md

                     

---
## Screenshots
<img width="583" height="190" alt="ai-sentiment-analyzer-test1" src="https://github.com/user-attachments/assets/2febc088-c096-4f7e-9be7-5f8322e9a770" />
<img width="583" height="190" alt="ai-sentiment-analyzer-test2" src="https://github.com/user-attachments/assets/0770a747-a030-4e37-9da4-20cd9fe14fe6" />
<img width="583" height="190" alt="ai-sentiment-analyzer-test3" src="https://github.com/user-attachments/assets/d62d47ea-1b1c-4130-9067-ae9afaf3d7d8" />



## Author
**Kunal Pawar**  

Program: B.Tech CSE Core
Course: Fundamentals of AI ML
