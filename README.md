# Local-Embedder
Setup for local embedder

# Quickstart

1. Install [`docker`](https://docs.docker.com/get-docker/), [`docker compose`](https://docs.docker.com/compose/install/) and clone the repo: 
   ```bash 
   git clone https://github.com/cheshire-cat-ai/local-embedder.git
   ```
2. Copy the .env.example and set the params:
   ```bash 
   cp .env.example .env && nano .env
   ```
3. Build the container
   ```bash
   docker-compose build
   ```
4. Start up the container
    ```bash 
   docker-compose up
   ```

