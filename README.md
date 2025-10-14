# TASK 4: Web Server using Docker 
 
# Container Lifecycle -
 
1. docker run <image> → Create + Start a container
2. docker ps -a → List all containers
3. docker stop <id> / docker kill <id> → Stop container (graceful vs force)
4. docker restart <id> → Restart
5. docker rm <id> → Remove

 # Monitoring & Troubleshooting -
 1. docker logs <id> → View container logs
 2. docker stats → Real-time CPU & memory usage
 3. docker exec -it <id> bash → Access shell inside container
 4. docker inspect <id> → Detailed config & state

 # Deployment Best Practices -
 1. Use lightweight images (e.g., alpine)
 2. Add a .dockerignore to exclude unnecessary files
 3. Apply multi-stage builds to keep images small
 4. Run as non-root user for security
 5. Define HEALTHCHECK in Dockerfile
 6. Use Docker networks for internal service communication
 7. For scaling → use Docker Compose / Swarm / Kubernetes
