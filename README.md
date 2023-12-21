# Cyber Cloud Project

## Overview
The Cyber Cloud project provides members of the college club with access to web-based tools. This documentation outlines the Docker containers used in the project and includes a section for Proxmox.

## Docker Containers

### aperisolve_back
- **Status:** Running
- **Image:** aperisolve/aperisolve_backend
- **Created:** 2023-10-09 20:37:30
- **IP Address:** 172.18.0.5
- **Port:** Not specified
- **User Access:** administrators

### aperisolve_web
- **Status:** Running
- **Image:** aperisolve/aperisolve_web:latest
- **Created:** 2023-10-09 21:33:44
- **IP Address:** 172.18.0.3
- **Port:** Not specified
- **User Access:** administrators

### cybercheff
- **Status:** Running
- **Image:** mpepping/cyberchef:latest
- **Created:** 2023-10-09 22:01:38
- **IP Address:** 172.17.0.3
- **Port:** 8111:8000
- **User Access:** administrators

### cybertitans-container-cloudflare
- **Status:** Running
- **Image:** cloudflare/cloudflared:2023.2.1
- **Created:** 2023-10-09 21:29:18
- **IP Address:** 172.18.0.4
- **Port:** Not specified
- **User Access:** administrators

### homarr
- **Status:** Running
- **Image:** ghcr.io/ajnart/homarr:latest
- **Created:** 2023-10-10 20:13:01
- **IP Address:** 172.20.0.2
- **Port:** 7575:7575
- **User Access:** administrators

### homarr-dash-1
- **Status:** Running
- **Image:** mauricenino/dashdot:latest
- **Created:** 2023-10-10 20:12:01
- **IP Address:** 172.20.0.3
- **Port:** 80:3001
- **User Access:** administrators

### mongodb
- **Status:** Running
- **Image:** mongo:4.0.8
- **Created:** 2023-10-09 20:37:30
- **IP Address:** 172.18.0.2
- **Port:** Not specified
- **User Access:** administrators

### portainer
- **Status:** Running
- **Image:** portainer/portainer-ce:latest
- **Created:** 2023-10-09 11:43:52
- **IP Address:** 172.17.0.2
- **Port:** 8000:8000, 9443:9443
- **User Access:** administrators

### runfile-db-1
- **Status:** Running
- **Image:** mariadb:10.1
- **Created:** 2023-11-01 15:45:18
- **IP Address:** 172.22.0.3
- **Port:** Not specified
- **User Access:** administrators

### runfile-web-1
- **Status:** Exited
- **Image:** filerun/filerun:8.1
- **Created:** 2023-11-01 15:45:29
- **IP Address:** Not applicable
- **Port:** Not applicable
- **User Access:** administrators

## Proxmox Section (To be filled)

[//]: # (Proxmox section to be added here)

