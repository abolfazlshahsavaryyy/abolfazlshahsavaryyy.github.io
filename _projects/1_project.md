---
layout: page
title: Citizen Journal
description: Twitter-like project with Django, FastAPI, ML models, Celery, RabbitMQ & GraphQL
img: assets/img/citizen-journal.png
importance: 1
category: work
related_publications: true
github: https://github.com/abolfazlshahsavaryyy/citizen_journal
---

Citizen Journal is a **Twitter-like platform** built with **Django** and **FastAPI**, integrated with advanced **machine learning models** for content moderation.  

- 📰 **Fake News Detection** – achieved **99.25% accuracy** on test data.  
- 💬 **Hate Speech Detection** – achieved **86% accuracy** on test data.  
- ⚡ **Celery + RabbitMQ** – used for asynchronous background task execution.  
- 📊 **GraphQL API** – powerful single endpoint for retrieving news in multiple formats.  
- 🐘 **PostgreSQL** – used as the relational database.  
- 📦 **Docker** – all services are fully containerized for easy deployment and scalability.  

---

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/citizen-journal.png" title="Citizen Journal Project" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Citizen Journal: Twitter-like project with Django, FastAPI, ML moderation, Celery & RabbitMQ.
</div>

---

## 📌 Core Features

### 📄 Page & News
- Create **Pages**  
- Publish **News** under each page  

### 💬 Comment
- Add and manage **comments** on news  
- Score comments using the **hate speech detection** service  

### 🗣️ Discussion & Topic
- Start and participate in **discussions**  
- Organize conversations under various **topics**  

### ❓ Question & Answer
- Ask and answer **questions** within discussions  
- Community-style interaction, like Q&A forums  

### 🔔 Notification
- Send **real-time notifications** (e.g., likes on news)  
- Handled asynchronously with **Celery & RabbitMQ**  

---

## ⚡ Technology Stack
- **Backend:** Django + FastAPI  
- **ML Models:** Fake News Detection (99.25%), Hate Speech Detection (86%)  
- **Async Tasks:** Celery + RabbitMQ  
- **Database:** PostgreSQL  
- **Containerization:** Docker for all services  
- **API:** GraphQL for flexible queries  

---

The project combines **social networking features** with **AI-driven moderation**, a robust **async communication system**, and full **Docker-based containerization** for deployment.  

---

📂 **Source Code:**  
[Citizen Journal Repository](https://github.com/abolfazlshahsavaryyy/citizen_journal)
