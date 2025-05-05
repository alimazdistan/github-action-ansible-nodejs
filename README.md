
This project is a Node.js web application that is automatically deployed to an AWS EC2 instance using GitHub Actions and Ansible.

Key Components:

Node.js app: The main backend application written in JavaScript.

GitHub Actions: Used for continuous integration and deployment (CI/CD).

Ansible: Handles the server-side deployment process on the EC2 instance.

How Deployment Works:
When you push changes to the GitHub repository, the GitHub Actions workflow is triggered.

The workflow connects to the EC2 instance using SSH and runs an Ansible playbook.

Ansible installs dependencies and starts the Node.js application on the server.

