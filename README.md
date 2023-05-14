# CloudProject - Installation Guide

This guide provides step-by-step instructions on how to install and run the CloudProject on your local machine using Docker.

## Prerequisites

Before you begin, make sure you have the following software installed on your machine:

- Docker
- Docker Compose

If you haven't installed Docker and Docker Compose yet, please visit the official Docker website and download the appropriate versions for your operating system.

## Installation Steps

Follow these steps to install and run the CloudProject:

1. Clone the CloudProject repository by running the following command in your terminal or command prompt:
   ```
   git clone https://github.com/AtefMMO/CloudProject.git
   ```

2. Navigate to the project directory:
   ```
   cd CloudProject
   ```

3. Build the Docker images for the backend and frontend applications using Docker Compose:
   ```
   docker-compose build
   ```

4. Start the Docker containers:
   ```
   docker-compose up
   ```

   This command will download any required Docker images and create the necessary containers for the project.

5. Once the containers are up and running, open a web browser and visit [http://localhost:5000/persons](http://localhost:5000/persons) to access the frontend application.

   Note: Ensure that port 5000 is not being used by any other application on your machine.

Congratulations! You have successfully installed and started the CloudProject on your local machine using Docker. You can now explore and interact with the application.

If you encounter any issues or have questions, please refer to the project's documentation or seek assistance from the project maintainers.

Enjoy using the CloudProject!
