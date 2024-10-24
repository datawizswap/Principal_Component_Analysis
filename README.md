# University Clustering using PCA and Flask

## Project Overview
This project performs dimensionality reduction using Principal Component Analysis (PCA) on university data and visualizes the results using a Flask-based web application. The data contains information on various U.S. universities, including SAT scores, acceptance rates, and graduation rates, among other metrics. The goal is to reduce the feature set and visualize the results for clustering and prediction purposes.

## Features
#### Data Collection: University data with 7 key features (SAT, acceptance rates, expenses, etc.).
#### PCA Implementation: Reduces the dimensionality of the dataset to 3 principal components.
#### Flask Web Application: Upload new university data, process it with the saved PCA model, and display the results.

## Technologies Used
#### Python (Pandas, NumPy, Scikit-learn, Matplotlib)
#### Flask (for the web interface)
#### Joblib (for saving and loading the PCA model)
#### Excel (for data input/output)

## Project Structure
#### app.py: Contains the Flask code for uploading and processing new university data.
#### University_Clustering.ipynb: Jupyter notebook for data preprocessing, PCA implementation, and visualization.
#### Data_prep_DimRed: Saved pipeline containing the imputation, standardization, and PCA transformation.
#### templates: HTML files for rendering the web interface.

## Installation
#### Clone this repository.
#### Install the necessary dependencies using:
#### Run the Flask app:
#### python app.py
#### Usage
#### Open the Flask app in your browser.
#### Upload an Excel file containing university details.
#### The app will display PCA results with the first three components.

## Data
The dataset contains information about 25 universities with the following features:

#### SAT: Average SAT score.
#### Top10: % of students in the top 10 of their previous academic class.
#### Accept: Acceptance rate.
#### SFRatio: Student-to-faculty ratio.
#### Expenses: Cost of attendance (in USD).
#### GradRate: Graduation rate.

## Future Enhancements
#### Add clustering algorithms (e.g., K-Means) to further analyze the PCA components.
#### Improve the UI to display interactive charts.
