

![İsimsiz video ‐ Clipchamp ile yapıldı (2)](https://github.com/user-attachments/assets/105d890f-8766-4a33-9766-41378de87e0f)


# Ollama ve Open WebUI Kurulumu

Bu rehber, **CodeLlama 7B** modelini ve **Open WebUI**'yi çalıştırmak için gerekli adımları içermektedir. Aşağıdaki komutlarla, sisteminizi hızla kurabilirsiniz.

## Gereksinimler

- Docker ve Docker Compose yüklü bir sistem.
- NVIDIA GPU ve uyumlu CUDA sürümü (isteğe bağlı ancak önerilir).

## 1. Komutlar

Öncelikle, GitHub reposunu yerel bilgisayarınıza klonlayın:

```bash
git clone https://github.com/cancakmk/ollama-webui-nvidia.git

cd ollama-webui-nvidia

docker-compose up -d

docker ps

docker exec -it <ollama_konteyner_id> bash

ollama run codellama:7b
```

# Ollama and Open WebUI Setup

This guide outlines the steps required to run the **CodeLlama 7B** model and **Open WebUI**. Follow the commands below to quickly set up your system.

## Requirements

- A system with Docker and Docker Compose installed.
- An NVIDIA GPU and compatible CUDA version (optional but recommended).

## 1. Commands

First, clone the GitHub repository to your local machine:

```bash
git clone https://github.com/cancakmk/ollama-webui-nvidia.git

cd ollama-webui-nvidia

docker-compose up -d

docker ps

docker exec -it <ollama_konteyner_id> bash

ollama run codellama:7b
```
