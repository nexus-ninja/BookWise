# BookWise

BookWise is an innovative online book repository and recommendation system designed to enhance the literary journey of readers by tailoring suggestions to their unique tastes and preferences. The platform leverages advanced technologies and follows CI/CD best practices to ensure a seamless and efficient user experience.

## Table of Contents

- [Features](#features)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [CI/CD Pipelines](#cicd-pipelines)
- [System Configuration](#system-configuration)
- [Installation](#installation)
- [Usage](#usage)
- [Project Demonstration](#project-demonstration)
- [Limitations and Future Scope](#limitations-and-future-scope)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Comprehensive Book Catalogue**: Browse an extensive list of books across various genres.
- **Personalized Recommendations**: Receive book suggestions tailored to your preferences using a custom machine learning model.
- **User-Friendly Interface**: Enjoy a responsive and intuitive interface optimized for all devices.
- **Backend Efficiency**: Experience fast and secure data processing with a robust backend.
- **Scalable Architecture**: Benefit from a modular design that allows for easy maintenance and scalability.

## Architecture

The architecture of BookWise is structured into three essential layers:

1. **Frontend**: Developed using **React** with **Vite**, providing a modern and efficient foundation for building a responsive user interface.
2. **Backend**: Built with **Flask** and utilizes **CORS** to manage cross-origin requests, ensuring robust and secure handling of application logic and data processing.
3. **Machine Learning Model**: A custom-built Python model that analyzes user preferences and past interactions to recommend books users are likely to enjoy.

## Technologies Used

- **Frontend Framework**: React with Vite
- **Backend Framework**: Flask with CORS
- **Machine Learning Model**: Python-based Collaborative Filtering
- **Programming Languages**: Python, JavaScript
- **Version Control**: GitHub
- **CI/CD Tools**: Jenkins, Docker, Kubernetes, Ansible
- **Containerization**: Docker and Docker Compose
- **Orchestration**: Kubernetes
- **Configuration Management and IaC**: Ansible
- **Testing**: pytest for backend, Jest for frontend

## CI/CD Pipelines

BookWise utilizes two robust CI/CD pipelines to automate the deployment process:

### Pipeline 1

- **Tools Used**: Jenkins, Docker, Docker-Compose, Ansible
- **Description**: Responsible for building, testing, and deploying the application using Docker and Docker-Compose. Ansible automates the configuration and management of the deployment environment.

### Pipeline 2

- **Tools Used**: Jenkins, Docker, Kubernetes
- **Description**: Focuses on container orchestration using Kubernetes, ensuring the application is scalable and resilient by managing containerized applications across a cluster of machines.

## System Configuration

- **Operating System**: Ubuntu LTS 20.04
- **CPU and RAM**: 8-core processor with 8GB RAM
- **Kernel Version**: 6.2.15
- **Python Version**: 3.x
- **Development Tools**:
  - **Frontend**: Vite, Node.js
  - **Backend**: Virtualenv, Flask
- **DevOps Tools**: GitHub, Jenkins, Docker, Docker Compose, Ansible, Kubernetes
- **Testing Tools**: pytest, Jest

## Installation

### Prerequisites

- **Node.js** and **npm** installed
- **Python 3.x** installed
- **Docker** and **Docker Compose** installed
- **Git** installed

### Frontend Setup

1. **Clone the Frontend Repository**

   ```bash
   git clone https://github.com/YourUsername/BookWise.git
   cd BookWise/frontend
