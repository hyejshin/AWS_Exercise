# AWS Exercise
The purpose of this repository is learning AWS services

## Projects
### EventTriggersForLambda
S3 bucket(create object put/delete trigger), lambda, and SNS(subscribe email or SMS) are required to use this code. 
The flow of this logic is S3 bucket -> Lambda -> SNS. 
Once user upload or delete a file, the lambda will be triggered. The python code will be processed and send a message to SNS.

### Lambda_DynamoDB
S3 bucket, Lambda, and DynamoDB are required to use this code.
static-site has html, js, and css files. This code displays list of artists and songTitle from DynamoDB. 
You can also add or update an item. This code will be deployed is S3 bucket.
create.js, delete.js, get.js, list.js, update.js are scripts for create, delete, get, and update data from DynamoDB.
createTest.json, getTest.json, and updateTest.json are example of data.
You can deploying and configuring Lambda functions for the API.
[Reference of this code: Linux Academy 'Fullstack Serverless Applications on AWS' course]

### S3EventProcessor_JAva
S3 bucket and lambda are required to us this code.
Once user upload a zipfile to a bucket, the lambda will be triggered and extract the zip file in S3 bucket.


## Licensing
You are welcome to use this code on your software.
