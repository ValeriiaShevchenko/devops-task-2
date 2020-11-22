url: localhost:8080
login: root
password: gitlabgitlab

project - Scribejava

1. Run docker-compose up -d
2. Wait until gitlab-web is available on localhost:8080
3. Import project from code folder
4. Get Token from CI/CD config in project configuration
5. Register runner with correct token using script gitlab-runner1-config/gitlab-runner-register.sh
6. Build the project
