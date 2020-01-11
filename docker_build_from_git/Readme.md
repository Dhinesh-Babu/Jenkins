# Docker image Build from a GIT repo.
This Folder is for automating jenkins to automatically build a dockerimage from a docker file and run it in the local machine.
# Flow
- Pull data from repo
- Build dockerimage using Dockerfile
- Docker-compose to run it.
- Stop docker-container
- Shutdown
# Notes
- Jenkins Runs the task manually, and not poll. (To save space. This can be configured easily)

