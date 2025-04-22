AWS Amplify and Amazon Bedrock Recipe Generator
Overview
This repository contains my implementation of the AWS Amplify serverless web application tutorial powered by Amazon Bedrock. The tutorial walked me through building an application that generates recipes based on user-provided ingredients using AI capabilities from the Claude 3 Sonnet foundation model.
What I Built
Through this tutorial, I learned how to:

Host a static website using AWS Amplify with continuous deployment
Configure user authentication and enable access to Amazon Bedrock foundation models
Create a serverless backend to process recipe generation requests
Integrate the frontend with the backend using Amplify Data
Build an intuitive user interface for submitting ingredients and displaying AI-generated recipes

Tech Stack

Frontend: HTML, CSS, JavaScript
Backend: AWS Amplify, AWS AppSync, AWS Lambda, Amazon Bedrock
Authentication: AWS Cognito
Deployment: AWS Amplify Console

Tutorial Structure
The tutorial was divided into six main tasks:

Host a Static Website - Configuring AWS Amplify to host the frontend with continuous deployment
Manage Users - Setting up Amplify Auth and enabling Amazon Bedrock foundation model access
Build a Serverless Backend - Creating the backend logic for handling recipe generation requests
Call the API from the Static Website - Using Amplify Data to interact with the serverless backend
Build the Frontend - Connecting the app to the backend and enhancing the user interface
Clean Up Resources - Removing all created AWS resources

Getting Started
To run this project yourself, you'll need:

An AWS account with administrator-level access
Nodejs and npm installed
AWS profile configured for local development
A GitHub account
Basic familiarity with Git

Notes
This project provided me with valuable experience in serverless application development and integrating AI capabilities into web applications. I particularly enjoyed learning how to leverage Amazon Bedrock's generative AI capabilities to create a practical application that can generate recipes based on available ingredients.