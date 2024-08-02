# Recommendation Engine

As dataset Retailrocket recommender system dataset from kaggle was used. Link to dataset: https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset

### Structure of the Code

* **Loading and Inspecting the Data**
* **Data Cleaning and Merging**
* **Data Preparation: Feature Extraction and Transformation**
* **Processing items_properties Files**
* **Splitting Data into Training and Test Sets**
* **Model Training: Applying SVD Model**
* **Evaluating Model Performance (Calculating RMSE)**
  * Evaluating the Average Error Ratio
  * Visualization of Results
* **Finding Similar Users Using KNN Model**
  * Cross-Validation and Hyperparameter Optimization 
* **Recommendation Functions***
  * Collaborative Filtering: Making Recommendations Using SVD and KNN Models
  * Content-Based Filtering Using Item Properties
  * Finding Similar Items Using Annoy

### Requirements
%pip install pandas
%pip install scikit-learn
%pip install scipy
%pip install numpy
%pip install matplotlib
%pip install annoy
