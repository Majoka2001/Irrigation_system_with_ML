# ML-Based Irrigation System

This project demonstrates the integration of **machine learning (ML)** into an automated irrigation system. Initially developed as a hardware-based system using Arduino, this project has been extended to include machine learning to predict irrigation needs dynamically based on environmental parameters.

## Overview
The irrigation system uses data from soil moisture, rainfall, and humidity sensors to determine whether the irrigation valve should be open or closed. By applying ML models like **Decision Trees** and **Support Vector Machines (SVMs)**, this project introduces intelligent decision-making to improve the system’s efficiency and adaptability.

## Files in the Repository
1. **`Irrigation_with_ML.ipynb`**:
   - Contains the complete Python code for:
     - Generating synthetic sensor data.
     - Training ML models (Decision Tree and SVM).
     - Evaluating model performance.
   - Includes explanations and comments to make the code easy to follow.

2. **`sensor_data.xlsx`**:
   - Synthetic dataset generated to simulate sensor readings for:
     - Soil moisture levels
     - Rainfall
     - Humidity
     - Valve state (Open/Close)

3. **`model_results.csv`**:
   - Contains the evaluation metrics of the trained ML models, including accuracy and other performance details.

## Features
- **Synthetic Dataset**:
  - Generated realistic data to simulate sensor readings for prototyping.
  - Includes 10,000 rows with features: `Soil_Moisture`, `Rainfall`, and `Humidity`.
- **Machine Learning Models**:
  - Decision Tree Classifier and Support Vector Machine (SVM) are used to predict valve states dynamically.
- **Dynamic Predictions**:
  - Transforms the irrigation system from a static rule-based system to a smart, data-driven solution.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Majoka2001/Irrigation_system_with_ML.git
   cd Irrigation_system_with_ML


Install the required dependencies:

pip install pandas numpy scikit-learn


## Run the code:

Open Irrigation_with_ML.ipynb in Jupyter Notebook or Google Colab.
Execute all cells to:
Generate the dataset.
Train the ML models.
Evaluate model performance.

## Project Highlights
Transitioned a hardware-based irrigation system to an ML-driven solution.
Used synthetic data to replicate real-world scenarios and prototype solutions.
Demonstrated the effectiveness of Decision Trees and SVMs for predictive modeling.
Future Scope
Collect real-world sensor data for improved training and evaluation.
Experiment with advanced ML models like Random Forest or Gradient Boosting.
Integrate with IoT platforms for real-time decision-making and deployment.
