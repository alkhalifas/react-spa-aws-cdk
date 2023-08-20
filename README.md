# React + Vite (S3 Static Deployment via AWS CDK)

This repo includes a boilerplate template to deploy a React application
to AWS S3 as a static application using AWS CDK.

Build the App:

    npm install
    npm run build

Bootstrap Infrastructure:

    cdk bootstrap #only run the first time

Deploy App:

    cdk deploy

Delete the full stack:

    cdk delete
