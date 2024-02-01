# End to End ML Model deployment using AWS Sagemaker

## Introduction

This project showcases the end-to-end deployment of a Random Forest multi-class classifier model on AWS SageMaker to predict the price range of mobile phones. The code and dataset are available in the repository. 

## Project Overview
The project aimed to train and deploy a Random-Forest multi-class classifier model on AWS Sagemaker to predict the price range of mobile phones. I followed Krish Naik’s tutorial [“End-to-end Machine Learning Project Implementation Using AWS Sagemaker”](https://www.youtube.com/watch?v=Le-A72NjaWs&list=PLZoTAELRMXVPS-dOaVbAux22vzqdgoGhG&index=17). Duration of project: 3 hours.

## Tools
`VS Code, Anaconda, AWS Sagemaker, AWS S3, AWS IAM`

## Project Structure

- `sagemaker-custom-script.ipynb`: Jupyter Notebook containing the project implementation.
- `script.py`: Python script used for model training.
- `requirements.txt`: File listing the required packages for the project.
- `mob_price_classification_train.csv`: Dataset used for training the model.
- `train-V-1.csv` and `test-V-1.csv`: Train and test data files.

## Installation

To install the necessary packages, run the following command:

```
pip install -r requirements.txt
```

## Conclusion

This project demonstrates the deployment of a machine learning model on AWS SageMaker, showcasing the importance of deploying models for real-world applications. For a detailed walkthrough, refer to the notebook provided.

**Medium article:** [End-to-end ML model deployment using AWS Sagemaker: Project review](https://medium.com/@pratishsmashankar/end-to-end-ml-model-deployment-using-aws-sagemaker-project-review-90df945d90df)
