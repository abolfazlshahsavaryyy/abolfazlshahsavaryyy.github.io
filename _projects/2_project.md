---
layout: page
title: Microservice Shopping Web API
description: Microservice architecture with ASP.NET Core, Carter, MediatR, SQL Server & Postgres
img: assets/img/microservice.png
importance: 2
category: work
giscus_comments: true
---

The **Microservice Shopping Web API** is a distributed system built with **ASP.NET Core**, following clean architecture principles and modern service communication patterns.  

It leverages **Carter** for lightweight routing, **MediatR** for CQRS and request/response handling, and is fully containerized with **Docker & Docker Compose** for seamless deployment.  

---

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/microservice.png" title="Microservice Web API Project" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Microservice Shopping Web API: ASP.NET Core, Carter, MediatR, SQL Server, Postgres + Marten, all containerized with Docker.
</div>

---

## 📌 Core Features

### 🛒 Shopping API
- RESTful **Shopping Service** for managing products, carts, and orders.  
- Built using **ASP.NET Core** + **Carter**.  

### ⚡ CQRS with MediatR
- Clear separation of **commands** and **queries**.  
- Extensible request/response pipeline with MediatR behaviors.  

### 🗄️ Database Layer
- **SQL Server** in Docker for structured relational data.  
- **PostgreSQL + Marten** for document-style persistence (NoSQL-like).  

### 🐳 Dockerized Microservices
- Fully configured with **Docker Compose**.  
- Runs SQL Server, Postgres, and API services seamlessly in isolated containers.  

---

## ⚡ Technology Stack
- **Backend Framework:** ASP.NET Core + Carter  
- **Architecture:** CQRS with MediatR  
- **Databases:**  
  - SQL Server (Relational)  
  - PostgreSQL + Marten (Document Store, NoSQL style)  
- **Containerization:** Docker & Docker Compose  

---

This project demonstrates a **scalable microservice architecture**, blending **relational and NoSQL-style persistence** within a clean, containerized development environment.  
