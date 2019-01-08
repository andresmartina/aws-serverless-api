# Simple backend API using Cognito + AWS Lambdas (Golang) + DynamoDB + API Gateway + CloudFormation

## App Model

![](./diagram.png =250x)

## Architecture

![](./architecture.png =250x)

## Use Cases
  - Authentication using Cognito and Facebook

##### Companies Resource
  - Create Company for logged in User (POST /companies)
  - List User's Companies (GET /companies)
  - Get Company (GET /companies/{companyID})

##### Staff Resource
  - Create Company Staff (POST /companies/{companyID}/staff)

##### Services Resource
  - Create Company Services (POST /companies/{companyID}/services)


## How data is stored in DynamoDB 

## Cloud Formation

## Cognito