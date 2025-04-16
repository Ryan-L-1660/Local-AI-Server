# Local-AI-Server
An Ubuntu Desktop computer running ollama and openwebui inside of docker.

## - Overview 
This project is a self-hosted AI server using **Ubuntu Desktop** as the OS and has **Docker** for containerization and **Ollama** for running lightweight LLMs. The server is only for local computers with the **Open-WebUI** login. 


## System Specs
- **CPU** AMD Ryzen 5 1500x (4c/8t)
- **RAM** 32gb mismatched DDR4 2133
- **GPU** Nvidia Geforce GT 1030 (Only for display out, CPU used for AI models)
- **SSD** Adata 128gb sata ssd
- **MOBO** Gigabyte B350 A gaming
- **Internet** Ethernet connection to a switch.
- **OS** Ubuntu Desktop (24.04.2 LTS)





## Links for Installation

- **Docker installation** 
https://docs.docker.com/engine/install/ubuntu/

- **Ubuntu installation**
https://ubuntu.com/download/desktop

- **Ollama installation**
https://ollama.com/download/linux

- **Open-WebUI installation**
https://github.com/open-webui/open-webui


## What I learned doing this 
- How to install and setup **Docker Desktop** for server usage
- How to run **AI models** locally using **Ollama** (Including optimizations for CPU-only usage)
- Learned how to create and manage **Docker containers** for self-hosted services.
- Gained hands-on experience with **Docker compose** for container creation.
- Gained understanding of how **YAML** files work and their role in Docker configurations
- Configured **networking and access controls** to ensure secure access to the AI server within my local network

## Security 
- The server is designed to be **accessible only from devices on the local network**.
- **Open-WebUI** is secured with a login, and only **my account** can access the AI server, ensuring that no unauthorized users can interact with the system.
- Future plans include improving security with a **firewall** and using **pfSense** for network segmentation if necessary.