[![Docker Automated build](https://img.shields.io/docker/automated/hendrik44/docker-compose-jira.svg)](https://github.com/Hendrik44/docker-compose-jira) [![Docker Build Status](https://img.shields.io/docker/build/hendrik44/docker-compose-jira.svg)](https://github.com/Hendrik44/docker-compose-jira) [![Open Issues](https://img.shields.io/github/issues/hendrik44/docker-compose-jira.svg)](https://github.com/Hendrik44/docker-compose-jira/issues) [![Stars on GitHub](https://img.shields.io/github/stars/hendrik44/docker-compose-jira.svg)](https://github.com/Hendrik44/docker-compose-jira/stargazers) [![Forks on GitHub](https://img.shields.io/github/forks/hendrik44/docker-compose-jira.svg)](https://github.com/Hendrik44/docker-compose-jira/network) [![Stars on Docker Hub](https://img.shields.io/docker/stars/hendrik44/docker-compose-jira.svg)](https://hub.docker.com/r/hendrik44/docker-compose-jira/) [![Pulls on Docker Hub](https://img.shields.io/docker/pulls/hendrik44/docker-compose-jira.svg)](https://hub.docker.com/r/hendrik44/docker-compose-jira/)

# Atlassian JIRA in a Docker Container

Easy use Atlassians Jira in a Docker-Container and manage it via docker-compose.

If you have issues please read first the atlassian docs before open an issue.

## Start it up

Run the following command:
1. ```curl -O https://raw.githubusercontent.com/Hendrik44/docker-compose-jira/master/docker-compose.yml```
2. Change the Database password and other settings in docker-compose-file like proxy ...
3. Run the container ```docker-compose up -d```

Open your browser and navigate to `http://[dockerhost]:8080` and finish the configuration or import a Backup.

## License
MIT