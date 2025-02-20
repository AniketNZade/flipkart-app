
A simple e-commerce application built with Flask and Docker, ready to deploy to Amazon ECS.

## Local Development

1. Install Docker and Docker Compose
2. Clone this repository
3. Run the application:
   ```bash
   docker-compose up --build
   ```
4. Access the API at http://localhost:5000

## API Endpoints

- GET `/`: Welcome message
- GET `/products`: List all products
- POST `/products`: Add a new product

## Deployment to AWS ECS

1. Create an ECR repository
2. Push the Docker image to ECR
3. Create an ECS cluster
4. Create a task definition
5. Create a service

## Environment Variables

- `DATABASE_URL`: PostgreSQL connection string
- `SECRET_KEY`: Flask secret key for session management
