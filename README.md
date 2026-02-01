# 🚀 Ansible Dynamic Configuration & System Intelligence

> **Enterprise-style Ansible automation showcasing dynamic configuration, system awareness, and production-grade logic.**

---

## 📌 Overview

This project demonstrates **real-world Ansible automation practices** with a strong focus on:

- Dynamic configuration management  
- System intelligence using Ansible facts  
- Environment-aware & conditional execution  
- Production-safe error handling  

The goal is to show **how Ansible adapts automation behavior intelligently** based on:

- Host & group variables  
- Hardware, OS, and network facts  
- Environment-specific configurations (dev / prod)  
- Conditional logic & validations  

> ⚙️ Designed to reflect **enterprise automation patterns** used by **DevOps & Linux System Engineers** — not tutorial-style playbooks.

---

## 🛠️ Technologies Used

- **Ansible** (latest, installed via `pip`)
- **YAML**
- **Linux** (Ubuntu / Debian-based)
- **Bash** (Custom facts)
- **Python** (Ansible runtime)

---

## 📂 Project Structure


inventory/        → Static inventory configuration  
group_vars/       → Group-level variables (web, database)  
host_vars/        → Host-specific overrides  
playbooks/        → Modular & reusable automation playbooks  
facts/            → Custom system & application facts  


## 🔑 Key Concepts Demonstrated
```text

###✅ Advanced Variable Management

Play-level variables
Group & host variables
External variable files
CLI-based variables (-e)
Variable precedence & scope resolution

###✅ System Facts & Intelligence

Automatic fact gathering
Selective fact filtering (performance optimization)
Hardware, OS, network & storage insights
Custom facts (JSON & INI formats)

###✅ Dynamic & Conditional Automation

OS-based task execution
Resource-aware decisions (CPU, RAM, Disk)
Version comparisons & Jinja2 filters
Conditional loops, checks & validations

###✅ Production-Grade Error Handling

block, rescue, always
Environment-based execution (dev vs prod)
Safe fallback logic
Deployment validation & cleanup

###▶️ Example Playbooks

Playbook	Purpose
variables-demo.yml           → Demonstrates all variable types
variable-precedence.yml	     → Shows real variable precedence
external-variables.yml	     → Environment-based deployments
facts-exploration.yml	       → Deep system intelligence
custom-facts.yml	           → Application & system custom facts
selective-facts.yml	         → Performance-optimized fact gathering
advanced-conditionals.yml	   → Real-world conditional logic
conditional-blocks.yml	     → Production-safe deployments

###🧪 How to Run
Basic execution:
ansible-playbook -i inventory/hosts playbooks/variables-demo.yml

With external variables:
ansible-playbook -i inventory/hosts playbooks/external-variables.yml \
-e "@playbooks/production-vars.yml"

###🎯 What This Project Proves to Employers

✔ Strong Ansible fundamentals
✔ Real production thinking (not lab-based)
✔ Deep Linux system awareness
✔ DevOps-style automation mindset
✔ Clean, readable & maintainable playbooks

👨‍💻 Author

Saad Khan
Cloud / DevOps Engineer
Focused on Automation, Reliability & Scalable Infrastructure
