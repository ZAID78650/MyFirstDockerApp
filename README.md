# MyFirstDockerApp

## Docker image publishing secrets

The CI workflow requires these secrets:

- `DOCKERHUB_USERNAME`
- `DOCKERHUB_TOKEN`

For successful `docker push`, use a Docker Hub Personal Access Token with at least **Read** and **Write** permissions.