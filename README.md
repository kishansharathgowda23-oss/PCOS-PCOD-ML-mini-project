PCOS + PCOD Prediction using Machine Learning (Combined Model)

This project predicts PCOS (Polycystic Ovary Syndrome) and PCOD (Polycystic Ovarian Disease) using machine learning models trained on a combined dataset.

 Project Overview

This system uses a dataset (combined_500.csv) to:

Predict whether a person has PCOS/PCOD
Train multiple machine learning models
Evaluate and compare model performance
Visualize results using graphs
  Features
  CSV Upload (Google Colab)
  Multiple ML Models:
Random Forest 
Logistic Regression 
K-Nearest Neighbors (KNN) 
  Evaluation Metrics:
Accuracy
Precision
Recall
F1 Score
 Visualizations:
Confusion Matrix (per model)
ROC Curve (combined)
Model Comparison Bar Chart
 Technologies Used
Python 
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Google Colab
  Dataset
File: combined_500.csv
Target Column: PCOS_PCOD
Description: Combined dataset including features related to PCOS and PCOD conditions
  Working Process
Upload dataset in Google Colab
Split data into:
Training set (80%)
Testing set (20%)
Train models:
Random Forest
Logistic Regression
KNN
Evaluate performance using metrics
Generate visual outputs:
Confusion Matrix
ROC Curve
Bar Graph Comparison
  Output Visualizations
  Confusion Matrix for each model
  ROC Curve showing model performance
  Bar Graph comparing Accuracy, Precision, Recall, F1 Score
   Results
Model	Accuracy	Precision	Recall	F1 Score
Random Forest	✔️	✔️	✔️	✔️
Logistic	✔️	✔️	✔️	✔️
KNN	✔️	✔️	✔️	✔️

(Values depend on dataset used)

 How to Run
Open project in Google Colab
Upload combined_500.csv
Run all cells

Install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn
 Project Structure
Combined-PCOS-PCOD-ML/
│── combined_model.ipynb
│── combined_500.csv
│── README.md
  Future Improvements
 Add Deep Learning (ANN / CNN models)
 Deploy as Web App (Flask / Streamlit)
 Feature Importance Visualization
 Integration with IoT devices (ESP32-based health monitoring)
 Contribution

Contributions are welcome! Feel free to fork and improve this project 

 License

This project is open-source and free to use.

⭐ GitHub

Host your project on GitHub and showcase your ML skills!
