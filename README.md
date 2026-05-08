# ARTI308-Lab10
# Iris Flower Classification Using Support Vector Machine (SVM)

## Project Description

This project uses the Support Vector Machine (SVM) algorithm to classify different iris flower species based on the well-known Iris dataset. The notebook presents a full machine learning process, covering data visualization, preprocessing, model training, performance evaluation, and hyperparameter tuning using GridSearchCV.
---

## Dataset Information

The dataset :  the Iris dataset provided by the seaborn library. 
the dataset contains 150 flower samples categorized into three iris species:

- Setosa  
- Versicolor  
- Virginica  

### Input Features

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

---

## Tools and Libraries
- Python  
- Pandas  
- Seaborn  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## Workflow

### 1. Importing Libraries

Python libraries for visualization, data handling, and machine learning are imported.
Machine Learning Process

The project is organized as a step-by-step machine learning workflow for classifying Iris flower species using the Support Vector Machine algorithm.

## Dataset Preparation

The Iris dataset is first loaded from the seaborn library. After loading it, the dataset is inspected to understand the number of records, the available features, and the target column that represents the flower species.

## Data Analysis and Visualization

Before building the model, the data is explored visually. This helps show how the different Iris species vary based on their flower measurements.

The notebook uses visualizations such as pairplots, KDE plots, and species comparison graphs to better understand the relationship between the features.

## Feature and Target Selection

The dataset is then divided into two main parts. The feature variables include the flower measurements, such as sepal length, sepal width, petal length, and petal width. The target variable represents the Iris species that the model needs to predict.

After that, the data is split into training and testing sets so the model can be trained and evaluated properly.

## Model Training

A Support Vector Machine classifier is created and trained using the training data. During this stage, the model learns patterns from the flower measurements to distinguish between the different Iris species.

## Prediction Stage

Once the model is trained, it is used to predict the species of the flowers in the testing dataset. These predictions are then compared with the actual labels to check how well the model performs.

# Model Evaluation

The performance of the SVM model is evaluated using a confusion matrix and a classification report. These evaluation tools help measure how accurately the model classified the flowers and where prediction errors occurred.

# Model Optimization

To improve the model, GridSearchCV is applied to test different combinations of SVM parameters. The main parameters tested are C, gamma, and kernel. This step helps identify the best settings for the model.

# Final Outcome

The SVM model showed strong performance in classifying the Iris flower species. After applying hyperparameter tuning, the model achieved better accuracy and reduced the number of incorrect predictions.

# Running the Notebook

To run the project, install the required libraries using:

pip install pandas seaborn matplotlib scikit-learn notebook

Then open the notebook in Jupyter Notebook and run all cells in order.
