# MERN App (MongoDB, Express, React, Node.js) with Docker Compose

##  Overview

This project is a full-stack MERN (MongoDB, Express, React, Node.js) application containerized using Docker Compose. It demonstrates a **3-tier architecture** where:

   **Frontend**: React application
   **Backend**: Express.js + Mongoose API server
   **Database**: MongoDB

The entire stack is orchestrated with Docker Compose for easy local development and portability.
# Useful commands
| Task                     | Command                        |
| ------------------------ | -------------------------------|
| Start all services       | docker compose up -d           |
| Stop all services        | docker compose down            |
| Rebuild all images       | docker compose up -d --build   |
| View container logs      | docker compose logs -f         |
| Access a container shell | docker compose exec backend sh |

