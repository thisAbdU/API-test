# API Test Repository

Welcome to the API Test Repository! This repository contains a collection of APIs for performing CRUD (Create, Read, Update, Delete) operations on a to-do task list.

## Overview

The APIs included in this repository are designed to interact with a to-do task list application. They provide endpoints for managing tasks such as creating new tasks, retrieving existing tasks, updating task details, and deleting tasks.

## Folder Structure

- **API**: This folder contains the code for the APIs responsible for CRUD operations on the to-do task list.
  
## API Endpoints

- **POST /api/tasks**: Creates a new task in the task list.
- **GET /api/tasks**: Retrieves all tasks from the task list.
- **GET /api/tasks/{taskId}**: Retrieves a specific task by its ID.
- **PUT /api/tasks/{taskId}**: Updates an existing task with new details.
- **DELETE /api/tasks/{taskId}**: Deletes a task from the task list.

## Usage

To use the APIs in this repository, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `API` folder.
3. Install any necessary dependencies by running `npm install`.
4. Start the server by running `npm start`.
5. Use an API testing tool like Postman or cURL to send requests to the specified endpoints.

## Dependencies

- **Express**: Java web application framework for creating APIs.
- **Body-parser**: Middleware for parsing incoming request bodies.
- **Mongoose**: Spring JPA object modeling tool for Spring app to interact with the database.

## Contributions

Contributions to this repository are welcome! If you have any suggestions for improvements or would like to add new features, feel free to fork this repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as needed.
