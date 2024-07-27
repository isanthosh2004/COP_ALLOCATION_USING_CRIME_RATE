
# Chicago Crime Analysis and Prediction

![GitHub last commit](https://img.shields.io/github/last-commit/username/repository)
![GitHub issues](https://img.shields.io/github/issues/username/repository)
![GitHub forks](https://img.shields.io/github/forks/username/repository)
![GitHub stars](https://img.shields.io/github/stars/username/repository)
![GitHub license](https://img.shields.io/github/license/username/repository)

This repository contains the analysis and prediction of crimes in Chicago using data from 2012 to 2017. The project includes data preprocessing, visualization, clustering, and classification using various machine learning models. The main goal is to predict the location of crimes and understand patterns in crime data.

## Table of Contents

- [Data Preprocessing](#data-preprocessing)
- [Data Visualization](#data-visualization)
- [Clustering](#clustering)
- [Classification](#classification)
- [Results](#results)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)

## Data Preprocessing

1. **Loading Data:** Loading the dataset from CSV files.
2. **Handling Missing Values:** Dropping rows with missing values.
3. **Dropping Irrelevant Columns:** Removing columns that are not useful for the analysis.
4. **Date Conversion:** Converting date columns to datetime format for better analysis.
5. **Feature Engineering:** Creating new features from existing ones to improve model performance.

## Data Visualization

1. **Crime Distribution:** Visualizing the distribution of different types of crimes.
2. **Time Series Analysis:** Analyzing trends in crimes over time.
3. **Geospatial Analysis:** Mapping crimes to visualize crime hotspots in Chicago.

## Clustering

- **K-Means Clustering:** Grouping similar crimes together to identify patterns.
- **DBSCAN Clustering:** Density-based clustering to find high-density areas of crimes.

## Classification

Several machine learning models were used to classify and predict crimes:

1. **Decision Tree Classifier:**
   - **Accuracy:** 22%
   - **Precision:** Varies by class, with an average precision of 19%.
   - **Recall:** Varies by class, with an average recall of 30%.
   - **F1-Score:** Varies by class, with an average F1-score of 20%.

2. **Multilayer Perceptron (MLP) Classifier:**
   - **Accuracy:** 24%
   - **Precision:** Varies by class, with an average precision of 22%.
   - **Recall:** Varies by class, with an average recall of 32%.
   - **F1-Score:** Varies by class, with an average F1-score of 19%.

## Results

The models were evaluated using various metrics:

- **Decision Tree Classifier:**
  - **Precision:** Average precision of 19%.
  - **Recall:** Average recall of 30%.
  - **F1-Score:** Average F1-score of 20%.
  - **Accuracy:** 22%.

- **Multilayer Perceptron (MLP) Classifier:**
  - **Precision:** Average precision of 22%.
  - **Recall:** Average recall of 32%.
  - **F1-Score:** Average F1-score of 19%.
  - **Accuracy:** 24%.

## How to Run

1. **Clone the Repository:** Clone this repository to your local machine.
2. **Install Dependencies:** Install the necessary dependencies using the requirements file.
3. **Run the Notebook:** Open and run the Jupyter notebooks provided to preprocess the data, visualize it, and train the models.
4. **Evaluate the Models:** Use the test data to evaluate the performance of the models.

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

## Acknowledgments

This project was inspired by the need to understand and predict crime patterns in urban areas to help improve public safety. Special thanks to the Chicago Police Department for providing the crime data used in this analysis.

