## Deployment Architecture

Developer → GitHub → GitHub Actions → Docker Hub → Container Runtime

- Code pushed to GitHub triggers CI/CD pipeline
- Pipeline builds Docker image
- Image is pushed to Docker Hub
- Container can be deployed anywhere (local / cloud)

## Docker Image

https://hub.docker.com/r/dattag/devops-demo-app
