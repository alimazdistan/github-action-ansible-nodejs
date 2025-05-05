
This project is a Node.js web application that is automatically deployed to an AWS EC2 instance using GitHub Actions and Ansible.

Key Components:




1-Node.js app: The main backend application written in JavaScript.

2-GitHub Actions: Used for continuous integration and deployment (CI/CD).

3-Ansible: Handles the server-side deployment process on the EC2 instance.

How Deployment Works:


1-When you push changes to the GitHub repository, the GitHub Actions workflow is triggered.

2-The workflow connects to the EC2 instance using SSH and runs an Ansible playbook.

3-Ansible installs dependencies and starts the Node.js application on the server.

