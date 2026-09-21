# 🏦 User Management Application

## 📌 Overview

This project covers the **setup, configuration, deployment, and application support** activities performed for a **User Management Application used in a banking environment**.

The application is deployed and managed in a **Windows Server environment**.

---

## 🖥️ Environment

| Component             | Technology                  |
| --------------------- | --------------------------- |
| 💻 Operating System   | Windows Server              |
| 🌐 Web Server         | Apache HTTP Server          |
| 🚀 Application Server | Apache Tomcat               |
| 🗄️ Database          | MySQL                       |
| ⚡ Cache               | Redis                       |
| 📦 Deployment         | WAR Application             |
| 🏦 Application        | User Management Application |

---

## 🔐 Application Login

The User Management Application provides a secure **Login Page** for authorized users.

### 🔑 Login Page

```text
┌─────────────────────────────────────────┐
│                                         │
│        🏦 USER MANAGEMENT SYSTEM        │
│                                         │
│        👤 Username                      │
│        ┌───────────────────────────┐    │
│        │                           │    │
│        └───────────────────────────┘    │
│                                         │
│        🔒 Password                      │
│        ┌───────────────────────────┐    │
│        │                           │    │
│        └───────────────────────────┘    │
│                                         │
│              [ 🔐 LOGIN ]               │
│                                         │
└─────────────────────────────────────────┘
```

The login request is processed by the backend application deployed on **Apache Tomcat**.

---

## ⚙️ Backend Application

The backend of the User Management Application is deployed as a **WAR application** on Apache Tomcat.

### 🔄 Backend Flow

```text
👤 User
   │
   │ Login Request
   ▼
🌐 Apache HTTP Server
   │
   ▼
🚀 Apache Tomcat
   │
   ▼
🏦 User Management Application
   │
   ├──────────────► 🗄️ MySQL
   │                  Database
   │
   └──────────────► ⚡ Redis
                      Cache / Session
```

### 🛠️ Backend Activities

* 📦 WAR deployment on Apache Tomcat
* ⚙️ Application configuration
* 🔗 Database connectivity configuration
* ⚡ Redis connectivity configuration
* 🔐 Authentication-related application configuration
* 📊 Application log monitoring
* 🔄 Application restart and deployment
* 🔍 Backend troubleshooting
* 🗄️ Database connectivity verification
* ⚡ Redis connectivity verification

---

## 🔧 Key Activities

* 🖥️ Performed fresh setup of the User Management Application on **Windows Server**
* 🌐 Configured **Apache HTTP Server**
* 🚀 Configured and managed **Apache Tomcat**
* 📦 Deployed application **WAR files**
* 🗄️ Configured **MySQL database connectivity**
* ⚡ Configured and managed **Redis**
* ⚙️ Configured application and server-specific settings
* 🔄 Performed application deployment and restart activities
* 📋 Managed application configuration across environments
* 📊 Monitored application and Tomcat logs
* 🔍 Troubleshot application startup and deployment issues
* 💾 Performed application/build backup activities
* 🔗 Verified application, database, and Redis connectivity
* 🛠️ Supported application maintenance and deployment activities

---

## 🏗️ Application Architecture

```text
                         👤 USER
                           │
                           ▼
                  🔐 LOGIN PAGE
                           │
                           ▼
                🌐 APACHE HTTP SERVER
                           │
                           ▼
                   🚀 APACHE TOMCAT
                           │
                           ▼
              🏦 USER MANAGEMENT APP
                     /           \
                    /             \
                   ▼               ▼
             🗄️ MYSQL           ⚡ REDIS
             DATABASE            CACHE
```

---

## 🖥️ Deployment Environment

```text
🖥️ WINDOWS SERVER
│
├── 🌐 Apache HTTP Server
│
├── 🚀 Apache Tomcat
│     └── 🏦 User Management Application
│
├── 🗄️ MySQL
│
└── ⚡ Redis
```

---

## 🛠️ Technologies & Skills

`Windows Server` `Apache` `Tomcat` `MySQL` `Redis` `SQL` `WAR Deployment` `Application Support` `Deployment` `Troubleshooting` `Log Monitoring` `Server Administration`

---

## 🎯 Objective

To maintain a **stable, secure, and reliable Windows Server environment** for deploying, configuring, monitoring, and supporting the User Management Application.

---

## 🔐 Security

This repository does **not** contain:

* ❌ Production passwords
* ❌ Database credentials
* ❌ Redis credentials
* ❌ Encryption keys
* ❌ Customer information
* ❌ Confidential banking data
* ❌ Production configuration
* ❌ Sensitive server information

---

## 👨‍💻 Maintainer

**Amit Pachpute**

💻 Application Support | 🗄️ SQL | 🪟 Windows Server | 🚀 Deployment | 🔧 Troubleshooting | 📊 Data Engineering

---

⭐ **Documenting real-world application deployment, backend configuration, and application support experience.**
