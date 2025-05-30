# Social Media Clone

A microservices-based social media app where users can create, edit, delete, and view posts.

![Frontend](./Screenshots/frontend.png)

### Tech Stack

- **Frontend:** React + Redux Toolkit  
- **Backend APIs:** Node.js + Express (Users & Posts services)  
- **Proxy:** NGINX  
- **DevOps:** Docker, Docker Compose, Kubernetes (AWS), Travis CI  

### Features

- User authentication & post management (CRUD)
- Microservices architecture with containerization
- Deployment-ready on AWS Kubernetes
- CI/CD with Travis CI & Docker Hub

### Run Locally

```bash
docker-compose -f docker-compose-build.yaml build --parallel
docker-compose up
