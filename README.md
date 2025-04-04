# Obesity Prediction using Machine Learning

## Overview

This project aims to predict obesity levels using machine learning algorithms. It involves data preprocessing, feature engineering, model training, and evaluation to achieve accurate predictions.

## Dataset

The project utilizes the "Obesity Prediction" dataset, which contains various features such as weight, height, age, gender, and eating habits. The target variable is "Obesity_level," representing different levels of obesity.

## Code Structure

The code is structured as follows:

1. **Data Loading and Exploration:** Importing necessary libraries, loading the dataset, and performing initial data exploration using visualizations like scatter plots.
2. **Data Preprocessing:** Handling missing values, identifying categorical and numerical features, and applying transformations like StandardScaler and OneHotEncoder for data normalization.
3. **Model Selection and Training:** Utilizing pipelines for two scenarios:
   - **Without PCA:** Using a RandomForestClassifier directly on the preprocessed data.
   - **With PCA:** Applying PCA for dimensionality reduction before feeding the data to the RandomForestClassifier.
4. **Model Evaluation:** Evaluating the performance of both models using classification reports, accuracy scores, and confusion matrices.
5. **Visualization:** Visualizing PCA-reduced data and using t-SNE for further visualization of data clusters.

![image](https://github.com/user-attachments/assets/79d9dcde-edde-4fc2-9101-0768cf92d3cd)


![image](https://github.com/user-attachments/assets/8bf5567d-f343-4012-9430-53ce9847198b)


## Logic

The project follows a supervised machine learning approach for classification. It utilizes the following logic:

1. **Data Preprocessing:** Preparing the data for model training by cleaning and transforming features.
2. **Model Training:** Training the RandomForestClassifier with and without PCA to learn patterns from the data.
3. **Prediction:** Using the trained models to predict obesity levels for new data points.
4. **Evaluation:** Assessing the accuracy and performance of the models to understand their effectiveness.

## Technology and Algorithms

- **Python:** The primary programming language used for this project.
- **Pandas and NumPy:** Libraries for data manipulation and numerical operations.
- **Scikit-learn:** Library for machine learning tasks, including data preprocessing, model selection, and evaluation.
- **Matplotlib and Seaborn:** Libraries for data visualization.
- **Altair:** Another data visualization library.
- **RandomForestClassifier:** Ensemble learning algorithm used for classification.
- **PCA (Principal Component Analysis):** Dimensionality reduction technique.
- **t-SNE (t-Distributed Stochastic Neighbor Embedding):** Manifold learning technique for visualization.

## Conclusion

This project demonstrates the application of machine learning techniques for predicting obesity levels. It showcases the use of various algorithms and visualization tools to gain insights into the data and achieve accurate predictions. The results and findings can be further utilized for obesity prevention and health-related applications.
