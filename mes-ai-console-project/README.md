# MES PI AI Console

## AI-Powered Root Cause Analysis & Predictive Maintenance Demo

This repository contains a front-end demonstration project that illustrates how Artificial Intelligence can be applied to an MES (Manufacturing Execution System) environment for Process Innovation (PI).

The demonstration focuses on two major AI capabilities frequently used in modern smart manufacturing systems:

- Root Cause Analysis AI
- Predictive Maintenance AI

The project was created as a conceptual prototype to demonstrate the overall AI workflow rather than a production-ready MES application.

---

# Online Demonstration

You can launch the interactive demonstration directly from GitHub Pages.

https://minseong-kim.github.io/mes-pi-ai-console/

No installation is required.

Simply open the website using any modern web browser.

---

# Project Structure

```
index.html
│
├── MES_PI_AI_Console_Manual.pdf
├── README.md
│
└── mes-ai-console-project
      ├── assets
      │      ├── css
      │      └── js
      │
      ├── pages
      │      ├── MES_Console_Full_EN.html
      │      └── MES_Console_Full_KR.html
      │
      └── README.md
```

---

# Running Locally

If you would like to run the project locally instead of using GitHub Pages:

1. Download or clone this repository.
2. Keep the folder structure unchanged.
3. Open **index.html** located in the project root.
4. Select either **English** or **Korean**.
5. The selected console will launch immediately.

No web server or additional software is required.

---

# Demonstration Features

### Root Cause Analysis AI

- Simulated defect occurrence
- Production / Process / Equipment log analysis
- Root cause ranking
- Feature Importance visualization
- Natural language explanation using Claude API concept
- Event history
- AI diagnosis workflow

---

### Predictive Maintenance AI

- Real-time sensor monitoring
- Equipment health visualization
- Failure risk prediction
- Anomaly detection
- Maintenance recommendation
- Remaining useful life estimation (simulation)

---

# Technology Stack

Frontend

- HTML5
- CSS3
- JavaScript

Backend Concept

- Spring Boot REST API
- Oracle / MS SQL
- MES Integration
- PLC Interface

Artificial Intelligence

- RandomForest
- IsolationForest
- Feature Importance
- Claude API (LLM)

---

# Purpose

This project demonstrates how AI technologies can improve manufacturing operations by:

- Detecting production defects
- Identifying root causes automatically
- Predicting equipment failures
- Reducing MTTR (Mean Time To Repair)
- Preventing unexpected downtime
- Supporting data-driven Process Innovation (PI)

---

# Notes

This is a demonstration prototype.

In a production environment, the system would be connected to:

- MES
- PLC
- Equipment Controllers
- Historian Database
- Real-time Sensor Data
- Manufacturing Database

---

Author

Min-Seong Kim

AI-powered MES Process Innovation Demonstration
