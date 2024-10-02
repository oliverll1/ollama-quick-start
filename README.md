# Ollama Self-Hosting Setup
Basic setup to run self-hosted Ollama and use LLMs locally (Works with Coolify)

## Requirements
- Ubuntu 22.04
- Nvidia GPU
- [Docker](https://docs.docker.com/engine/install/ubuntu/)


## Steps
1. Run setup.bash (installs Nvidia drivers, Nvidia CUDA toolkit, and Nvidia Container Toolkit)
2. If using Coolify, paste the docker-compose.yaml content in the Docker Compose section of your project. Otherwise, just run `docker compose up -d` inside the project's folder on your machine.
3. Go to localhost:3000 or the respective Coolify link for your service.


## Installing models
* Model Library: https://ollama.com/library
* Run `docker exec <ollama_container_id> -it ollama pull <modelname>`


## For more information:
- [Ollama](https://ollama.com/)
- [Open Web UI](https://docs.openwebui.com/)
- [CUDA Toolkit](https://developer.nvidia.com/cuda-downloads?target_os=Linux)
- [Nvidia Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html)
- [Coolify](https://coolify.io/)
