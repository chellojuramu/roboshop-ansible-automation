# RoboShop Microservices - Ansible Automation 🤖

This repository contains the Infrastructure as Code (IaC) configuration for **RoboShop**, an e-commerce microservices application. These Ansible playbooks replace legacy shell scripts to provide a fully automated, idempotent, and scalable deployment process.

## 🏗️ Architecture Overview

RoboShop is a multi-tier e-commerce platform composed of several microservices written in different languages (NodeJS, Python, Java, Go) backed by various databases (MongoDB, Redis, MySQL, RabbitMQ). 

This project automates the configuration of the following components:
* **Frontend:** NGINX Web Server
* **Databases:** MongoDB, Redis, MySQL, RabbitMQ
* **Microservices:** Catalogue, User, Cart, Shipping, Payment, Dispatch

## 🎯 Project Goals & Automation Strategy

The primary objective of this project is to transition from imperative shell scripting to declarative configuration management using Ansible.

**Key Features Implemented:**
* **Idempotency:** Playbooks are designed to be run repeatedly without causing unintended system changes or failures.
* **Modularity:** Infrastructure components are broken down into isolated, reusable roles/plays.
* **Variable Management:** Centralized configuration using Ansible variables for easier environment promotion (Dev -> QA -> Prod).
* **Error Handling:** Implementation of robust error handling and conditional logic to manage complex service dependencies.

## 🛠️ Technology Stack

* **Configuration Management:** Ansible
* **Target OS:** CentOS / Amazon Linux 2 / RHEL (Enterprise Standard)
* **Application Stack:** NodeJS, Java, Python, Golang
* **Datastores:** MySQL, MongoDB, Redis, RabbitMQ

## 🚀 Execution & Usage

*(Detailed execution instructions will be added as playbooks are developed. This will include inventory management and execution commands).*

---
*Developed as a demonstration of Enterprise Configuration Management practices.*
