# Docker HTML App Project

## 📌 Project Overview

This project demonstrates the deployment of a simple HTML web application using Docker and Nginx. The application is containerized and executed inside a Docker container, ensuring portability, scalability, and consistency across different environments.

## 🚀 Technologies Used

- HTML5
- Docker
- Nginx
- Docker Desktop

## 📂 Project Structure

```text
Docker-html-app-prj
│
├── Dockerfile
├── index.html
├── README.md
│
├── 01_Docker_Installation.png
├── 02_Docker_Acceptance.png
├── 03_Index_HTML_Code.png
├── 04_Dockerfile_Code.png
├── 05_Docker_Build_Process.png
├── 06_Docker_Container_Execution.png
└── 07_Application_Output.png
```

## ⚙️ Implementation Steps

1. Installed Docker Desktop on Windows.
2. Created a simple HTML web application.
3. Created a Dockerfile using the Nginx base image.
4. Built a Docker image from the project files.
5. Executed the Docker container with port mapping.
6. Accessed the application through a web browser.

## 🐳 Docker Commands Used

### Build Docker Image

```bash
docker build -t my-html-app .
```

### Run Docker Container

```bash
docker run -d -p 8080:80 my-html-app
```

## 📸 Documentation

The repository contains screenshots demonstrating:

- Docker Installation
- Docker Acceptance and Setup
- HTML Source Code
- Dockerfile Configuration
- Docker Image Build Process
- Docker Container Execution
- Application Output

## 🎯 Application Output

The application successfully displays:

```text
Welcome to My HTML App

This is running inside a Docker container!
```

## 🎓 Academic Project

This project was developed as part of the B.Sc Information Technology Final Year curriculum to demonstrate Docker containerization and deployment of a web application.

## 👩‍💻 Author

**Bidhu P**  
B.Sc Information Technology (2022–2025)  
Sri Krishna Adithya College of Arts and Science

## ✅ Conclusion

This project successfully demonstrates the containerization and deployment of a static HTML web application using Docker and Nginx. It provides a practical understanding of Docker images, containers, and web application hosting.
