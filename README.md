# Azur_docker

Stage misfat projet1 - Azure hosted Docker app

This project aims to create a Docker application managed through Portainer, enhancing efficiency by streamlining container operations. It covers Docker setup, Portainer installation, application deployment, and best practices for effective container management.

## 1) Install Ubuntu VM

Create a virtual machine running Ubuntu for an isolated development environment.

## 2) Update and configure SSH

In a Microsoft Azure project, setting up SSH access involves creating a username and password for connecting to a virtual machine (VM). This configuration enables secure remote access, essential for managing and deploying applications within the Azure environment.

## 3) Install Docker and Portainer
### 1)Install Docker on Ubuntu
```bash
sudo apt update
sudo apt install apt-transport-https ca-certificates curl software-properties-common
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
sudo apt install docker-ce
### Clone App from GitHub and Download Dependencies 

#### *(Details on cloning and downloading dependencies)*

### 5. Build App Using Docker

#### *(Steps for building the application using Docker)*

### 6. Host App on Netlify to Test Online
