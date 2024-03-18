# Submission-Evaluator-using-AWS
Assignment Evaluator is an evaluation platform built using AWS Services. This system leverages the use of Serverless AWS Services to score the assignment submitted. It features scalability, flexibility of cloud computing without the need to manually work on evaluating the submissions and grade them accordingly.

It features the use of services like: AWS S3, AWS Textract, AWS Lambda, AWS CloudWatch logs.
1. S3 bucket that stores all the submitted assignments, make it publicly accessible and grant basic read/write permissions to other AWS accounts.
2. Using IAM Role we can manage the level of user's access to AWS Servcies. We attach this IAM Role to the lambda function and define permissions.
3. Lambda function is used to get the objects from S3 bucket where it retrieves two file - Reference and submitted
4. cloudwatch to verify the result

![image](https://github.com/divyagottipati-2908/Submission-Evaluator-using-AWS/assets/110450411/3e9a9c32-03fc-4dfc-87c0-0039c6d19f19)
![image](https://github.com/divyagottipati-2908/Submission-Evaluator-using-AWS/assets/110450411/1f1efdea-2cb5-44eb-9a65-95d36cbe18bf)
![image](https://github.com/divyagottipati-2908/Submission-Evaluator-using-AWS/assets/110450411/4005c2ea-5ed6-487f-966f-4311375fff3c)
![image](https://github.com/divyagottipati-2908/Submission-Evaluator-using-AWS/assets/110450411/b61fdc94-d502-4b71-a5f9-ab3d75c97b28)

If any concerns can connect to my LinkedIn: https://www.linkedin.com/in/gottipati-divya-23918721a/
