## Hi, I'm Stiben 👋

### 🔐 Infrastructure & Security · Full-Stack Developer

I'm the person who takes a business application from idea to production **and keeps it running safely**.
I design the servers it lives on, harden them, deploy and monitor the services, automate the processes
around them, and build the application itself: database, API and interface.

My work sits where **development, infrastructure and security** meet. I care less about "it works on my
machine" and more about: *Is it isolated? Who can reach it? Is there a backup? Can we roll back in minutes?*

---

### 🧠 About me

- 🏢 I build and operate the **internal platforms of a company** in the accounting, finance, tax, legal and BPO space.
- 🖥️ I administer **Linux servers end to end**: virtualization, containers, reverse proxies, TLS, DNS and SSH access.
- 🛡️ I run **security audits** on internal systems and apply hardening and least-privilege principles to everything I deploy.
- ⚙️ I automate business processes with **n8n**, connecting internal APIs, databases and external services.
- 📊 I started in **data science** (Python, Pandas, NumPy) and grew into full-stack development and infrastructure.

---

### 🛠️ What I've built and run

**🏗️ Self-hosted platform on isolated containers**
Designed a deployment platform with **Coolify running inside an Incus (LXC) container** on a VPS.
Each application, database and cache is a separate resource with its own lifecycle and backups,
databases are reachable only from the private network, and only ports 80/443 are exposed.

**🔄 Zero-data-loss production migrations**
Migrated live services between servers, including a Django/React platform, an **n8n instance with
100+ workflows and 60+ encrypted credentials**, and a Supabase stack. The process included
PostgreSQL dump/restore with row-count verification, encryption-key validation by hash comparison
(without exposing secrets), low-TTL DNS cutovers and container snapshots for instant rollback.

**🧾 Internal business applications**
Full-stack platforms (**Django + React + PostgreSQL + Redis**) for administrative, accounting,
treasury and document-processing workflows, deployed with Docker Compose behind Nginx and Traefik.

**🛡️ Security audits**
Review of internal systems and infrastructure: exposed services, access control,
secrets handling and server configuration.

---

### 💻 Languages

[![Languages](https://skillicons.dev/icons?i=python,nodejs,js,java,cpp,bash&perline=8)](https://skillicons.dev)

### 🗄️ Databases

[![Databases](https://skillicons.dev/icons?i=postgres,mysql,redis,supabase&perline=8)](https://skillicons.dev)

![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### 🖥️ Servers & Infrastructure

![Coolify](https://img.shields.io/badge/Coolify-6B16ED?style=for-the-badge&logoColor=white)
![Incus](https://img.shields.io/badge/Incus_%28LXC%29-E95420?style=for-the-badge&logo=linuxcontainers&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![SSH](https://img.shields.io/badge/SSH-000000?style=for-the-badge&logo=openssh&logoColor=white)

### 🛡️ Security

[![Security](https://skillicons.dev/icons?i=kali&perline=8)](https://skillicons.dev)

![Security Audits](https://img.shields.io/badge/Security_Audits-B71C1C?style=for-the-badge&logoColor=white)
![Hardening](https://img.shields.io/badge/Server_Hardening-37474F?style=for-the-badge&logoColor=white)

### 🧩 Frameworks & Automation

[![Frameworks](https://skillicons.dev/icons?i=django,react,vite&perline=8)](https://skillicons.dev)

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

---

### 🎯 Currently

- 🔭 Hardening and consolidating self-hosted infrastructure.
- 🌱 Going deeper into offensive and defensive security.
- 💬 Ask me about **Linux servers, Docker, self-hosting, n8n or Django**.

### 📫 Let's connect

Most of my work lives in private repositories. Feel free to reach out to talk about infrastructure, security or automation.
