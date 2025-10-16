 TASK 2: Jenkins Remoting Project
# Components:
1. Jenkins Controller – The main Jenkins server managing builds and pipelines.
2. Docker Agents – Remote worker nodes connected via Jenkins Remoting protocol.
3. Docker Network – Custom bridge network for secure communication between containers.

# Security Measures

1. Each agent runs inside its own Docker container, ensuring isolation.
2. Agents connect via Jenkins’ JNLP (Remoting) protocol securely.
3. Controller and agents communicate through a private Docker network only.

# Key Learnings

1. How to connect remote Jenkins nodes using Docker.
2. How to distribute builds across multiple environments.
3. How to use Jenkins Remoting effectively.
4. How to secure Jenkins communication using container isolation.






