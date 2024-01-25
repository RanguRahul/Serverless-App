# Serverless-Application Architecture

The application architecture uses AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console.   


![Serverless_Architecture](https://github.com/RanguRahul/Serverless-App/assets/120587828/f4fb2aee-68a5-4ea1-bf3c-7394f2352c79)


1) Static Web Hosting

   AWS Amplify provides hosts static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser.

2) User Management

  Amazon Cognito provides user management and authentication functions to secure the backend API.


3) Serverless Backend

  Amazon DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.


4) RESTful API

  JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway.

  What Do we need  ?
  _________________________________________________________________

  A way to store/update/pullcode

  A way to handle permission for code

  A place to host website & make updates.

  A way for Users to registry and log in.
  
  A way to do ride sharing functionality.

  Some where to store/return ride results

  A way to invole ride sharing functionality.

