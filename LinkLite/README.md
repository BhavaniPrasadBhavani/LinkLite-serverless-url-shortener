# LinkLite

A serverless URL shortening platform built using AWS Lambda, API Gateway, DynamoDB, and Lovable.

## Overview

LinkLite converts long URLs into short, shareable links using a fully serverless AWS architecture. The application is designed to be scalable, cost-efficient, and easy to maintain without managing servers.

### Example

Long URL:

https://www.amazon.in/?&adgrpid=155259813593&hvpone=&hvptwo=&hvadid=809000348074&hvpos=&hvnetw=g&hvrand=2652211031721929842&hvqmt=e&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9040222&hvtargid=kwd-64107830&hydadcr=14452_2459470

Short URL:

https://hqgmempkm4.execute-api.ap-south-1.amazonaws.com/s6DCP6

## Features

* URL shortening
* URL redirection
* Serverless architecture
* DynamoDB-based storage
* Cost-efficient cloud deployment
* Responsive frontend

## Architecture

Frontend (Lovable)
↓
API Gateway
↓
AWS Lambda
↓
Amazon DynamoDB

## Tech Stack

### Frontend

* Lovable
* TypeScript

### Backend

* AWS Lambda
* API Gateway

### Database

* Amazon DynamoDB

### Monitoring

* Amazon CloudWatch

## Why Serverless?

* No server management
* Automatic scaling
* Pay-per-use pricing
* Low operational overhead
* Suitable for high-traffic workloads

## Project Structure

frontend/
backend/
lambda/
docs/

## Future Improvements

* Click analytics
* QR code generation
* Custom aliases
* Password-protected links
* Link expiration
* User authentication
* Dashboard for analytics

## Learning Outcomes

This project helped me gain hands-on experience with:

* AWS Lambda
* API Gateway
* DynamoDB
* CloudWatch
* Serverless architecture
* REST API development
* Cloud-native application design

## Author

Bhavani Prasad
