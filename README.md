# **Web Application Development with AWS**

## **Overview**
This project demonstrates how to build a secure, scalable, and cost-effective web application using AWS services. The application includes user authentication, real-time data storage, and dynamic user profile display, leveraging AWS Amplify, Cognito, Lambda, DynamoDB, and GraphQL API for an end-to-end solution.

---

## **Features**
- **User Authentication**: Secure sign-up, sign-in, and password recovery using Amazon Cognito.
- **Serverless Backend**: AWS Lambda for custom logic triggered upon user actions.
- **Real-Time Data Storage**: User profiles stored in DynamoDB and accessed via a GraphQL API.
- **Frontend Framework**: React-based single-page application built with Vite for an optimized development experience.
- **Global Deployment**: Hosted on AWS Amplify for high availability and continuous deployment.

---

## **Technologies Used**
### **Frontend**:
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)

### **Backend**:
- [AWS Lambda](https://aws.amazon.com/lambda/) (serverless compute)
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) (scalable NoSQL database)
- [AWS AppSync](https://aws.amazon.com/appsync/) with GraphQL

### **Authentication**:
- [Amazon Cognito](https://aws.amazon.com/cognito/)

### **Hosting**:
- [AWS Amplify Hosting](https://aws.amazon.com/amplify/)

### **Development Tools**:
- [Node.js](https://nodejs.org/) and npm
- [Git](https://git-scm.com/) and GitHub

---

## **Architecture**
1. **Frontend**: React app hosted on AWS Amplify, allowing users to interact with the application.
2. **Authentication**: Amazon Cognito manages user accounts, verification, and session management.
3. **Serverless Functionality**: AWS Lambda processes user data and triggers events post-authentication.
4. **Database**: DynamoDB securely stores user profile information with high scalability.
5. **API Layer**: AWS AppSync provides real-time communication between the frontend and backend via GraphQL.

---
