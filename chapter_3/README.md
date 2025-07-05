# Chapter 3 - Full Stack Todo Application

## Description
This project is a full stack todo application using a Node.js backend, SQLite database, and JWT authentication.

## Features
- User authentication with JWT.
- CRUD operations for todo items.
- Serves static frontend files from the public directory.
- Uses bcryptjs for password hashing.

## Technologies Used
- Node.js
- Express.js
- SQLite
- JWT (jsonwebtoken)
- bcryptjs

## Running the Server
Start the server in development mode:

```bash
npm run dev
```

The server listens on port 5000 by default.

## Project Structure
- `src/` - Backend source code including routes, middleware, and server setup.
- `public/` - Static frontend files.
