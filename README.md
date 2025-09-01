# Running Apache Inside a Docker Container

This project demonstrates how to deploy and manage an **Apache web server** inside a **Docker container**. Containerizing Apache allows for **isolated, portable, and easily deployable web hosting**, making it simple to run consistent environments across development, testing, and production.  

---

## 🚀 Project Overview

- **Web Server:** Apache HTTP Server  
- **Containerization:** Docker  
- **Objective:** Run Apache in an isolated container environment for portable and reproducible deployments.  
- **Benefits:**  
  - Consistent environment across machines  
  - Quick setup and teardown  
  - Easy version management  
  - Portable deployments  

---

## 🛠️ Tech Stack

- **Apache HTTP Server** – Web server software  
- **Docker** – Containerization platform  
- **Linux / Windows / macOS** – Host OS for Docker  

---

## 📂 Project Structure

apache-docker/
│
├── Dockerfile # Instructions to build Apache container image
├── html/ # Sample HTML files to serve
│ └── index.html
├── docker-compose.yml # Optional: Multi-container setup
└── README.md # Project documentation
