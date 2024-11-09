# TODO-app-using-docker
This project is a simple TODO app containerized using Docker. It demonstrates how to use Docker to build, run, and manage a microservices-based application for a basic task management system. The TODO app allows users to add, update, delete, and manage a list of tasks, providing an example of CRUD (Create, Read, Update, Delete) functionality.

Features
Add Tasks: Easily add new tasks with a title and description.
Update Tasks: Edit existing tasks to update status, priority, or details.
Delete Tasks: Remove completed or irrelevant tasks from the list.
View Tasks: Display all tasks with options to filter or search.
Containerized Deployment: Package the application in Docker for easy, portable deployment.
Environment Configuration: Utilize Docker Compose to manage environment variables and dependencies.
Tech Stack
Frontend: HTML, CSS, JavaScript(react).
Backend: Node.js/Express.
Database: MongoDB/PostgreSQL.
Containerization: Docker and Docker Compose.

Getting Started:
1.Clone the Repository:
  git clone <repository-url>
  cd todo-app-using-docker
2.Build and Run with Docker:
  docker-compose up --build
3.Access the Application:
  Open your browser and go to http://localhost:<port>.
  
Prerequisites:
Docker and Docker Compose installed on your system.
Node.js for local development.

Project Structure:
frontend/: Contains frontend files.
backend/: Contains backend files.
Dockerfile: Defines Docker image for the application.
docker-compose.yml: Orchestrates services and sets environment configurations.
