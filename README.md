# Frappe Docker

## Docker build and run command
```
docker ps -q -a --filter label=com.docker.compose.project=frappe_docker_devcontainer --filter label=com.docker.compose.service=frappe

docker compose -f /media/ubuntu/Projects3/ERP/v14/frappe_docker/.devcontainer/docker-compose.yml --profile * config
```
