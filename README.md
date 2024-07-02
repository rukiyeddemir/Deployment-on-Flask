# Deployment on Flask / Iris Classification Project

This project demonstrates a machine learning workflow for classifying Iris species using logistic regression. It includes data preprocessing, model training, and deploying a Flask API for making predictions using the famous Iris dataset.
## Table of Contents

- [Project Description](#project-description)
- [Datasets](#datasets)
- [Installation](#installation)
- [Analysis and Insights](#analysis-and-insights)
- [Results](#results)
- [Recommendations](#recommendations)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project aims to classify Iris species using a logistic regression model. The workflow involves data loading, preprocessing, model training, and deploying a Flask API for real-time predictions.
## Datasets

The following dataset is used for the analysis:

Iris Dataset: Contains 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width, and a target variable indicating the species (setosa, versicolor, virginica).

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/rukiyeddemir/Deployment-on-Flask.git
    cd Deployment-on-Flask
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
## Analysis and Insights
The analysis includes the following steps:

1. Data Loading and Cleaning:
Load the Iris dataset.
Convert the data into a pandas DataFrame.

2. Data Splitting:
Split the data into training and testing sets.

3. Data Scaling:
Normalize the features using StandardScaler.

4. Model Training:
Train a logistic regression model.

5. Model Saving:
Save the trained model and scaler using joblib.

6. Flask API Development:
Create a Flask API to serve the model for predictions.

## Results
Key insights derived from the analysis:
The logistic regression model achieved high accuracy in classifying the Iris species.
Sepal length, sepal width, petal length, and petal width are significant features for classification.

## Recommendations
Based on the analysis, the following recommendations were made:

Use the Logistic Regression Model:
For real-time predictions due to its simplicity and effectiveness.

Further Feature Engineering:
Explore additional features or transformations to improve model performance.

Model Deployment:
Deploy the model using Flask API for accessibility and scalability.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
