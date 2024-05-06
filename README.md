# ExamPortal

Welcome to ExamPortal, a web application developed for learning and exercising the strengths of the Spring Boot framework. This project utilizes Angular for the frontend, Spring Boot for the backend, and MySQL for the database.

## Table of Contents

1. Introduction
2. Features
3. Installation
4. Usage

## Introduction

ExamPortal is a comprehensive platform designed to facilitate online testing for students. Users can register and log in to the platform to access a variety of quizzes across different categories. As the administrator, you have the ability to manage user accounts, quiz categories, and questions.

## Features

1. User Authentication: Users can register and log in to the platform securely.
2. Quiz Categories: Create and manage different categories of quizzes such as General Knowledge, Programming, etc.
3. Quiz Creation: Easily create quizzes within each category and add relevant questions.
4. Scoring and Feedback: Instant feedback and scoring upon completion of quizzes.

## Installation

To run ExamPortal locally, follow these steps:

1. Clone the repository: git clone https://github.com/chinmaykulkarnii/ExamPortal.git
2. Navigate to the project directory: cd ExamPortal
3. Install dependencies for frontend and backend:
4. Frontend (Angular): cd frontend && npm install
5. Backend (Spring Boot): Open the project in IntelliJ and let Maven download dependencies.
   
Configure MySQL database:

1. Create a new database named exam.
2. Update application.properties in the backend with your MySQL username and password.
3. Run the backend server in IntelliJ.
4. Run the frontend server: ng serve

## Usage

Once the application is up and running, you can access it at http://localhost:4200.

1. Register/Login: Create a new account or log in with existing credentials.
2. Browse Categories: Explore different quiz categories available on the platform.
3. Take Quizzes: Select a quiz and start answering questions.
4. View Results: Receive instant feedback and scores upon completing quizzes.
