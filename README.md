# Heart Disease Prediction Project

## Overview

This project focuses on predicting heart disease risk using machine learning techniques. It includes data preprocessing, exploratory data analysis (EDA), model development, and a web application for real-time predictions.

## Project Structure

1. `heart_disease_prediction.py`: Main application file for the Streamlit web interface.
2. `requirements.txt`: List of Python dependencies for the project.
3. `ALY_6040_Group_4-Heart_Diease-EDA.ipynb`: Jupyter notebook containing exploratory data analysis.
4. `Kocherlakota_Module_1_Assignment.ipynb`: Additional Python exercises (not directly related to the heart disease prediction).

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Machine learning model development (Random Forest)
- Interactive web application for heart disease risk prediction

## Installation

1. Clone the repository:
   ```
   git clone (https://github.com/mohankocherlakota/CardioRiskAnalyser.git)
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

### Web Application

Run the Streamlit app:

```
streamlit run heart_disease_prediction.py
```

The application allows users to input various health parameters and receive a prediction for heart disease risk.

### Data Analysis

Open the `ALY_6040_Group_4-Heart_Diease-EDA.ipynb` notebook in Jupyter to view the exploratory data analysis process.

![image](https://github.com/user-attachments/assets/7459b093-dbad-4b7a-a6ea-0c13c9a44f1f)


## Data Description

The dataset includes various health-related features such as:

- Physical health days
- Mental health days
- Physical activities
- Sleep hours
- Medical history (stroke, asthma, COPD, etc.)
- BMI
- Age category
- Smoking status
- Vaccination history

## Model

The project uses a Random Forest classifier for predicting heart disease risk. The model is trained on preprocessed data and saved as `random_forest_model.pkl`.

## Files Description

1. `heart_disease_prediction.py`:
   - Contains the Streamlit web application code
   - Includes functions for loading the model, preprocessing user input, and making predictions

2. `requirements.txt`:
   - Lists all Python libraries required for the project
   - Key libraries: scikit-learn, pandas, streamlit, matplotlib, seaborn, joblib

3. `ALY_6040_Group_4-Heart_Diease-EDA.ipynb`:
   - Jupyter notebook with detailed EDA
   - Includes data cleaning, feature engineering, and visualization

4. `Kocherlakota_Module_1_Assignment.ipynb`:
   - Contains basic Python exercises (not directly related to the main project)

## Contributing

Contributions to improve the model accuracy, extend the feature set, or enhance the web application are welcome. Please follow the standard fork-and-pull request workflow.

## License

[Specify the license here, e.g., MIT, GPL, etc.]

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/43151071/1f751afa-03df-4f89-841c-6dfeab2af1e3/heart_disease_prediction.py
[2] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/43151071/8847a663-ddc2-4638-8c67-e4a0dd8405a2/requirements.txt
[3] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/43151071/b893efc7-1fd7-46e8-a774-a727b32a1c70/ALY_6040_Group_4-Heart_Diease-EDA.ipynb
[4] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/43151071/70ed7add-7dbd-45ef-91ca-04bade3c31e7/Kocherlakota_Module_1_Assignment.ipynb
