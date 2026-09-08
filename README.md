# MyFirstDockerApp

## Docker image publishing secrets

The CI workflow supports both secret pairs below:

- Preferred: `DOCKERHUB_USERNAME` and `DOCKERHUB_TOKEN`
- Backward-compatible: `DOCKER_USERNAME` and `DOCKER_PASSWORD`

For successful `docker push`, use a Docker Hub Personal Access Token with at least **Read** and **Write** permissions.