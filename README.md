# Portainer docker compose install guide

## Link to the [Portainer](https://www.portainer.io/) website
Portainer is a great tool to help you manage your containers. If you're new to Docker, Portainer provides you with an easy to use graphical interface, instead of having to use the command line. The traditional method to install Portainer is with "docker run". I prefer to have this part of my docker compose yml file.

### Assumptions:
You already have Docker intalled on your Linux server.

- Docker install [guide](https://docs.docker.com/engine/install/).
- Follow the post install [guide](https://docs.docker.com/engine/install/linux-postinstall/) and add your user to the docker group.

### Installation:
In your home directory create an App Data folder for all of your Docker config files. "appdata", "docker" are common folder names you can use.
```
mkdir appdata
cd appdata
mkdir portainer
```
Add the contents of the attached 'docker-compose-portainer.yml' file to your existing docker-compose.yml file
```

