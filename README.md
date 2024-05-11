# Heart Disease Prediction Using Machine Learning

## Introduction
This project aims to predict the likelihood of heart disease in individuals based on various health and demographic factors. It uses machine learning algorithms such as K-nearest neighbors (KNN) and Decision Tree Classifier to make predictions.

## Dataset
The dataset used in this project contains 319,795 rows and 18 columns. It includes information such as BMI, smoking habits, alcohol consumption, history of stroke, physical and mental health status, and more.

## Data Wrangling and Data Encoding
- Converted categorical values into numerical values for analysis.
- Checked for null values (no null values found).
- Encoded categorical columns using a dictionary.

## Visualization
- Plotted the percentage of heart disease cases by race.
- Visualized the distribution of heart disease cases by age category.
- Created a stacked bar chart to show heart disease cases by kidney disease status.
- Used KDE plots to compare the sleep time distribution between individuals with and without heart disease.

## Data Preprocessing
- Encoded categorical columns using one-hot encoding.
- Scaled numerical columns using StandardScaler.
- Split the data into training and testing sets.

## Machine Learning Models
### K-nearest Neighbors (KNN)
- Created a KNN classifier with 5 neighbors.
- Achieved an accuracy of 90%.

### Decision Tree Classifier
- Created a Decision Tree Classifier with a maximum depth of 5.
- Achieved an accuracy of 91%.

## Conclusion
The KNN and Decision Tree Classifier models show promise in predicting heart disease based on the given dataset. Further optimization and feature engineering could improve the accuracy of these models.

## Usage
To use this project, follow these steps:
1. Install the required libraries (pandas, numpy, matplotlib, seaborn, scikit-learn).
2. Clone the repository to your local machine.
3. Run the Jupyter notebook `HeartDiseaseML.ipynb` to train and test the machine learning models.
4. Explore the results and visualize the data using the provided code.

## Contributors
- Kirandeep Kaur https://github.com/Kiran-Gill99

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
