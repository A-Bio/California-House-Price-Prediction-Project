# California-House-Price-Prediction
This project focuses on predicting housing prices in California using machine learning techniques.By leveraging data preprocessing, feature engineering, and regression models, this project highlights the core steps in building an end-to-end data science pipeline.

**Table of Contents**
- Project Overview
- Dataset Sources
- Installation
- Usage
- Analysis Breakdown
- Modeling and Results
- Technologies Used
- Contributions
- License

# Project Overview
The goal of this project is to create a robust machine learning model capable of predicting housing prices in California. By leveraging data preprocessing, feature engineering, and advanced regression models, this project highlights the core steps in building an end-to-end data science pipeline.

# Dataset Sources
The dataset used for this project is publicly available and contains features about California housing. Below are the columns available in the dataset:

- longitude: Longitude of the house location
- latitude: Latitude of the house location
- housing_median_age: Age of the house (in years)
- total_rooms: Total number of rooms in the house
- total_bedrooms: Total number of bedrooms in the house
- population: Population of the area around the house
- households: Number of households in the area
- median_income: Median income in the area
- ocean_proximity: Proximity of the house to the ocean (categorical feature)
- median_house_value: Median house value (Target variable)

**Installation**
- Clone the repository to your local machine
- Create and activate a virtual environment
- Install the necessary dependencies

**Usage**
- Open the Notebook
- Open the California_House_Price_Prediction.ipynb file.
- Follow the steps in the notebook to load and preprocess the data, train the model, and evaluate its performance.

**Technologies Used**
- **Python**: The main programming language used for data analysis and machine learning.
- **Pandas & NumPy**: Libraries for data manipulation and numerical computations.
- **Scikit-learn**: For building and evaluating machine learning models.
- **Matplotlib & Seaborn**: For data visualization.
- **Google Colab**: Interactive computing environment for executing and documenting the analysis.

**Contributing**
Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bugs. For major updates, please open an issue to discuss your ideas.

**License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Data Preprocessing: Preprocess the data by handling missing values, scaling features, and encoding categorical variables.

Model Building: Develop three models for predicting housing prices: VIG, Lasso, and Ridge. These models will leverage the processed data to make accurate predictions.


Creating new features
Removing outliers
Transforming skewed features
Checking for multicoliniearity
2) Training machine learning algorithms:
Here, I have trained various machine learning algorithms like

Linear Regression
Ridge Regression
Support Vector Regression
Gradient Boosting Regression
Stacking of various models
