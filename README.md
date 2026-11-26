## Hola, soy Stiben 👋

### 🔐 Infraestructura y Seguridad · Desarrollador Full-Stack

Llevo aplicaciones empresariales desde la idea hasta producción **y las mantengo funcionando de forma segura**.
Diseño los servidores donde viven, los endurezco, despliego y monitoreo los servicios, automatizo los procesos
a su alrededor y construyo la aplicación en sí: base de datos, API e interfaz.

Mi trabajo está donde se cruzan el **desarrollo, la infraestructura y la seguridad**. Me importa menos
"funciona en mi máquina" y más: *¿Está aislado? ¿Quién puede llegar a él? ¿Hay copia de seguridad? ¿Podemos volver atrás en minutos?*

### 🧠 Sobre mí

- 🏢 Construyo y opero las **plataformas internas de una empresa** del sector contable, financiero, tributario, legal y BPO.
- 🖥️ Administro **servidores Linux de punta a punta**: virtualización, contenedores, proxies inversos, TLS, DNS y acceso SSH.
- 🛡️ Hago **auditorías de seguridad** a sistemas internos y aplico endurecimiento y mínimo privilegio en todo lo que despliego.
- ⚙️ Automatizo procesos de negocio con **n8n**, conectando APIs internas, bases de datos y servicios externos.
- 📊 Empecé en **ciencia de datos** (Python, Pandas, NumPy) y crecí hacia el desarrollo full-stack y la infraestructura.

### 🛠️ Lo que he construido y opero

**🏗️ Plataforma autoalojada en contenedores aislados**
Diseñé una plataforma de despliegue con **Coolify dentro de un contenedor Incus (LXC)** en un VPS.
Cada aplicación, base de datos y caché es un recurso independiente, con su propio ciclo de vida y copias de seguridad.
Las bases de datos solo son accesibles desde la red privada y únicamente se exponen los puertos 80/443.

**🔄 Migraciones a producción sin pérdida de datos**
Migré servicios en vivo entre servidores: una plataforma Django/React, una instancia de **n8n con más de 100 flujos
y más de 60 credenciales cifradas**, y un stack de Supabase. El proceso incluyó volcado y restauración de PostgreSQL
con verificación de conteo de registros, validación de claves de cifrado por comparación de hash (sin exponer secretos),
cambios de DNS con TTL bajo y snapshots de contenedores para volver atrás al instante.

**🧾 Aplicaciones internas de negocio**
Plataformas full-stack (**Django + React + PostgreSQL + Redis**) para procesos administrativos, contables,
de tesorería y de procesamiento de documentos, desplegadas con Docker Compose detrás de Nginx y Traefik.

**🛡️ Auditorías de seguridad**
Revisión de sistemas e infraestructura internos: servicios expuestos, control de acceso,
manejo de secretos y configuración de servidores.

<details>
<summary><b>🇬🇧 English version</b></summary>

### 🔐 Infrastructure & Security · Full-Stack Developer

I take business applications from idea to production **and keep them running safely**.
I design the servers they live on, harden them, deploy and monitor the services, automate the processes
around them, and build the application itself: database, API and interface.

My work sits where **development, infrastructure and security** meet. I care less about "it works on my machine"
and more about: *Is it isolated? Who can reach it? Is there a backup? Can we roll back in minutes?*

### 🧠 About me

- 🏢 I build and operate the **internal platforms of a company** in the accounting, finance, tax, legal and BPO space.
- 🖥️ I administer **Linux servers end to end**: virtualization, containers, reverse proxies, TLS, DNS and SSH access.
- 🛡️ I run **security audits** on internal systems and apply hardening and least privilege to everything I deploy.
- ⚙️ I automate business processes with **n8n**, connecting internal APIs, databases and external services.
- 📊 I started in **data science** (Python, Pandas, NumPy) and grew into full-stack development and infrastructure.

### 🛠️ What I've built and run

**🏗️ Self-hosted platform on isolated containers**
Designed a deployment platform with **Coolify running inside an Incus (LXC) container** on a VPS.
Each application, database and cache is a separate resource with its own lifecycle and backups.
Databases are reachable only from the private network, and only ports 80/443 are exposed.

**🔄 Zero-data-loss production migrations**
Migrated live services between servers: a Django/React platform, an **n8n instance with 100+ workflows
and 60+ encrypted credentials**, and a Supabase stack. The process included PostgreSQL dump/restore
with row-count verification, encryption-key validation by hash comparison (without exposing secrets),
low-TTL DNS cutovers and container snapshots for instant rollback.

**🧾 Internal business applications**
Full-stack platforms (**Django + React + PostgreSQL + Redis**) for administrative, accounting,
treasury and document-processing workflows, deployed with Docker Compose behind Nginx and Traefik.

**🛡️ Security audits**
Review of internal systems and infrastructure: exposed services, access control,
secrets handling and server configuration.

</details>

---

### 💻 Languages

[![Languages](https://skillicons.dev/icons?i=python,nodejs,js,java,cpp,bash&perline=8)](https://skillicons.dev)

### 🗄️ Databases

[![Databases](https://skillicons.dev/icons?i=postgres,mysql,redis,supabase&perline=8)](https://skillicons.dev)

![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### 🖥️ Servers & Infrastructure

![Coolify](https://img.shields.io/badge/Coolify-6B16ED?style=for-the-badge&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![SSH](https://img.shields.io/badge/SSH-000000?style=for-the-badge&logo=openssh&logoColor=white)

### 🛡️ Security

[![Security](https://skillicons.dev/icons?i=kali&perline=8)](https://skillicons.dev)




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
