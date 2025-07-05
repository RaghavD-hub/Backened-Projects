# Chapter 4 - Dockerized Full Stack Todo Application

## Description
This project is a Dockerized full stack todo application using a Node.js backend, PostgreSQL database, Prisma ORM, and JWT authentication.

## Features
- User authentication with JWT.
- CRUD operations for todo items.
- Database integration with PostgreSQL using Prisma ORM.
- Docker support for containerized deployment.
- Uses bcryptjs for password hashing.

## Technologies Used
- Node.js
- Express.js
- PostgreSQL
- Prisma ORM
- JWT (jsonwebtoken)
- bcryptjs
- Docker

## Running the Server
Start the server in development mode:

```bash
npm run dev
```

The server listens on port 5000 by default.

## Docker
Use the provided `Dockerfile` and `Docker-compose.yaml` to build and run the application in Docker containers.

## Project Structure
- `src/` - Backend source code including routes, middleware, and server setup.
- `prisma/` - Prisma schema and migrations.
- `public/` - Static frontend files.
- `commands/` - Screenshots and other command-related files.
