# G8-capstone-project

AdoptAFriend-ReactFlaskFullstack
Welcome to AdoptAFriend-ReactFlaskFullstack! This project aims to develop a website for pet adoption using the React and Flask frameworks for the frontend and backend, respectively. The website will be deployed on AWS (Amazon Web Services) using Terraform for infrastructure as code, Docker for containerization, EKS (Elastic Kubernetes Service) for container orchestration, and Jenkins for continuous integration and continuous deployment.

Project Overview
AdoptAFriend-ReactFlaskFullstack is a full-stack web application that connects pet seekers with pet owners and animal shelters. The application allows users to browse available pets, view their details, and contact the respective pet owners or shelters for adoption. The project leverages React for the frontend to provide an interactive and responsive user interface, while Flask is used for the backend to handle database interactions and API requests.

Features
The website will include the following features:

User registration and login: Users can create accounts and log in to the website to access additional functionality.
Pet browsing: Users can browse through a list of available pets and view their details, including photos, descriptions, and adoption information.
Pet search: Users can search for specific pets based on various filters such as species, breed, age, and location.
Adoption requests: Users can submit adoption requests for pets they are interested in. Pet owners or shelters will be notified of the requests.
Messaging system: Users can communicate with pet owners or shelters through an integrated messaging system to discuss adoption details.
Admin dashboard: An admin dashboard will be provided to manage user accounts, pet listings, and adoption requests.
Technologies Used
The following technologies and frameworks are utilized in this project:

React: A JavaScript library for building user interfaces.
Flask: A Python web framework for backend development.
AWS (Amazon Web Services): A cloud computing platform for deploying and managing web applications.
Terraform: An infrastructure as code tool used for provisioning and managing AWS resources.
Docker: A containerization platform for packaging applications and their dependencies.
EKS (Elastic Kubernetes Service): A managed Kubernetes service for container orchestration.
Jenkins: An open-source automation server for continuous integration and continuous deployment.
Deployment
To deploy the AdoptAFriend-ReactFlaskFullstack project to AWS using Terraform, Docker, EKS, and Jenkins, follow these steps:

Set up an AWS account if you don't have one already.
Install Terraform and Docker on your local machine.
Configure your AWS credentials and access keys on your local machine.
Create an EKS cluster using Terraform to provide the Kubernetes environment for deploying the application.
Build Docker images for the React frontend and Flask backend.
Push the Docker images to a container registry like Amazon ECR (Elastic Container Registry).
Set up a Jenkins server and configure the necessary plugins for Docker, Kubernetes, and AWS integration.
Create a Jenkins pipeline that includes the steps for pulling the code, building the Docker images, deploying to EKS, and performing any necessary testing or quality checks.
Trigger the Jenkins pipeline for automatic builds and deployments whenever changes are pushed to the repository.
Access the deployed website by navigating to the public URL of the EKS cluster.
Development Setup
To set up the AdoptAFriend-ReactFlaskFullstack project for local development, follow these steps:

Clone the project repository to your local machine.
Set up a virtual environment and activate it.
Install the required Python dependencies using pip install -r requirements.txt.
Change to the frontend directory and install the required npm packages using npm install.
Start the React development server using npm start.
In a separate terminal, activate the virtual environment, navigate to the project root directory, and run the Flask backend using python app.py.
Open your browser and access the website at http://localhost:3000.
Contributing
Contributions to the AdoptAFriend-ReactFlaskFullstack project are welcome! If you find any issues or would like to add new features, please submit a pull request with your changes. Be sure to follow the project's coding style and guidelines.

License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for personal or commercial purposes.

Acknowledgments
We would like to thank the contributors and developers who have helped make this project possible. Your support and dedication are greatly appreciated.

If you have any questions or need further assistance, please don't hesitate to reach out. Happy coding and enjoy using AdoptAFriend-ReactFlaskFullstack!
