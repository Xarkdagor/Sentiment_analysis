# Real-Time Twitter Sentiment Analysis Platform (Full-Stack)

This repository hosts a **full-stack web application** designed to perform **real-time sentiment analysis** on Twitter data. The platform enables users to analyze public opinion trends dynamically using a responsive frontend and a robust backend.

---

##  Overview

This application processes tweets from a pre-defined dataset and classifies their sentiments into:
- Positive
- Negative
- Neutral
- Irrelevant

It provides real-time insights through a dashboard, making it a powerful tool for understanding social media sentiment trends.

---

##  System Design & Technology Stack

###  Architectural Components

- **Data Pipeline:** Ingests tweets from `twitter_validation.csv` for real-time sentiment analysis.
- **Web Interface:** Displays insights via interactive charts and graphs using a modern UI.

###  Key Technologies

#### Frontend
- **Angular:** For building the dynamic, component-based UI.
- **Bootstrap:** For mobile responsiveness and sleek design.

#### Backend
- **Express.js:** RESTful API server handling logic and requests.
- **MongoDB:** Stores analysis results, user data, and historical sentiment trends.

---

##  Development Approach

###  User Interface Layer

Developed using Angular + Bootstrap:

- **Homepage:** Briefs users on application goals and usage.
- **Analytics Dashboard:** Displays sentiment trends through:
  - Pie Charts
  - Bar Graphs
  - Live updates

###  Server Layer

Developed with Express.js and integrated with MongoDB:

- **API Services:**
  - Accept tweet data
  - Process sentiment classification (ML model can be integrated)
  - Send results back to frontend
- **Database Operations:**
  - Store predictions
  - Provide analytics endpoints (e.g., total sentiments, time-based trends)
  - Support CRUD operations


