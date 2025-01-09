# Breast Cancer Predictor

A Streamlit web application that leverages a machine learning model to assist medical professionals in predicting whether a breast mass is benign or malignant based on cell nuclei measurements. This project includes features for interactive data input, visual analysis through radar charts, and real-time predictions.

## Features
- **Interactive Sliders**: Adjust cell nuclei measurements in the sidebar to explore predictions dynamically.
- **Radar Chart Visualization**: Visualize the scaled measurements for mean, standard error, and worst-case values in an intuitive radar chart.
- **Machine Learning Predictions**: Classifies breast masses as benign or malignant using a pre-trained machine learning model and displays prediction probabilities.
- **Professional Disclaimer**: Clearly states that the tool is for assistance only and not a substitute for professional medical diagnosis.

## Tech Stack
- **Streamlit**: For building the interactive web interface.
- **Plotly**: For creating radar charts to visualize data.
- **Pandas**: For data cleaning and preprocessing.
- **Scikit-learn**: For model loading and scaling input values.
- **Python**: Core programming language used.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/breast-cancer-predictor.git
   cd breast-cancer-predictor
   
2. Install dependencies and run:
 ```bash
 pip install -r requirements.tx

 streamlit run app/main.py
        OR
 python -m streamlit run app/main.py
