# Learning Ansible for my Network and System Administration class 

> *Ansible is a agentless, simple powerful tool used for automating configuration, orchestration, and application deployment across multiple servers just by using SSH and Python.*

## 🎯 Objectives

- Learn to manage multiple servers with Ansible
- Understand playbooks, inventories, and modules
- Explore agentless architecture of Ansible
- Manage files, services on multiple servers
- Install third-party software on servers

---

## 🛠️ Environment Setup Overview

### 🧰 Server Provisioning
- Use **Multipass** to create and manage lightweight Ubuntu VMs

### 🔐 SSH Key Configuration
- Generate and distribute an **Ansible SSH key** for secure server access

### ⚙️ Ansible Control Setup
- Designate one node as the **control machine**
- Other nodes act as **Ansible-managed hosts (agents)**

---

## 📁 Key Components

- **Inventory**: Defines the list of hosts or groups
- **Playbooks**: YAML files describing automation tasks
- **Modules**: Reusable units for executing actions (e.g., `copy`, `apt`, `service`)
- **Roles**: Pre-structured directory format for organizing playbooks
- **Facts**: System information gathered from managed nodes

---

## 📘 Learning Focus

- Running ad-hoc commands across all servers
- Writing playbooks for repeatable automation
- Managing roles and variables efficiently
- Ensuring idempotency and error handling


