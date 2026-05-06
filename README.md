# Flask Web App with Docker Compose

A containerized Flask web application that collects user data through a simple form and stores it in a database. This project demonstrates **full-stack basics + Docker Compose orchestration** in a clean and reproducible setup.

---

## Overview

This application allows users to submit their **name and email address**, which are then stored in a SQLite database for future use or analysis.

It is designed to showcase:
- Backend development with Flask  
- Database integration using SQLAlchemy  
- Frontend templating with Jinja2  
- Containerization using Docker and Docker Compose  

---

## Core Components

### Frontend
- Built using **HTML + Jinja2 templates**
- Simple and user-friendly form interface
- Collects user name and email

### Backend
- Developed with **Flask (Python)**
- Handles routing, form submission, and business logic
- Processes user input and communicates with the database

### Database
- Uses **SQLite** for lightweight data storage
- Integrated via **SQLAlchemy ORM**
- Stores user-submitted data in a structured table

---

## Key Features

- **User Input Form**  
  Users can submit their name and email through a web interface  

- **Data Persistence**  
  Submitted data is stored in a SQLite database  

- **Flash Messages**  
  Displays success messages after form submission  

- **Dockerized Setup**  
  Fully containerized for easy setup and deployment  

- **Docker Compose Orchestration**  
  Simplifies running the application with a single command  

---

## Tech Stack

- **Frontend:** HTML, Jinja2  
- **Backend:** Flask (Python)  
- **Database:** SQLite, SQLAlchemy  
- **DevOps:** Docker, Docker Compose  

---

## Getting Started

### Prerequisites
- Docker  
- Docker Compose  

### Run the Application

```bash
docker-compose up --build
