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
- [Limitations and Future Scope](#limitations-and-future-scope)

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
2. **Install Dependencies**

    ```bash
    npm install

3. **Run Development Server**

   ```bash
    npm run dev

### Backend Setup

1. **Clone the Backend Repository**

    ```bash
    git clone https://github.com/YourUsername/BookWise.git
    cd BookWise/backend

2. **Create and Activate Virtual Environment**

    ```bash
    python3 -m venv venv
    source venv/bin/activate

3. **Install Dependencies**

    ```bash
    pip install -r requirements.txt

4. **Run Flask Server**

    ```bash
    flask run

## Usage

1. **Ensure Both Servers are Running**
   - Frontend at `http://localhost:3000`
   - Backend at `http://localhost:5000`

2. **Access the Application**

   Open your web browser and navigate to `http://localhost:3000`.

3. **Explore Features**
   - **Browse** the comprehensive book catalog.
   - **Use** the recommendation feature by entering a book name to get personalized suggestions.

## Limitations and Future Scope

### Limitations

- **Scalability of the Machine Learning Model**: May not efficiently handle rapid increases in data volume.
- **Lack of Advanced Filtering**: Limited options for refining searches based on specific criteria.
- **User Interface Customization**: Minimal customization options may not meet all user preferences.
- **Internationalization**: Currently limited to English language support.

### Future Scope

- **Enhancing the Machine Learning Model**: Implementing advanced algorithms and deep learning techniques.
- **Introducing More Personalized Features**: Allowing users to customize their reading experience further.
- **Expansion to New Markets**: Adding multi-language support and regional book selections.
- **Social Features**: Integrating book clubs, reading groups, and user forums.
- **Integration with Educational Tools**: Collaborating with educational platforms for enhanced learning experiences.
- **Adaptive User Interfaces**: Developing interfaces that adapt to individual devices and accessibility needs.
