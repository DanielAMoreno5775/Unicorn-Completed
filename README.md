# Daniel's Wild Rydes Site 
[Modified version of the code found at AWS](https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/module-1/)
[Config file where all the magic is stored](./js/config.js)
Original version of the code was provided in the original repository that was forked.

Most of the code can be connected to Amazon Amplify like normal. The code in requestUnicorn.js should go in a Node.js 16.x Lambda function which needs DynamoDB permissions.
This program uses the following AWS services: API Gateway, Lambda, DynamoDB, Amplify, IAM, Cognito, and SES.