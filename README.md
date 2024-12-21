#  WOC7015 Exercise 3.1

I have chosen the K-Nearest Neighbors (KNN) algorithm to train and test the dataset. 

Here is the comparison of the results:

| **Algorithm**              | **Accuracy** | **Precision (Neg)** | **Precision (Pos)** | **Recall (Neg)** | **Recall (Pos)** | **F1-Score (Neg)** | **F1-Score (Pos)** | **Macro Avg F1** | **Weighted Avg F1** |
|----------------------------|--------------|---------------------|---------------------|------------------|------------------|--------------------|--------------------|------------------|---------------------|
| **Multinomial Naive Bayes** | 0.80         | 0.89                | 0.78                | 0.43             | 0.97             | 0.58               | 0.87               | 0.72             | 0.78                |
| **Decision Tree**          | 0.92         | 0.91                | 0.93                | 0.84             | 0.96             | 0.88               | 0.94               | 0.91             | 0.92                |
| **Random Forest**          | 0.92         | 0.94                | 0.91                | 0.78             | 0.98             | 0.86               | 0.94               | 0.90             | 0.91                |
| **Support Vector Machine** | 0.87         | 0.92                | 0.85                | 0.64             | 0.97             | 0.76               | 0.91               | 0.83             | 0.86                |
| **Logistic Regression**    | 0.87         | 0.96                | 0.84                | 0.61             | 0.99             | 0.75               | 0.91               | 0.83             | 0.86                |
| **K-Nearest Neighbors**         | 0.79         | 0.74                | 0.81                | 0.55             | 0.91             | 0.63               | 0.86               | 0.74             | 0.79                |
