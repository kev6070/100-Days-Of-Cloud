# 100-Days-Of-Cloud
POC Designs of all my AWS Well Architected Framework Architecture Diagrams
The Use Cases will Varry From Higly Available Architecture to highly scalable and Secure Architectures

Sample NodeJs deployed using Serverless Application Model (SAM) using the SAM CLI 
1. It has a single Lambda function, an API Gateway that exposes a /hello resource and invokes the Lambda function when called with an HTTP GET request. The Lambda function assumes an IAM role that can have permissions to interact with other AWS resources, like a database for example.

2. A continuous delivery pipeline for a simple web application. Where ou will first use a version control system which is Git to store your source code. Then you create a continuous delivery pipeline that will automatically deploy your web application whenever your source code is updated.
           Set up a GitHub repository for the application code.      
           Create an AWS Elastic Beanstalk environment to deploy the application
           Configure AWS CodeBuild to build the source code from GitHub
           Use AWS CodePipeline to set up the continuous delivery pipeline with source, build, and deploy stages
