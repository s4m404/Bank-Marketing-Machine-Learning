# Bank Marketing Machine Learning Project

This project predicts whether a customer subscribed to a bank term deposit after a marketing contact. It compares three supervised classification models and uses K-means clustering to explore customer groups.

## Models

- Logistic Regression
- Gaussian Naive Bayes
- Neural Network using `MLPClassifier`
- K-means clustering using age and call duration

## Results

| Model | Accuracy | Precision | Recall | AUC |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.9093 | 0.6501 | 0.4224 | 0.9390 |
| Gaussian Naive Bayes | 0.7591 | 0.2965 | 0.8287 | 0.8508 |
| Neural Network | 0.9109 | 0.6359 | 0.4892 | 0.9392 |

The Neural Network achieved the highest accuracy and AUC. Logistic Regression produced almost the same AUC with slightly higher precision, while Gaussian Naive Bayes achieved the highest recall.

## Files

- `Bank_Marketing_Project.ipynb`: complete Colab notebook with saved outputs
- `Bank_Marketing_Project_Report.pdf`: project report

## Running the Notebook

1. Open the notebook in Google Colab.
2. Select **Runtime > Run all**.
3. Upload `Bank Marketing.csv` when requested.

The dataset is not included in this repository.

## Tools

Python, pandas, Matplotlib, Seaborn and scikit-learn.
