🏥 Healthcare Premium Prediction

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-App-orange.svg)

A simple and effective ML app to predict health insurance premium costs based on a person’s age, BMI, smoking status, and other factors.
Built using machine learning and Streamlit for ease of use.

## Project Structure

- **main.py**: Main script for model and predictions

- **prediction_helper.py**: Functions used in prediction

- **artifacts**: Saved models/results

- **requirements.txt**: Python dependencies

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/healthcare-premium-prediction
    cd healthcare-premium-prediction
    Install dependencies
    ```
2. **Install dependencies**:
   ```commandline
   pip install -r requirements.txt
   ```
3. **(Optional) Run Streamlit app**:
    ```commandline
    streamlit run app.py
   ```
4. **Run model script**:
   ```bash
    python main.py
    ```
   
## Tech Stack

- **Python 3.8+**
- **scikit-learn, pandas, numpy**
- **Streamlit** (for web app)

## Data & Sample

- **Dataset**: Public datasets like “Medical Cost Personal Datasets” from Kaggle
- **Sample Prediction**:
Input: age=30, BMI=28, smoker=yes → Premium: ₹42,000