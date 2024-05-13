# adult-census-income-classification 👾

### Requirements

**The project was developed with:**
 - Jupyter notebook
 - Python
 - Matplotlib
 - Scikit-learn
 - pandas
 - numpy

### ✔ Purpose and Aim of This Assignment

- Predict whether income exceeds $50K/yr based on census data. Also known as "Census Income" dataset.
- Prediction task is to determine whether a person makes over 50K a year.
- Dataset is from https://archive.ics.uci.edu/dataset/2/adult
- In order to achieve this task, we perform;
  - various data preprocessing, 
  - feature engineering steps,
  - trying different regression models 

#### This project is the final project of the "Supervised Machine Learning: Classification" course given by IBM on Coursera. I have completed the course and here is the [link](https://www.coursera.org/account/accomplishments/verify/HTWETW6ST7R5)

### ✔ Results and Insights
- Balancing the data is crucial because it ensures that the predictive model is not biased towards the majority class, leading to more accurate and fair predictions. When one class heavily outweighs the others, the model may become biased, neglecting the minority classes.
- This part initializes classifiers for a multi-output classification task. SVM, Random Forest, Decision Tree, KNN, and Naive Bayes classifiers are set up using scikit-learn's MultiOutputClassifier. Each classifier is capable of handling multiple target variables simultaneously, making them suitable for multi-output classification tasks.

- Gradient Boosting constructs a strong ensemble model that excels at predictive accuracy. Additionally, it is less prone to overfitting compared to other ensemble methods.

- Gradient Boosted Classifier model appears to perform the best among the evaluated models, achieving the highest accuracy and a good balance between precision and recall. However, it's essential to consider the specific requirements and constraints of the problem domain when selecting the most suitable model.

- There is an implication that the models' robustness could be further tested by examining more metrics beyond just AUC and accuracy, and by using techniques like cross-validation to assess the model's generalizability.  Or maybe withh different predictive models.



