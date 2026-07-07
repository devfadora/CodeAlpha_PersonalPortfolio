# CodeAlpha Personal Portfolio

## Project Overview

This project is a responsive personal portfolio website developed as part of the CodeAlpha DevOps Internship.

The website introduces me, showcases my technical skills, projects, and contact information. It has been containerized using Docker and served using the Nginx web server.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Docker
- Nginx

---

## Features

- Responsive Portfolio Website
- Modern User Interface
- Dockerized Deployment
- Nginx Web Server

---

## Docker Commands

### Build Image

```bash
docker build -t codealpha-portfolio .
```

### Run Container

```bash
docker run -d -p 8080:80 --name portfolio-container codealpha-portfolio
```

### View Running Containers

```bash
docker ps
```

---

## Project Structure

```
CodeAlpha_PersonalPortfolio
│
├── css
├── images
├── js
├── index.html
├── Dockerfile
├── nginx.conf
└── README.md
```

---

## Author

Faith Izebhor

Aspiring DevOps Engineer