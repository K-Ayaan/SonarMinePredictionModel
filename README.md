# Machine Learning Project: Predictive Classification System

## Overview
This project implements a machine learning pipeline using **Logistic Regression** to build a predictive classification system. The workflow follows industry-standard practices for data science projects, from data collection through model evaluation.

## Project Workflow

The project is organized into the following stages:

1. **Dependencies** - Import required libraries and tools
2. **Data Collection** - Gather raw data (Mine → Rock classification)
3. **Data Processing** - Clean, transform, and prepare data for modeling
4. **Training and Test Data** - Split data into training and testing sets
5. **Model Training** - Train a Logistic Regression model
6. **Model Evaluation** - Assess model performance and accuracy
7. **Predictive System** - Create a system for making predictions on new data

## Machine Learning Approach

- **Algorithm**: Logistic Regression
- **Task Type**: Binary Classification (Mine vs. Rock)
- **Key Steps**:
  - Data preprocessing and feature engineering
  - Train-test split for validation
  - Model training on training dataset
  - Performance evaluation using test dataset
  - Deployment of predictive system

## 📁 Project Structure

```
swiggy-sales-analysis/
│
├── README.md
├── main.ipynb
├── data.csv
├── requirements.txt

```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/K-Ayaan/SonarMinePredictionModel.git
   cd main.ipynb
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

4. **Open the notebook**
   - Navigate to `main.ipynb` and run all cells

## Results

Accuracy on training data :  0.8342245989304813 = 83.4%
Accuracy on test data :  0.7619047619047619 = 76.2%

```
