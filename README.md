# LMS(Online Learning Portal With Video Upload)

This repository contains the source code and implementation of a Learning Management System (LMS) developed using the MERN stack (MongoDB, Express.js, React, Node.js) along with Tailwind CSS and DaisyUI for styling, Cloudinary for managing media, and Razorpay for subscription management.


## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Subscription Management](#subscription-management)
- [Prerequisites](#prerequisites)
- [Contributing](#contributing)
- [Further-Support](#further-support)

## Overview

The Learning Management System (LMS) is a web-based application that facilitates the management and delivery of educational content and training materials. It allows administrators to create courses, manage users, and track progress. Users can access courses, view content, and complete assessments. Additionally, it offers subscription management through Razorpay, allowing users to purchase and cancel subscriptions.

## Features

- User authentication and authorization (using JWT)
- Course creation, modification, and deletion
- Content upload and management via Cloudinary
- User enrollment in courses and progress tracking
- Interactive user interface using React and Tailwind CSS
- Subscription management with Razorpay (for premium content)

## Admin Login Credentials

By default, the LMS comes with an admin account. Use the following credentials to log in:

- **Email-1:** `adminDemo@gmail.com`
- **Password-1:** `123456789@Lms`

- **Email-2:** `adminDemo2@gmail.com`
- **Password-2:** `123456789@Lms`
  
## User Login Credentials

By default, the LMS comes with an admin account. Use the following credentials to log in:

- **Email-1:** `user1@gmail.com`
- **Password-1:** `123456789@Lms`

## Installation

 Clone the project 

```bash
git@github.com:Princegupta101/Larning-Management-System.git
```

### Setup instruction  for Frontend

1. Move into the directory

```bash
cd Client
```
2. install  dependenices

```bash
npm install
```
3.  run the server

```bash
npm run dev
```

### Setup instruction  for Backend

1. Move into the directory

```bash
cd Server
```
2. install  dependenices

```bash
npm install
```
3.  run the server

```bash
npm run dev
```
4.  Set up environment variables:
   Create a `.env` file in the `server` directory and add the following:

```bash
    PORT = <Port number >
    MONGODB_URL=<Connection_LINK>
    JWT_SECRET = <YOUR_LONG_JWT_SECRET>
    JWT_EXPIRY = <JWT_EXPIRY>

    FRONTEND_URL = <YOUR_FRONTEND_WEBSITE_URL>

    CONTACT_US_EMAIL = <YOUR_CONTACT_US_EMAIL>

    CLOUDINARY_CLOUD_NAME = <YOUR_CLOUDINARY_CLOUD_NAME>
    CLOUDINARY_API_KEY = <YOUR_CLOUDINARY_API_KEY>
    CLOUDINARY_API_SECRET = <YOUR_CLOUDINARY_API_SECRET>

    SMTP_HOST = <YOUR_SMTP_HOST>
    SMTP_PORT = <YOUR_SMTP_POST>
    SMTP_USERNAME = <YOUR_SMTP_USERNAME>
    SMTP_PASSWORD = <YOUR_SMTP_PASSWORD>
    SMTP_FROM_EMAIL = <YOUR_SMTP_FROM_EMAIL>

    RAZORPAY_KEY_ID = <YOUR_RAZORPAY_KEY>
    RAZORPAY_SECRET = <YOUR_RAZORPAY_SECRET>
    RAZORPAY_PLAN_ID = <YOUR_RAZORPAY_PLAN_ID>
```

## Subscription Management

- Users can purchase subscriptions for accessing premium content or features.
- Implement a subscription management interface that allows users to:
  - View available subscription plans
  - Select and purchase a subscription plan via Razorpay
  - Cancel an existing subscription

## Low Level Diagram
![diagram](low-level-diagram.png)

## Prerequisites

Before running this project locally, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14.x or higher)
- [npm](https://www.npmjs.com/) (v6.x or higher)
- [MongoDB](https://www.mongodb.com/) (v4.x or higher)
- [Cloudinary](https://cloudinary.com/) account and API credentials
- [Razorpay](https://razorpay.com/) account and API credentials

## Contributing

We welcome contributions to Learning Management System  Feel free to create pull requests with your enhancements or bug fixes. Please ensure your contributions adhere to the coding style and conventions used in the project.



# Screen Shots Of The Project
<img width="1828" height="949" alt="image" src="https://github.com/user-attachments/assets/743cda9f-eb0a-4476-b9b5-3e7d2559b05a" />

# Admin Portal
<img width="1907" height="904" alt="image" src="https://github.com/user-attachments/assets/e4e2ed10-1a17-4387-9ed7-0782dedcd6c9" />

<img width="1919" height="913" alt="image" src="https://github.com/user-attachments/assets/ff50b7f3-c0e3-4e4d-b59c-e5cd6a212912" />

<img width="1879" height="911" alt="image" src="https://github.com/user-attachments/assets/9f8a68e3-9fc1-4813-842f-f1d6e31f0886" />

<img width="1907" height="935" alt="image" src="https://github.com/user-attachments/assets/870320eb-3a95-4ce6-879e-049ec86e7910" />

# Student Portal

<img width="1919" height="989" alt="image" src="https://github.com/user-attachments/assets/9a3d5031-2db2-4b2c-ae55-d1718b83a646" />

<img width="1919" height="993" alt="image" src="https://github.com/user-attachments/assets/d744808b-5777-410e-a0bc-e396907aa280" />

<img width="1894" height="1001" alt="image" src="https://github.com/user-attachments/assets/7352e0bd-9df2-425f-a137-c7fac5cf216e" />

<img width="1892" height="987" alt="image" src="https://github.com/user-attachments/assets/300f4825-1f83-49ce-b177-f220638657c0" />

<img width="1869" height="980" alt="image" src="https://github.com/user-attachments/assets/97824079-e489-4494-9a80-d5bf132ae0ee" />


# Project Files Structure
<img width="546" height="1005" alt="image" src="https://github.com/user-attachments/assets/8ba63d9e-7f0a-4e92-8c2f-ae5466423646" />        
<img width="535" height="995" alt="image" src="https://github.com/user-attachments/assets/d485b933-3f01-40af-9d65-48eeb3cad514" />











