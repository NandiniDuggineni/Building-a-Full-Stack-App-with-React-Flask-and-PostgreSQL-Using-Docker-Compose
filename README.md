# Building-a-Full-Stack-App-with-React-Flask-and-PostgreSQL-Using-Docker-Compose
we build a full-stack web application combining React as the frontend, Flask as the backend API, and PostgreSQL as the database — all containerized using Docker Compose for seamless development and deployment.

This project is perfect if you want to learn how to:

Containerize multi-service apps
Connect frontend and backend services via Docker networking
Use a production-ready database like PostgreSQL
Simplify your local development workflow with Docker Compose

Why Docker Compose for Full-Stack Apps?
When working with modern web apps, you usually have multiple services:
Frontend (React)
Backend API (Flask)
Database (PostgreSQL)

Running these separately on your machine can get messy, with different ports, dependencies, environment setups.
Docker Compose helps you define and run multi-container Docker apps using a simple YAML file — with one command you can spin up all your services, connected and ready.

Project Overview
Service	Tech Stack	Description
Frontend	React	UI layer consuming Flask API
Backend	Flask (Python)	REST API handling logic & DB
Database	PostgreSQL	Persistent data storage


Step 1: Backend Setup (Flask API)
Simple Flask API exposing REST endpoints.
Connects to PostgreSQL using environment variables.
Dockerfile defines the Python environment and dependencies.

Fetches data from Flask backend API.
Dockerfile builds a production-ready static bundle and serves it with nginx.

Step 3: Database Setup (PostgreSQL)
Using the official PostgreSQL Docker image.
Persistent volume mapped for data storage.
Environment variables for username, password, and database name.

Step 4: Docker Compose Configuration
docker-compose.yml defines all three services and their dependencies.

Flask connects to PostgreSQL database running in the db container

Conclusion
This project demonstrates the power of Docker Compose to simplify running complex, multi-service web apps on your local machine — no installation hassles, no environment conflicts. It’s a great foundation for learning container orchestration and modern web development workflows.

If you want, I can also share the full source code — just let me know!

Follow me for more dev projects! 🚀
Got questions or suggestions? Drop a comment below!
You can read the detailed article: https://nandiniduggineni.hashnode.dev/building-a-full-stack-app-with-react-flask-and-postgresql-using-docker-compose

