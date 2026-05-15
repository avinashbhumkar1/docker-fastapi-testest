# FastAPI Dockerized Application

This project is a simple FastAPI application that has been containerized using Docker and can be run using docker-compose.

---

## Features

- GET `/` → Returns a hello message  
- GET `/users` → Returns list of users from JSON file  
- POST `/users` → Stores user data in JSON file  

---

## Docker Setup

This application is fully dockerized and can be run using Docker Compose.

### Run the Application

```bash
docker-compose up --build
