# my-First-Website
link : https://5aywg33x1d.execute-api.ap-south-1.amazonaws.com/default/myFunction

Deploying on a serverless environment involves uploading your code to a cloud platform that automatically scales up and down based on demand. This eliminates the need for managing servers, allowing you to focus on developing and delivering your application. Common serverless deployment options include AWS Lambda, Azure Functions, and Google Cloud Functions.

# Amazon AWS Lambda
AWS Lambda is an event-driven, serverless Function as a Service provided by Amazon as a part of Amazon Web Services. It is designed to enable developers to run code without provisioning or managing servers. It executes code in response to events and automatically manages the computing resources required by that code

# lambda Function Code :

index.mjs

export const handler = async (event) => {
  // TODO implement
  const response = {
    statusCode: 200,
    body: JSON.stringify('Hello from myFuction || jaydip dhananjay jadhav || serverless'),
  };
  return response;
};
