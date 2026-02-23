# 02-Maven-WebApp

A Java-based Web Application built using **Maven** and automated through a **CI/CD pipeline** with **Jenkins** and **Tomcat**.

## 🚀 Project Overview
This project demonstrates an automated deployment workflow:
* **Build Tool:** Maven
* **CI Server:** Jenkins
* **Web Server:** Apache Tomcat 9
* **Environment:** AWS EC2 (Ubuntu/Amazon Linux)

## 🛠️ Tech Stack
* **Java:** Backend logic
* **JSP/Servlets:** Web interface
* **Maven:** Dependency management and packaging (WAR)
* **Jenkins:** Automation of build and deployment
* **Tomcat:** Hosting the web application

## 📋 Features
* Automated build on code commit.
* Automatic deployment to Tomcat via Jenkins "Deploy to container" plugin.
* Configured for remote management using `manager-script` roles.

## 🔧 Installation & Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/02-Maven-WebApp.git](https://github.com/YOUR_USERNAME/02-Maven-WebApp.git)
