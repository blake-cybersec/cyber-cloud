# Cyber Cloud Project

## Overview
The Cyber Cloud project, tailored for the CyberTitans club, serves as a comprehensive platform offering club members access to a suite of web-based tools crucial for engaging in Capture The Flag (CTF) activities. CTFs involve various challenges and require a diverse set of tools, and the Cyber Cloud project is designed to streamline access to these resources. This documentation provides insights into the Docker containers utilized in the project, as well as a dedicated section for Proxmox.


## Proxmox Section (To be filled)

[//]: # (Proxmox section to be added here)


## Docker Containers

### Docker
Docker is a containerization platform that streamlines application development, deployment, and execution. At its core, Docker uses containers lightweight, standalone packages that encapsulate an application and its dependencies. These containers are created from Docker images, which serve as blueprints specifying the application's runtime, code, libraries, and system tools. A Dockerfile, a set of instructions defining the image, automates the image creation process. The Docker daemon manages these containers, while the Docker client enables users to interact with the daemon via command-line tools or APIs. Docker promotes consistency across different environments, providing isolation, portability, and efficient resource usage. It employs a layered file system for optimized image management and supports container orchestration tools for scaling and managing applications at scale, making it a widely adopted solution for building and running applications.

In essence, Docker facilitates the packaging of applications into self-contained, reproducible units that can run consistently across various environments. Its containerization approach ensures efficiency, security, and scalability in the development and deployment lifecycle, making it a fundamental tool for modern software development.

### aperisolve_back
- **Status:** Running
- **Image:** aperisolve/aperisolve_backend
- **Created:** 2023-10-09 20:37:30
- **IP Address:** 172.18.0.5
- **Port:** Not specified

### aperisolve_web
- **Status:** Running
- **Image:** aperisolve/aperisolve_web:latest
- **Created:** 2023-10-09 21:33:44
- **IP Address:** 172.18.0.3
- **Port:** Not specified

### cybercheff
- **Status:** Running
- **Image:** mpepping/cyberchef:latest
- **Created:** 2023-10-09 22:01:38
- **IP Address:** 172.17.0.3
- **Port:** 8111:8000

### cybertitans-container-cloudflare
- **Status:** Running
- **Image:** cloudflare/cloudflared:2023.2.1
- **Created:** 2023-10-09 21:29:18
- **IP Address:** 172.18.0.4
- **Port:** Not specified

### homarr
- **Status:** Running
- **Image:** ghcr.io/ajnart/homarr:latest
- **Created:** 2023-10-10 20:13:01
- **IP Address:** 172.20.0.2
- **Port:** 7575:7575

### homarr-dash-1
- **Status:** Running
- **Image:** mauricenino/dashdot:latest
- **Created:** 2023-10-10 20:12:01
- **IP Address:** 172.20.0.3
- **Port:** 80:3001

### mongodb
- **Status:** Running
- **Image:** mongo:4.0.8
- **Created:** 2023-10-09 20:37:30
- **IP Address:** 172.18.0.2
- **Port:** Not specified

### portainer
- **Status:** Running
- **Image:** portainer/portainer-ce:latest
- **Created:** 2023-10-09 11:43:52
- **IP Address:** 172.17.0.2
- **Port:** 8000:8000, 9443:9443

### runfile-db-1
- **Status:** Running
- **Image:** mariadb:10.1
- **Created:** 2023-11-01 15:45:18
- **IP Address:** 172.22.0.3
- **Port:** Not specified

### runfile-web-1
- **Status:** Exited
- **Image:** filerun/filerun:8.1
- **Created:** 2023-11-01 15:45:29
- **IP Address:** Not applicable
- **Port:** Not applicable



