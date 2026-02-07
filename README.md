# AWS Lambda Mini Application

This is a simple serverless application built using **AWS Lambda** and **API Gateway**.

## 🛠️ Tech Stack
- AWS Lambda (Python)
- AWS API Gateway
- Python 3.x

## 🚀 What this app does
It returns a simple message when accessed via a browser:

Hello from my first Lambda mini application!

## 📂 Project Structure
lambda-mini-app/
│
├── docs/
│   └── Lambda-Mini-App.pdf
│
└── src/
│    ├── lambda_function.py
└── README.md




## ▶️ How to deploy (high level)
1. Create a Lambda function in AWS
2. Copy `lambda_function.py` into Lambda
3. Attach API Gateway as a trigger
4. Use the generated URL to access the app