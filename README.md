# Dockerized React Application

A simple React application containerized using Docker to demonstrate frontend containerization and deployment concepts.

## Project Overview

This project shows how a React application can be packaged into a Docker container and run consistently across different environments.

## Technologies Used

* React.js
* Docker
* Node.js
* Create React App

## Features

* React frontend application
* Docker containerization
* Port mapping
* Easy deployment using Docker
* Cross-platform compatibility

## Project Structure

```
dockerized-react-app/
├── public/
├── src/
├── Dockerfile
├── .dockerignore
├── package.json
└── README.md
```

## Prerequisites

* Docker installed
* Node.js (optional for local development)

## Build Docker Image

```bash
docker build -t dockerized-react-app .
```

## Run Docker Container

```bash
docker run -p 3000:3000 dockerized-react-app
```

## Access Application

Open your browser and navigate to:

```
http://localhost:3000
```

## Docker Concepts Demonstrated

<img width="1470" height="956" alt="Screenshot 2026-06-01 at 7 36 08 PM" src="https://github.com/user-attachments/assets/599b12d9-dc18-4566-9676-9fc9104dbdee" />

<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/ef369897-cd28-4e5e-bcf9-1975f442a25d" />

<img width="1470" height="956" alt="Screenshot 2026-06-01 at 6 48 20 PM" src="https://github.com/user-attachments/assets/f7f06d4b-a32c-4328-ab50-3774db0a0c0c" />

<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/de326148-4eb5-46a2-8675-24518a42dc51" />

## Future Improvements

* Multi-stage Docker builds
* Nginx integration
* Docker Compose support
* CI/CD with GitHub Actions
* AWS EC2 Deployment

## Author

Jayanth Somala

## License

MIT License
