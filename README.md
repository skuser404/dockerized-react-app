<div align="center">

# 🐳 Dockerized React Application

### A clean, production-style example of containerizing a React app with Docker

<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" width="70" height="70" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" width="70" height="70" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js" width="70" height="70" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="70" height="70" />
</p>

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<p>
  <img src="https://img.shields.io/badge/status-active-success.svg?style=flat-square" alt="status" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs welcome" />
  <img src="https://img.shields.io/github/last-commit/JayanthSomala/dockerized-react-app?style=flat-square" alt="last commit" />
</p>

</div>

---

## 📌 Overview

This project demonstrates how a **React.js** application can be packaged into a **Docker** container and run consistently across any environment — no more "but it works on my machine." It's a hands-on look at frontend containerization, image building, and port mapping.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :---: | :--- |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="28" /> **React.js** | Frontend UI library |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="28" /> **Docker** | Containerization & deployment |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="28" /> **Node.js** | Runtime environment |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="28" /> **Create React App** | Project scaffolding |

---

## ✨ Features

- ⚛️ React frontend application
- 🐳 Full Docker containerization
- 🔌 Port mapping (host ↔ container)
- 🚀 One-command deployment
- 🌍 Cross-platform compatibility

---

## 📂 Project Structure

```
dockerized-react-app/
├── public/             # Static assets
├── src/                # React source code
├── Dockerfile          # Container build instructions
├── .dockerignore       # Files excluded from the image
├── package.json        # Dependencies & scripts
└── README.md           # You are here
```

---

## ✅ Prerequisites

- 🐳 [Docker](https://www.docker.com/get-started) installed
- 🟢 [Node.js](https://nodejs.org/) *(optional — only for local dev)*

---

## 🚀 Getting Started

### 1️⃣ Build the Docker image

```bash
docker build -t dockerized-react-app .
```

### 2️⃣ Run the container

```bash
docker run -p 3000:3000 dockerized-react-app
```

### 3️⃣ Open the app

Navigate to 👉 **[http://localhost:3000](http://localhost:3000)**

---

## 📸 Docker Concepts Demonstrated

> Screenshots of the build process, running container, and the live app.

<div align="center">

<img width="800" alt="Docker build / app screenshot 1" src="https://github.com/user-attachments/assets/599b12d9-dc18-4566-9676-9fc9104dbdee" />

<br/><br/>

<img width="800" alt="Docker build / app screenshot 2" src="https://github.com/user-attachments/assets/ef369897-cd28-4e5e-bcf9-1975f442a25d" />

<br/><br/>

<img width="800" alt="Docker build / app screenshot 3" src="https://github.com/user-attachments/assets/f7f06d4b-a32c-4328-ab50-3774db0a0c0c" />

<br/><br/>

<img width="800" alt="Docker build / app screenshot 4" src="https://github.com/user-attachments/assets/de326148-4eb5-46a2-8675-24518a42dc51" />

</div>

---

## 🔮 Future Improvements

- [ ] 🏗️ Multi-stage Docker builds (smaller images)
- [ ] 🌐 Nginx integration for production serving
- [ ] 🧩 Docker Compose support
- [ ] ⚙️ CI/CD with GitHub Actions
- [ ] ☁️ AWS EC2 deployment

---

## 👤 Author

**Jayanth Somala**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JayanthSomala)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/)

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

⭐ **If you found this helpful, give it a star!** ⭐

</div>
