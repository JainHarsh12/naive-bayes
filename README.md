# Employee Attrition Prediction using Naive Bayes

This project uses a Naive Bayes model to predict employee attrition. The model helps in identifying employees who are likely to leave the company based on key factors such as job satisfaction, number of projects, working hours, and tenure at the company.

## Project Overview

Employee attrition is a critical factor in maintaining a productive and cost-effective workforce. High attrition rates lead to increased hiring and training costs, impacting the organization. Predicting employee attrition enables companies to proactively address the factors that lead to turnover, enhancing retention strategies and improving employee satisfaction.

This project uses a Naive Bayes classifier, ideal for categorical and numerical data, to classify employees as either "likely to stay" or "likely to leave."

## Dataset

The model is based on a synthetic dataset with the following features:

- **Job_Satisfaction**: Satisfaction level (scale of 1 to 5)
- **Num_Projects**: Number of projects an employee is currently working on
- **Working_Hours_Per_Week**: Average weekly working hours
- **Years_at_Company**: Total years the employee has been with the company
- **Attrition**: Target variable, where 1 indicates "likely to leave" and 0 indicates "likely to stay"

## Installation

To run this project, clone this repository and install the required dependencies.

```bash
git clone <repository-url>
cd <repository-folder>
pip install -r requirements.txt
