 TASK 4: Web Server using Docker 
 
 Container Lifecycle -
 
 docker run <image> → Create + Start a container
 docker ps -a → List all containers
 docker stop <id> / docker kill <id> → Stop container (graceful vs force)
 docker restart <id> → Restart
 docker rm <id> → Remove

 Monitoring & Troubleshooting -
 docker logs <id> → View container logs
 docker stats → Real-time CPU & memory usage
 docker exec -it <id> bash → Access shell inside container
 docker inspect <id> → Detailed config & state

 Deployment Best Practices -
 Use lightweight images (e.g., alpine)
 Add a .dockerignore to exclude unnecessary files
 Apply multi-stage builds to keep images small
 Run as non-root user for security
 Define HEALTHCHECK in Dockerfile
 Use Docker networks for internal service communication
 For scaling → use Docker Compose / Swarm / Kubernetes
