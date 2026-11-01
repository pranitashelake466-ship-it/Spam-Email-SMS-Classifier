# Spam Email and SMS Classifier using Machine Learning

## Project Overview

This project develops a Machine Learning-based Spam and Ham Message Classification System using Natural Language Processing (NLP), TF-IDF Vectorization, and Logistic Regression.

The model analyzes text messages and predicts whether a message is Spam (unwanted message) or Ham (legitimate message).

## Dataset

The project uses the **UCI SMS Spam Collection Dataset**.

- Total Messages: 5,572
- Ham Messages: 4,825
- Spam Messages: 747
- Ham Label: 0
- Spam Label: 1

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorizer
- Logistic Regression
- Matplotlib
- Seaborn
- Joblib
- Google Colab

## Project Workflow

1. Dataset Loading and Exploration
2. Exploratory Data Analysis (EDA)
3. Text Preprocessing and Cleaning
4. Label Encoding
5. Train-Test Splitting
6. TF-IDF Feature Extraction
7. Logistic Regression Model Training
8. Model Prediction
9. Model Evaluation
10. Confusion Matrix Visualization
11. Interactive Spam Message Prediction
12. Model and Vectorizer Saving

## Model Performance

The Logistic Regression model achieved the following results:

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 96.50% |
| Precision | 100.00% |
| Recall | 73.83% |
| F1 Score | 84.94% |

## Confusion Matrix

The confusion matrix shows the actual and predicted classifications of Spam and Ham messages.

- True Negative: 966
- False Positive: 0
- False Negative: 39
- True Positive: 110

## Sample Predictions

**Spam Message:**

Congratulations! You won a free prize. Click here to claim now!

Prediction: Spam Message

Spam Probability: 93.12%

**Ham Message:**

Hello, how are you? Are you coming to college tomorrow?

Prediction: Ham Message

Ham Probability: 95.34%

## Project Files

- `Spam_Email_SMS_Classifier.ipynb` – Complete Jupyter Notebook
- `spam_dataset.csv` – Dataset used for training and testing
- `spam_classifier_model.pkl` – Trained Logistic Regression model
- `tfidf_vectorizer.pkl` – Saved TF-IDF Vectorizer
- `confusion_matrix.png` – Model evaluation visualization
- `requirements.txt` – Required Python libraries
- `README.md` – Project documentation

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   `pip install -r requirements.txt`

3. Open the Jupyter Notebook.
4. Run the notebook cells in sequence.
5. Enter your own text messages to test the classifier.

## Future Improvements

- Improve spam detection recall.
- Experiment with Naive Bayes and other classification algorithms.
- Develop a user-friendly web application using Streamlit.
- Extend testing to email datasets.

## Disclaimer

This project is developed for educational purposes. The model is trained using the UCI SMS Spam Collection Dataset. Its predictions may not correctly identify every spam or legitimate message.
