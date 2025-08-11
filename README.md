# 🛠️ Vagrant Provisioning — vProfile Application

This repository contains the **vProfile multi-tier web application** set up locally using **Vagrant** for provisioning. 
we have set up this project manually then we have also Autiomated it using vagrgant Automation 
The goal of this project is to simulate an on-premise style deployment for development and testing purposes.

---

## 📌 Project Overview

The vProfile application is a sample enterprise web application with the following components:

- **Frontend** — Tomcat application server  
- **Database** — MySQL  
- **Caching** — Memcached  
- **Messaging** — RabbitMQ  
- **Reverse Proxy / Load Balancer** — Nginx  

Using **Vagrant**, we automate the provisioning of these services into virtual machines.

---

## ⚙️ Tech Stack

- **Vagrant** — VM provisioning  
- **VirtualBox** — Virtualization provider  
- **Shell Provisioning** — For installing and configuring services  
- **MySQL** — Database  
- **Tomcat** — Application server  
- **RabbitMQ** — Messaging queue  
- **Memcached** — Caching  
- **Nginx** — Load balancer

---


---

## 🚀 How to Run

### 1️⃣ Install Prerequisites
- [Vagrant](https://www.vagrantup.com/downloads)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

### 2️⃣ Clone the Repository

git clone https://github.com/Neerajgupta12345677/Dev-Ops-Projects.git   
- cd Dev-Ops-Projects/vagrant
- vagrant up

