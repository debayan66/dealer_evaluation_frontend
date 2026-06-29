# Dealer Evaluation Frontend

A frontend web application developed as part of the **IBM Full Stack Software Developer Professional Certificate**. This project demonstrates the deployment and integration of a microservices-based dealer evaluation system using IBM Cloud Code Engine.

> **Course:** IBM Full Stack Software Developer Professional Certificate  
> **Module:** Application Development using Microservices and Serverless

---

## Project Overview

The Dealer Evaluation Frontend provides a user interface for viewing products, dealers, and dealer-specific pricing by interacting with backend microservices.

The application communicates with deployed backend services to:

- Display available products
- Retrieve dealers supplying a selected product
- Display pricing for a selected dealer
- Compare pricing across all dealers

---

## Features

- Product selection interface
- Dealer selection based on product
- Dealer-specific pricing
- All Dealers pricing comparison
- Frontend integrated with deployed backend microservices
- Responsive web interface
- IBM Cloud Code Engine deployment

---

## Technologies Used

- HTML5
- JavaScript
- Axios
- Python (Flask)
- Docker
- IBM Cloud Code Engine
- IBM Cloud Container Registry

---

## Project Structure

```
dealer_evaluation_frontend/
│
├── html/
│   └── index.html
├── app.py
├── Dockerfile
├── requirements.txt
├── products.json
└── eval-findings/
```

---

## Deployment

The frontend was containerized using Docker and deployed on **IBM Cloud Code Engine**.

During deployment:

- Backend service endpoints were configured
- Frontend URLs were updated to communicate with deployed microservices
- Application was successfully built and deployed using IBM Cloud Code Engine

---

## Evaluation Findings

The repository contains an **eval-findings** directory that includes screenshots captured during the IBM course final assessment.

The screenshots demonstrate:

- Successful frontend deployment
- Products loaded successfully
- Dealer selection
- Dealer pricing retrieval
- All dealers pricing comparison

These screenshots serve as evidence of successful completion of the deployment and integration tasks required in the assessment.

---

## Learning Outcomes

Through this project I gained practical experience in:

- Microservices architecture
- Frontend and backend integration
- REST API consumption
- Docker containerization
- IBM Cloud Code Engine deployment
- Cloud-native application deployment
- Troubleshooting deployment issues
- Configuring production endpoints

---

## Repository Information

This repository is a **fork** of the original IBM Skills Network project and contains my own deployment, configuration, and assessment work completed during the course.

The modifications include:

- Frontend configuration
- Backend service endpoint updates
- Cloud deployment configuration
- Successful application deployment
- Assessment evidence (screenshots)

---

## Disclaimer

This repository is intended for educational and portfolio purposes only.

The original project template and starter code were provided by **IBM Skills Network** as part of the IBM Full Stack Software Developer Professional Certificate. The deployment, configuration, integration, and assessment work contained in this repository were completed independently as part of the course requirements.

---

## Acknowledgements

- IBM Skills Network
- IBM Full Stack Software Developer Professional Certificate
- IBM Cloud Code Engine
