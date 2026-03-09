# Breast Cancer Prediction App
A Machine Learning–based web application that predicts whether a breast tumor is Benign or Malignant using diagnostic measurements of cell nuclei. The application provides an interactive interface where users can modify medical features and instantly obtain prediction results.

This project demonstrates the integration of Machine Learning, Data Visualization, and Web Application Deployment using Python and Streamlit.

# Project Overview 
Breast cancer is one of the most common cancers worldwide. Early detection plays a critical role in improving treatment outcomes.

This application uses a trained machine learning model to analyze cytological features of cell nuclei and classify tumors as benign or malignant.

Users can adjust feature values through an interactive sidebar and observe real-time predictions along with probability scores.

# Machine Learning Model 
The model is trained using the Breast Cancer Wisconsin Dataset, which contains diagnostic measurements extracted from breast mass images.

## Input Features

The model uses several cell nuclei characteristics such as:

Radius

Texture

Perimeter

Area

Smoothness

Compactness

Concavity

Concave Points

Symmetry

# Application Features
Interactive Streamlit web interface
Sidebar sliders for adjusting medical parameters
Real-time tumor classification prediction
Probability scores for benign and malignant classes
Radar chart visualization of feature measurements
Clean and intuitive UI for easy interaction

# Application Interface 
The application allows users to:

Adjust cell nuclei measurement values using the sidebar sliders
Visualize the selected feature values using a radar chart
View the prediction result (Benign or Malignant)
See probability scores for both classes

# Technologies Used 
Python

Pandas

NumPy

Scikit-learn

Streamlit

Plotly

# Run the Application
Run the below command in the terminal:
streamlit run app.py

# ⚠️ Disclaimer

This application is designed for educational and research purposes only.
It should not be used as a substitute for professional medical diagnosis.

## 👨‍💻 Author
Sanjay S 

B.Tech – Data Science and Artificial Intelligence
