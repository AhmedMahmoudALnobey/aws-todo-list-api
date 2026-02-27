# Serverless To-Do List REST API

**مشروع تخرج AWS Solutions Architect - Associate**

## Solution Architecture Diagram
<image-card alt="Architecture Diagram" src="ddb-crud.png" ></image-card>

## الخدمات المستخدمة
- Amazon API Gateway (HTTP API)
- AWS Lambda
- Amazon DynamoDB
- Amazon S3 (للـ Frontend النهائي)

## How it works
اليوزر بيفتح صفحة ويب بسيطة → يعمل Create/Read/Update/Delete → API Gateway ينادي Lambda → Lambda يخزن في DynamoDB.

## Live URL (هيتحط بعد ما نخلص)
