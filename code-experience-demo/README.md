# Code Experience Demo

This folder includes three Jupyter Notebooks that illustrate a complete workflow:

1. [01-cleaning-demo.ipynb](./01-cleaning-demo.ipynb) – techniques for handling missing values, outliers, and noisy records.  
2. [02-preprocessing-demo.ipynb](./02-preprocessing-demo.ipynb) – normalization, feature engineering, and categorical encoding.  
3. [03-stgnn-model-demo.ipynb](./03-stgnn-model-demo.ipynb) – implementation of a Spatio-Temporal Graph Neural Network (STGNN), including training and evaluation results (Precision, Recall, and F1-score).  

---

### Model Evaluation

The dataset used in this demo was **imbalanced** between the two classes.  
For this reason, **Accuracy** was not considered a reliable performance metric.  

Instead, the model was evaluated using:  
- **Precision** – proportion of positive predictions that are correct.  
- **Recall** – proportion of actual positives that are correctly identified.  
- **F1-score** – harmonic mean of Precision and Recall, providing a balanced measure.  

These metrics provide a more meaningful evaluation when working with imbalanced datasets.
