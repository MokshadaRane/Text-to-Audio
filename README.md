Cloud Computing Miniproject
# Title: Text-to-Speech Converter

This project uses AWS services to convert text files (such as blog posts, articles, newsletters) into speech. This is particularly useful for creating audio versions of written content, making it accessible to a wider audience, including those who prefer listening over reading.

# Project Architecture

![Userclient](https://github.com/user-attachments/assets/ce946cca-2e8f-44c7-a277-851a0e20e084)

# Steps to build the project

Step 1: Create two S3 Buckets (Source bucket: sourcebucket-pdf-to-audio, Destination bucket: destinationbucket-pdf-to-audio)
Step 2: Create IAM policy
Step 3: Create an IAM Role and attach pdf-to-audio-lambda-policy and AWSLambdaBasicExecutionRole Policies
Step 4: Create and Configure the Lambda Function (Lambda Function Name: TextToSpeechFunction)
Step 5: Configure S3 Event Notification
Step 6: Testing
