# Integrating IoT for Soil Monitoring and Hybrid Machine Learning in Predicting Tomato Crop Diseases
This project develops a hybrid machine learning (ML) algorithm integrated with IoT 
technology to improve the accuracy and efficiency of soil monitoring and tomato crop disease 
prediction. An IoT device collected critical 
soil parameters—humidity, temperature, pH values, nitrogen (N), phosphorus (P), and potassium 
(K)—essential for assessing soil health and optimizing crop growth. 

## Overview
This project focuses on predicting NPK levels (Nitrogen, Phosphorus, and Potassium) in soil using various environmental factors such as temperature, humidity, and pH value. Accurate NPK prediction helps in monitoring soil quality and optimizing crop yield, making it highly beneficial for agricultural planning.

The model is developed using a Random Forest Regressor for machine learning, which was trained on historical soil data to predict NPK levels. This project can be integrated into real-world systems for continuous evaluation and enhancement.

## Dataset
The dataset used in this project contains the following key features:

Temperature
Humidity
pH Value
NPK Level (Target variable)
The dataset is structured as a CSV file, and the notebook handles data preprocessing, training, and evaluation of the machine learning model.

### Installation & Setup
To run the code locally or in Google Colab:

### Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/crop-yield-predictor.git

### Required libraries include:

pandas
scikit-learn
matplotlib
Open the notebook Crop_Yield_Predictor.ipynb in Google Colab or Jupyter Notebook and run the cells.

## Model
We use the Random Forest Regressor as the machine learning model for predicting NPK levels. The model was chosen for its robustness and ability to handle nonlinear relationships between features.

### Evaluation Metrics
Mean Squared Error (MSE): 0.07145
R² Score: 0.92855
A higher R² score indicates that the model can explain ~92.8% of the variance in the NPK levels, signifying good prediction accuracy.

### Visualizations
The project includes multiple visualizations to assess the model's performance:

## Train vs Test Performance Graph: A comparison of how the model performs on both the training and testing datasets.
Feature Importance Graph: Highlights which features (Temperature, Humidity, or pH) are most important in predicting NPK levels.
Residual Plot: Visualizes the residual errors between predicted and actual NPK values.

## How to Use the Model
To predict NPK levels, simply input new values for Temperature, Humidity, and pH. The model will output the predicted NPK level.

## Future Improvements
Deploy the model as an API for real-time soil monitoring.
Tune the hyperparameters of the Random Forest model for better performance.
Expand the dataset to include more diverse environmental conditions and regions.

### Contributing
If you'd like to contribute, feel free to fork this repository and submit a pull request. Suggestions and improvements are always welcome!
