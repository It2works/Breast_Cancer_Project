# Breast Cancer Project

## Overview
This project aims to develop machine learning models for the classification of breast cancer based on various features. The dataset used contains a collection of features computed from digitized images of breast mass, which are used to predict whether a tumor is malignant or benign.

## Dataset
The dataset used in this project is sourced from kaggle the link: https://www.kaggle.com/datasets/reihanenamdari/breast-cancer.
It consists of 4025 instances and 16 features, including attributes such as Age, Race, Marital Status, T Stage , N Stage , Tumor Size, Progesterone Status, Estrogen Status,  etc.


## Models Used
Several machine learning algorithms were trained and evaluated for the breast cancer classification task, including:
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Gradient Boosting

## Evaluation
The models were evaluated using various performance metrics such as accuracy, precision, recall, F1-score, ROC AUC score, and average precision score. Additionally, confusion matrices were utilized to visualize the model's performance.

## Conclusion
Based on the evaluation results:

Gradient Boosting, Decision Tree, Naive Bayes, SVM, Random Forest: These models achieved exceptional performance, correctly predicting the majority of instances in both classes with no false positives or false negatives.

KNN (K-Nearest Neighbors): This model exhibited some misclassifications, particularly in distinguishing between instances of class 'Alive' and 'Dead'.
## Usage
To use this project:
1. Clone the repository to your local machine.
2. Run the main script or Jupyter notebook to train and evaluate the machine learning models.
3. Experiment with different preprocessing techniques and model parameters to improve performance.
 
## Contributors
- Ayari Mohamed Ghassen

## License
This project is licensed under the MIT License - see the MIT(LICENSE) file for details.

---

Feel free to customize the content according to your specific project details and requirements.
