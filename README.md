# Breast-Cancer-Classification-Using-Supervised-Machine-Learning-Algorithms
This project uses the sklearn Breast Cancer dataset to classify tumors as benign or malignant using five supervised learning models. After preprocessing and scaling the data, each model is trained and evaluated. Their accuracies are compared to identify the best-performing classifier.

## Dataset
The Breast Cancer Wisconsin dataset contains 569 samples and 30 numerical features extracted from digitized images of breast tissue. The target variable indicates whether a tumor is malignant (0) or benign (1).

## Preprocessing
Checked for missing values to ensure data integrity.

1.Applied StandardScaler to normalize all features, as the dataset contains variables with different scales.

2.Split the dataset into training and testing sets for model evaluation.

3.Scaling is essential for algorithms like SVM and k‑NN, which are sensitive to feature magnitude.

## Models Implemented
Five supervised learning algorithms were trained and evaluated:

*Logistic Regression

*Decision Tree Classifier

*Random Forest Classifier

*Support Vector Machine (SVM)

*k‑Nearest Neighbors (k‑NN)

Each model was trained on the preprocessed data and evaluated using accuracy, precision, recall, F1‑score, and confusion matrices.

## Results
Model	Accuracy
-Logistic Regression	0.9824
-Support Vector Machine	0.9824
-Random Forest	0.9561
-k‑Nearest Neighbors	0.9561
-Decision Tree	0.9035
#### Best Performance: Logistic Regression and SVM
#### Lowest Performance: Decision Tree Classifier

The results show that the dataset is nearly linearly separable, which explains the strong performance of linear and margin‑based models.

## Conclusion
This project demonstrates how different supervised learning algorithms perform on a real‑world medical dataset. Logistic Regression and SVM achieved the highest accuracy, while the Decision Tree model showed signs of overfitting. Ensemble and distance‑based methods also performed reliably.
## Technologies Used
Python

NumPy

Pandas

Scikit‑learn

Matplotlib / Seaborn

Google Colab
