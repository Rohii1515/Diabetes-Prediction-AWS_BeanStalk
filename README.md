# Diabetes Prediction AWS BeanStalk


![image](https://github.com/Rohii1515/Diabetes-Prediction-AWS_BeanStalk/assets/101645749/fa8a688b-ee75-433e-89e2-942e66a6e99f)

## Overview

This project utilizes Logistic Regression for predicting the likelihood of diabetes in individuals based on specific health metrics. The model is deployed on AWS BeanStalk for easy access and scalability. AWS CodePipeline is integrated for automated deployment and continuous integration. The tech stack primarily includes Python and Flask.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Deployment](#deployment)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [AWS CodePipeline Integration](#aws-codepipeline-integration)
- [Tech Stack](#tech-stack)

## Introduction

Diabetes Prediction AWS BeanStalk is a machine learning-driven project designed to predict the risk of diabetes using Logistic Regression. It offers a simple yet effective means of assessing an individual's likelihood of having diabetes based on their health metrics. The application is deployed on AWS BeanStalk, ensuring smooth accessibility. AWS CodePipeline is used for automated deployment.

## Features

- **Logistic Regression Model**: Employs a Logistic Regression algorithm for diabetes prediction.
- **AWS BeanStalk Deployment**: Provides a scalable environment for deploying and accessing the prediction system.
- **Data Processing**: Preprocesses input data to ensure accurate predictions.
- **AWS CodePipeline Integration**: Automates the deployment process using AWS CodePipeline.

## Deployment

To deploy this project locally or on AWS BeanStalk, follow these steps:

1. Clone the repository: `git clone https://github.com/Rohii1515/Diabetes-Prediction-AWS_BeanStalk.git`
2. Install necessary dependencies using `requirements.txt`.
3. Set up AWS credentials and configure BeanStalk environment.
4. Run the application using `python app.py`.

## Usage

To utilize the diabetes prediction system:

1. Input the required health metrics.
2. Click on the "Predict" button.
3. Receive the prediction output indicating the likelihood of diabetes.

## AWS CodePipeline Integration

AWS CodePipeline automates the deployment process, ensuring continuous integration and delivery. Any changes pushed to the repository will trigger the pipeline, automatically deploying the updated version of the application to AWS BeanStalk.

## Tech Stack

The tech stack used in this project includes:
- **Python**: Programming language used for building the application and implementing the machine learning model.
- **Flask**: Web framework utilized for creating the web application and exposing the prediction functionality.

## Contributing

Contributions are welcome! If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your_feature`).
3. Implement your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your_feature`).
6. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or suggestions, feel free to contact [Rohidas](mailto:rohidasjondhale1515@gmail.com).
