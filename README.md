# 🌐 REST API CI/CD Pipeline using Postman & GitHub

## 🚀 Technologies & Tools Used

🧪 Postman – for API testing and automation

💻 Visual Studio Code – code editor

⚙️ CI/CD – Continuous Integration and Continuous Deployment

🔧 GitHub – version control and GitHub Actions for pipeline

🖥️ Terminal – command-line tool

## ✅ Prerequisites

Make sure you have the following installed:

✅ Postman Desktop App

✅ Postman CLI (Command Line Interface) – Install Guide

## 🔍 API Project Scenario

This project simulates a simple user management system. The available REST API operations include:

➕ Create a user

➕ Create a user by ID and name

📄 Retrieve all users

🔍 Retrieve a user by ID

✏️ Update a user by ID

❌ Delete a user by ID

## 📑 API Documentation

 [Click to View](https://documenter.getpostman.com/view/16548351/2sA3BoaXSA#116cbeb2-02e8-4637-9d46-3caedd1bd5f0)

## How to set up Postman CLI Configuration with GitHub

### 🛠️ Setup Postman CLI Configuration with GitHub

🔹 Step 1: Setup in Postman

1. Open Postman

2. Create a Workspace

3. Create a Collection

### 🔹 Step 2: Collection Run Setup
- Click the collection
  
  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/5ae3cde3-e3f8-492b-8ad8-58fb800a7fd9)

- Click the Run button

  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/6ee1dab5-47e6-4fb8-87f5-d314543fa1fc)
  
- Select Automate Run via CLI

  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/2197efd6-e3ad-4022-ab71-02a7bb470b7c)
  
### 🔹 Step 3: Install Postman CLI & Run Tests

- Download Postman CLI
- Open Terminal and run:
- open the terminal
  
    postman login --with-api-key {{your_api_key}}
  
- hit the commmand
- after postman cli install then generate a api key
- then login with this command in cmd

              postman login --with-api-key {{xyz}}
  
- after login successfully then hit this command in cmd

             postman collection run {{collection_key}}
  
  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/b05fae3a-3b00-48bb-b75c-4c59ed3de8b1)

### 🔹 Step 4: CI/CD Integration in Postman

- Click Run on CI/CD

![image](https://github.com/Mamun104/restapi_ci_and_cd_pipeline_using_postman_and_github/assets/78067017/25582ac2-10a9-485b-a420-d158096a388f)

- then Generate Postman CLI Configuration

![image](https://github.com/Mamun104/restapi_ci_and_cd_pipeline_using_postman_and_github/assets/78067017/ee098a91-d6cc-4d72-ba65-bc3c50a64682)

- after that copy postman cli command

![image](https://github.com/Mamun104/restapi_ci_and_cd_pipeline_using_postman_and_github/assets/78067017/f9191c0b-3f68-4fb5-8dd4-3ff308744f99)

### 🔹 Step 5: GitHub Action Setup

- create a new repository via github
- Go to the Actions tab

![image](https://github.com/Mamun104/restapi_ci_and_cd_pipeline_using_postman_and_github/assets/78067017/eb449f88-7fab-47b7-80ce-27e0526ef8da)

- then select the simple workflow

![image](https://github.com/Mamun104/restapi_ci_and_cd_pipeline_using_postman_and_github/assets/78067017/51da6529-8e50-4b1f-ae37-c21fc2fb7846)

- then copy and paste the postman cli command in the github action
- after that can commit this file
- then click the github action and run this file

## newman-reporter-html

![image](https://github.com/Mamun104/api-cicd-pipeline-using-postman-and-github/assets/78067017/ddec0095-81c0-4573-96d3-9f4be0fa4c3e)

## newman-allure-reporter

![image](https://github.com/Mamun104/api-cicd-pipeline-using-postman-and-github/assets/78067017/8c6b0dc8-b4d5-4738-a302-0afc116ff888)
![image](https://github.com/Mamun104/api-cicd-pipeline-using-postman-and-github/assets/78067017/f6ef0a8d-ff7a-4dde-a5d3-e2d7a80eca3d)


