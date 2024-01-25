# Serverless-Application Architecture

The application architecture uses AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console. Amplify Console provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.

![Serverless_Architecture](https://github.com/RanguRahul/Serverless-App/assets/120587828/f4fb2aee-68a5-4ea1-bf3c-7394f2352c79)


Static Web Hosting

AWS Amplify hosts static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser.

User Management

Amazon Cognito provides user management and authentication functions to secure the backend API.


Serverless Backend

Amazon DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.


RESTful API

JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway.

