# ChatApplication_Microservices

# Objective 

To understand the concept of Microservices and Orchestration by building a simple two tier live chat application and deploy it in minikube.

# Configuration

1) GCP instance with 2vCPU, 4 GB memory and 20 GB hard disk and Ubuntu 18.04 LTS
2) Firewall: check "Allow HTTP traffic" to access http connections and port 8080
3) Under "VPC network -> Firewall", add port 8080 to "default-allow-http"

# Task 1 Building Native Environment
1) MongoDB Installation
2) Web Server Installation

# Task 2 Containerization
1) MongoDB Containerization
2) Web Server Containerization

# Task 3 Orchestration
1) Deploy MongoDB
2) Deploy Web Server

# Execution
Use your own browser and external IP address of GCP VM plus 8080 port and access live chat microservices. Can be accessed using multiple sessions and all users should see the same messages at the same time.
