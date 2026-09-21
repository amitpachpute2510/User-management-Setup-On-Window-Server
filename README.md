# 🏦 User Management Application — Windows Server

## 📌 Overview

This project covers the **fresh setup, configuration, deployment, and application support** of a **User Management Application used in a banking environment**.

The application is deployed and managed on a **Windows Server environment** using Apache HTTP Server, Apache Tomcat, MySQL, and Redis.

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

# 🖥️ Application Screens

## 🔐 Frontend — User Management Login

<table border="3">
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/amitpachpute2510/User-management-Setup-On-Window-Server/refs/heads/main/FrontEnd%20Page.png"
           alt="User Management Frontend Login Page"
           width="900">
    </td>
  </tr>
</table>

---

## ⚙️ Backend — Application Server

<table border="3">
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/amitpachpute2510/User-management-Setup-On-Window-Server/refs/heads/main/BackEnd%20Page.png"
           alt="User Management Backend Page"
           width="900">
    </td>
  </tr>
</table>

---

# 🏗️ Application Architecture

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

# 🖥️ Deployment Environment

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

# 🔧 Key Activities

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
* 💾 Performed application and build backup activities
* 🔗 Verified application, database, and Redis connectivity
* 🛠️ Supported application maintenance and deployment activities

---

# 🔄 Application Flow

```text
👤 User
   │
   ▼
🔐 Frontend Login
   │
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
   │                  │
   │                  └── Database
   │
   └──────────────► ⚡ Redis
                      │
                      └── Cache / Session
```

---

# 🛠️ Technologies & Skills

### 💻 Server & Application

`Windows Server` `Apache HTTP Server` `Apache Tomcat` `WAR Deployment`

### 🗄️ Database & Cache

`MySQL` `SQL` `Redis`

### 🔧 Application Support

`Application Deployment` `Configuration Management` `Log Monitoring` `Troubleshooting` `Server Administration` `Backup & Restore`

---

# 🎯 Objective

To maintain a **stable, reliable, and properly configured Windows Server environment** for deploying, monitoring, and supporting the User Management Application.

---

# 🔐 Security

This repository does **not** contain sensitive production information.

The following information is excluded:

* ❌ Production passwords
* ❌ Database credentials
* ❌ Redis credentials
* ❌ Encryption keys
* ❌ Customer information
* ❌ Confidential banking data
* ❌ Production secrets
* ❌ Private certificates
* ❌ Authentication tokens

---

# 📁 Repository

**GitHub Repository:**
`User-management-Setup-On-Window-Server`

The repository contains application setup documentation, deployment information, architecture references, and relevant application screenshots.

---

# 👨‍💻 Maintainer

### Amit Pachpute

💻 Application Support
🗄️ SQL & MySQL
🪟 Windows Server
🚀 Application Deployment
🔧 Troubleshooting
📊 Data Engineering

---

⭐ **Documenting real-world application deployment, server configuration, and application support experience.**
