```markdown
# Docker Infra Automation 🚀

Automated Docker infrastructure deployment & management using Ansible.

## 📌 Overview
This project automates Docker server setup, container deployment, and maintenance tasks using Ansible playbooks. Useful for DevOps learning & real server automation.

## ✅ Features
- Install & configure Docker
- Deploy containers automatically
- Manage Docker services & images
- Multi-server support via Ansible inventory
- Clean & modular Roles structure

## 📂 Project Structure


├── deploy.yml                # Setup Docker infra
├── docker_management.yml     # Manage Containers & Images
├── hosts.ini                 # Target hosts
└── roles/                    # Ansible roles


## 🛠️ Requirements
- Linux Server (Ubuntu/CentOS/Debian)
- Ansible installed
- SSH access to nodes

## 🚀 How to Use

### 1️⃣ Clone Repo
```bash
git clone https://github.com/rohitboghara/docker-infra-automation.git
cd docker-infra-automation
````

### 2️⃣ Edit Inventory

Edit `hosts.ini`:

```ini
[docker_hosts]
192.168.1.10 ansible_user=root
```

### 3️⃣ Deploy Docker Infra


ansible-playbook -i hosts.ini deploy.yml


### 4️⃣ Manage Docker Services


ansible-playbook -i hosts.ini docker_management.yml


## 📘 Example Use Case

* Setup new VM with Docker
* Deploy applications via containers
* Restart/Stop/Update containers automatically

## 👨‍💻 Author

**Rohit Boghara**
GitHub: [https://github.com/rohitboghara](https://github.com/rohitboghara)

---
