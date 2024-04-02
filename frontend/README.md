# Limbic AI - FrontEnd Overview

## Components

- **Frontend**: Next.js

## Docker Setup

### Starting with Docker

1. **Docker Compose**: Use `docker-compose` to orchestrate the containers for each service.
   - Next.js apps is built and run in it container.

### How to Run

- Execute `docker-compose up --build` in the terminal. This command builds the images and starts the containers defined in the `docker-compose.yml` file.

## Non-Docker Setup

### Frontend Setup (Next.js)

1. **Installation**: Ensure Node.js is installed on your system.
2. **Dependencies**: Navigate to your Next.js project directory and run `npm install`.
3. **Running the Application**: Start the development server with `npm run dev`.

## Environment Configuration

- For the frontend, setup any API endpoints or other environment-specific configurations required for the Next.js app.
