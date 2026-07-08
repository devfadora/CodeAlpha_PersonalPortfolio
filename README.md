# 🚀 CodeAlpha Personal Portfolio

A responsive personal portfolio website developed as part of the **CodeAlpha DevOps Internship**.

The project demonstrates frontend web development, Docker containerization, and preparation for Azure CI/CD deployment.

---

## 📸 Preview

(Add screenshots here after completing the project.)

---

## ✨ Features

- Responsive personal portfolio website
- Modern and clean user interface
- About Me, Skills, Projects and Contact sections
- Dockerized using Nginx
- Ready for Azure CI/CD deployment

---

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript
- Docker
- Nginx
- Git
- GitHub
- Azure Pipelines (Configuration Prepared)

---

## 📂 Project Structure

```text
CodeAlpha_PersonalPortfolio
│
├── css
├── js
├── images
├── index.html
├── Dockerfile
├── nginx.conf
├── .dockerignore
├── azure-pipelines.yml
└── README.md
```

---

## 🐳 Docker Commands

### Build the Docker image

```bash
docker build -t codealpha-portfolio .
```

### Run the container

```bash
docker run -d -p 8080:80 --name portfolio-container codealpha-portfolio
```

### View running containers

```bash
docker ps
```

### Stop the container

```bash
docker stop portfolio-container
```

### Start the container

```bash
docker start portfolio-container
```

---

## 📈 DevOps Workflow

```text
Developer
     │
     ▼
 GitHub Repository
     │
     ▼
 Azure Pipeline
     │
     ▼
 Docker Build
     │
     ▼
 Azure Container Registry
     │
     ▼
 Azure App Service
```

*The Azure deployment stage will be completed once Azure resources are available.*

---

## 👩‍💻 Author

**Faith Izebhor**

Statistics Graduate | Aspiring DevOps Engineer

GitHub: https://github.com/Faith-DevOps