# Cloud-based Restaurant Ordering & Inventory System

## Project Overview
This project is a serverless cloud-based restaurant ordering system built on AWS.
Customers can place orders through a web menu.
Orders are stored in a cloud database.
Restaurant owners can view orders and sales records through an admin dashboard.

## Architecture
Customer Web App (S3)  
→ API Gateway  
→ AWS Lambda  
→ DynamoDB  
→ Admin Dashboard (S3)

## Tech Stack
- AWS S3 (Static Website Hosting)
- AWS API Gateway
- AWS Lambda (Python)
- AWS DynamoDB
- AWS IAM
- GitHub

## Features
- Online menu ordering
- Store orders in database
- Admin order management dashboard
- Fully serverless architecture
- AWS Free Tier deployment

## Project Structure
/frontend-customer   → Customer ordering web page  
/frontend-admin      → Admin dashboard web page  
/backend-lambda      → AWS Lambda functions  
/infrastructure      → Architecture and deployment notes  
/docs                → Screenshots and documentation  

## Deployment Status
Phase 1: Project initialization completed  
Phase 2: Frontend static website in progress

## Live Demo
Customer Ordering Page:
http://restaurant-cloud-ordering-smkhong.s3-website-ap-southeast-1.amazonaws.com/

## Author
SM Khong

