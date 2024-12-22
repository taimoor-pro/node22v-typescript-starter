## 😎 Introduction

The TypeScript Express Mongoose Starter is a comprehensive boilerplate for building robust and scalable web applications using the TypeScript programming language, Express.js framework, and Mongoose ORM for MongoDB. It provides a solid foundation and a set of best practices to kickstart your TypeScript-based Express projects with ease.

## Features

- **TypeScript:** Enjoy the benefits of static typing, enhanced code maintainability, and better developer tooling with TypeScript.
- **Express.js:** Build powerful and flexible web APIs using the popular Express.js framework.
- **Mongoose:** Utilize the elegant MongoDB object modeling library Mongoose for seamless integration with MongoDB databases.
- **User Authentication:** Includes a pre-configured user authentication system with password hashing using bcrypt and JWT-based authentication.
- **API Documentation:** Generate API documentation effortlessly with Swagger and Swagger UI integration.
- **Error Handling:** Implement centralized error handling and consistent error responses across your application.
- **Environment Configuration:** Manage your application's configuration using environment variables with the help of the dotenv library.
- **Linting and Formatting:** Maintain clean and consistent code with ESLint and Prettier pre-configured.
- **Testing with Jest:** Write unit tests and run them using the Jest testing framework.
- **Docker Integration:** Easily containerize your application using Docker for simplified deployment and scalability.
- **Nginx Reverse Proxy:** Set up Nginx as a reverse proxy to enhance performance, security, and load balancing capabilities.
- **Process Management:** Utilize PM2 or Nodemon for process management and automatic application restarts during development and production.
- **SWC Compiler:** Utilize the SWC compiler for faster TypeScript compilation and improved performance.

## ⚒ How to Install

Alternatively, you can clone the repository and install the dependencies:

```bash
$ git clone https://github.com/taimoor-pro/node22v-typescript-starter.git
$ cd node22v-typescript-starter
$ pnpm install
```

## Configuration

Before starting the project, make sure to set up your database credentials in the `.env.development.local` file. This file is used for local development and should not be committed to version control. Here's an example of how the `.env.development.local` file should be structured:

### Database Configuration

- **DB_HOST=** 127.0.0.1
- **DB_PORT=** 27017
- **DB_DATABASE=** development
- **LOG_FORMAT=** dev
- **LOG_DIR=** ../logs
