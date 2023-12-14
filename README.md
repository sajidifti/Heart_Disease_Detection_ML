# Predicting Heart Disease Using Machine Learning Algorithms

The field of Machine Learning is exceptionally prevalent and broadly used with completely different viewpoints. It is exceptionally well known within the field of anticipating classification and relapse issues. This study focused on different supervised and classification models such as Logistic Regression, Decision Tree Classifier, SVM, Random Forest Classifier, AdaBoost Classifier, KNN Classifier. Different parameters are used here in Neural Network, AdaBoost Classifier and Decision Tree Classifiers. The way the models work well or not depends a lot on how we get the data ready and what types of models we use. The study found that using "Random Forest" results in the highest accuracy.

## Dataset

This notebook uses the [HEART DISEASE DATASET (COMPREHENSIVE)](https://ieee-dataport.org/open-access/heart-disease-dataset-comprehensive "HEART DISEASE DATASET (COMPREHENSIVE) from IEEE Dataport") from IEEE Dataport. The dataset is curated by combining 5 popular heart disease datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:

1. Cleveland
2. Hungarian
3. Switzerland
4. Long Beach VA
5. Statlog (Heart) Data Set.

The dataset consists of 1190 instances with 11 features. These datasets were collected and combined at one place to help advance research on CAD-related machine learning and data mining algorithms, and hopefully to ultimately advance clinical diagnosis and early treatment.

## Classifier Algorithms

In the pursuit of developing an accurate and reliable predictive model for heart disease, a diverse set of classifier algorithms was employed. Each algorithm brings its unique strengths and characteristics to the task of discerning patterns within the data, contributing to the overall robustness of the predictive model.

### 1. Logistic Regression

Logistic Regression is a fundamental classification algorithm used for predicting binary outcomes. In the context of heart disease prediction, it models the probability of occurrence based on a linear combination of input features. With its simplicity and interpretability, logistic regression serves as a valuable baseline model. It is particularly useful when exploring the relationship between independent variables and the likelihood of heart disease.

### 2. Decision Tree

Decision Trees are intuitive and interpretable models that recursively partition the data into subsets based on feature conditions. In heart disease prediction, decision trees can reveal key risk factors and provide insights into the decision-making process. However, they are prone to overfitting, which can be mitigated through techniques like pruning.

### 3. Random Forest

Random Forest is an ensemble learning method that leverages multiple decision trees to enhance predictive accuracy and generalization. By combining the outputs of individual trees, Random Forest mitigates overfitting and improves robustness. It is particularly effective in handling complex relationships within the data and identifying significant features in heart disease prediction.

### 4. K-Nearest Neighbours (KNN)

KNN is a non-parametric algorithm that classifies data points based on the majority class of their k-nearest neighbors. In heart disease prediction, KNN considers the similarity between instances, making it sensitive to local patterns. While KNN is computationally efficient, the choice of an appropriate distance metric and the determination of an optimal value for k are crucial for its success.

### 5. Support Vector Machine (SVM)

SVM is a powerful classification algorithm that works by finding a hyperplane that maximally separates classes in the feature space. SVM is effective in handling complex decision boundaries and is well-suited for datasets with high dimensionality. In heart disease prediction, SVM aims to identify a boundary that optimally distinguishes between individuals at risk and those without risk.

### 6. Naïve Bayes

Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem. Despite its "naive" assumption of feature independence, Naive Bayes performs well in various applications, including heart disease prediction. It is computationally efficient and particularly useful for datasets with a large number of features.

### 7. Adaboost

AdaBoost (Adaptive Boosting) is an ensemble learning technique that combines weak learners to create a robust model. In the context of heart disease prediction, AdaBoost sequentially trains models, giving more weight to misclassified instances. This iterative process results in a strong classifier that excels in capturing complex relationships within the data.
