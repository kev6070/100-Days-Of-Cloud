# 100-Days-Of-Cloud
POC Designs of all my AWS Well Architected Framework Architecture Diagrams
The Use Cases will Varry From Higly Available Architecture to highly scalable and Secure Architectures

Sample NodeJs deployed using Serverless Application Model (SAM) using the SAM CLI 
1. It has a single Lambda function, an API Gateway that exposes a /hello resource and invokes the Lambda function when called with an HTTP GET request. The Lambda function assumes an IAM role that can have permissions to interact with other AWS resources, like a database for example.
