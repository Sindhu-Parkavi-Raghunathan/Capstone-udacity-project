# Flower Boutique - Serverless

To implement this project, you need to implement a simple Flower Items application using AWS Lambda and Serverless framework. Search for all comments starting with the `Flower Items:` in the code to find the placeholders that you need to implement.

# Functionality of the application

This application will allow creating/removing/updating/fetching 'Flower Items' items. Each Flower Items item can optionally have an attachment image. Each user only has access to Flower Items items that he/she has created.

# How to run the application

## Backend

To deploy an application run the following commands:

```
cd backend
npm install
sls deploy -v
```

## Frontend

To run a client application first edit the `client/src/config.ts` file to set correct parameters. And then run the following commands:

```
cd client
npm install
npm run start
```

This should start a development server with the React application that will interact with the serverless TODO application.

