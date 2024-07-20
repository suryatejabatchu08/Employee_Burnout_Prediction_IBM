# Employee Burnout Prediction

## Project Overview

Employee burnout is a state of physical, emotional, and mental exhaustion caused by excessive and prolonged stress. This project aims to predict employee burnout using machine learning techniques. By analyzing various factors such as workload, mental fatigue, and work-life balance, we aim to develop a model that can help organizations identify employees at risk of burnout and take proactive measures.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/blurredmachine/are-your-employees-burning-out?select=train.csv) and includes the following features:

- **Employee ID**: The unique ID allocated for each employee (example: fffe390032003000)
- **Date of Joining**: The date-time when the employee joined the organization (example: 2008-12-30)
- **Gender**: The gender of the employee (Male/Female)
- **Company Type**: The type of company where the employee is working (Service/Product)
- **WFH Setup Available**: Indicates if the work from home facility is available for the employee (Yes/No)
- **Designation**: The designation of the employee within the organization (range: 0.0 to 5.0, where higher is a higher designation)
- **Resource Allocation**: The amount of resource allocated to the employee, i.e., the number of working hours (range: 1.0 to 10.0, where higher means more resources)
- **Mental Fatigue Score**: The level of mental fatigue the employee is facing (range: 0.0 to 10.0, where 0.0 means no fatigue and 10.0 means complete fatigue)
- **Burn Rate**: The target value predicting the burnout rate of the employee (range: 0.0 to 1.0, where higher means more burnout)

## Project Structure

The repository is organized as follows:

- `employee_burnout_analysis-AI.xlsx`: The dataset file.
- `Employee_Burnout_Prediction.ipynb`: The main notebook for data analysis and model training.
- `requirements.txt`: Listed necessary libraries used in the training.
- `README.md`: Project overview and instructions.

## Installation

To get started with the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/suryatejabatchu08/Employee_Burnout_Prediction_IBM.git
cd Employee_Burnout_Prediction_IBM
pip install -r requirements.txt
```

## Usage

1. **Data Preprocessing and Exploration**: Open the Jupyter notebook `Employee_Burnout_Prediction.ipynb` to explore and preprocess the data.

2. **Model Training**: Follow the steps in the notebook to train the machine learning model using the preprocessed data.

3. **Model Evaluation**: Evaluate the performance of the trained model as demonstrated in the notebook.

## Results

The results of the project, including model performance metrics and visualizations, can be found in the notebook.

## Contributing

We welcome contributions to the project. If you have any suggestions, bug reports, or improvements, please create an issue or submit a pull request.


## Acknowledgements

- The dataset was provided in the file `employee_burnout_analysis-AI.xlsx`.
---
