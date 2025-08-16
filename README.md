# 🌐 ProManage  
_A Microservices-based Smart Resource Management Platform_

![Java](https://img.shields.io/badge/Java-17-blue) 
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen)
![Docker](https://img.shields.io/badge/Docker-Enabled-blue)
![React](https://img.shields.io/badge/Frontend-React%20%2B%20Tailwind-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🚀 Overview
**ProManage** is a smart resource management platform built using a **Microservices Architecture**.  
It provides scalable modules for **user management, finance, task handling, and notifications** – all connected through a centralized **API Gateway** and **Service Registry**.

---

## 🛠️ Microservices

### 🔐 **User Service**
- Handles **user registration, authentication, and authorization**
- Uses **MongoDB**, **Redis**, and **JWT** for security & caching  

### 💰 **Finance Service**
- Manages **finance transactions & vouchers**
- Powered by **MySQL**

### 📋 **Task Service**
- Provides **task & project management**
- Built on **MongoDB**, integrates with **Kafka** for event-driven processing  

### 🔔 **Notification Service**
- Real-time notifications system  
- Uses **Kafka** + **Redis** for streaming & caching  

### 🌍 **API Gateway**
- Single entry point for all services  
- Enables **routing, load balancing, and security**

### 🧭 **Service Registry**
- **Eureka** based service discovery  
- Keeps track of running microservices  

---

## 🎨 Frontend
- Built with **React + TailwindCSS**  
- Responsive, modern, and user-friendly UI  

---

## ⚡ Infrastructure
All infra components are containerized using **Docker Compose**:  
- 🐳 **Redis** → Caching & session store  
- 🐳 **MySQL** → Relational database for finance  
- 🐳 **Kafka + Zookeeper** → Event streaming backbone  

---

## 📂 Project Structure
ProManage/
│── service-registry/
│── api-gateway/
│── user-service/
│── finance-service/
│── task-service/
│── notification-service/
│── frontend/
│── docker-compose.yml

🏗️ Tech Stack

## Backend: Java 17, Spring Boot, Spring Cloud, Kafka, Redis, Eureka
Frontend: React, Tailwind CSS
Databases: MongoDB, MySQL
Infra: Docker, Docker Compose