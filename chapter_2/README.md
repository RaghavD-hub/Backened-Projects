# Chapter 2 - Simple Express Backend Server

## Description
This project is a simple backend server built with Express.js. It serves basic website endpoints and API endpoints for managing an in-memory data array.

## Features
- Serves a home page and a dashboard page.
- Provides API endpoints to get, add, and delete data entries.
- Uses Express middleware for JSON parsing.

## Endpoints
- `GET /` - Serves the home page with data display.
- `GET /dashboard` - Serves the dashboard page.
- `GET /api/data` - Retrieves the current data array.
- `POST /api/data` - Adds a new entry to the data array.
- `DELETE /api/data` - Deletes the last entry from the data array.

## Running the Server
Run the server using nodemon for development:

```bash
npm run dev
```

The server listens on port 8383 by default.

## Dependencies
- express
- nodemon (development)
