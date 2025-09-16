# Code Experience Demo

This folder includes three Jupyter Notebooks:  

1. **Data Cleaning** – demonstrates techniques for handling missing values, outliers, and noisy records.  
2. **Data Preprocessing** – covers normalization, feature engineering, and categorical encoding.  
3. **STGNN Model** – implementation of a Spatio-Temporal Graph Neural Network (STGNN), with training and evaluation results (Precision, Recall, and F1-score).  

---

### Model Evaluation

The dataset used in this demo was imbalanced between the two classes.  
For this reason, **Accuracy** was not considered a reliable performance metric.  

Instead, the model was evaluated using:  
- **Precision** – proportion of predicted positives that are correct.  
- **Recall** – proportion of actual positives that are correctly identified.  
- **F1-score** – harmonic mean of Precision and Recall, providing a balanced measure.  

These metrics provide a more meaningful evaluation for imbalanced datasets.
