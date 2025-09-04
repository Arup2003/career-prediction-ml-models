# Career Prediction Using Machine Learning

## Overview
This project leverages machine learning to provide personalized career recommendations based on individual strengths, interests, and market trends. The goal is to guide students, especially those in rural areas with limited access to career counseling, toward suitable career paths by analyzing data such as academic performance, skills, and personal interests.

## Repository Structure
The repository is organized as follows:

### Data
- **CareerMapping.csv**: Initial dataset for model development.
- **CareerMapping1.csv**: Updated dataset used for the revised model.

## Machine Learning Methods
The project uses multiple machine learning algorithms to predict career paths:

- K-Nearest Neighbors (KNN)
- Naïve Bayes
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest

## Model Training and Results
| Model           | Train Accuracy | Test Accuracy |
|-----------------|----------------|---------------|
| KNN             | 65%            | 55%           |
| Naïve Bayes     | 51.1%          | 50.16%        |
| SVM             | 55%            | 52%           |
| Random Forest   | 97%            | 89%           |

The Random Forest model achieved the highest performance, demonstrating strong potential for accurate career predictions.
