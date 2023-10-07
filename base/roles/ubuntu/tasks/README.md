## Content for main.yaml

### ubuntu_server.yaml
1- Upgrade packages (apt update && apt upgrade)
2- Remove non-required packages (apt autoremove)
3- Hardening SSH --> Passing ssh_config file

### docker_install.yaml
1- Install docker
> * Possible to deploy specific containers within it.

2- Install docker-compose 


### services.yaml
1- Get photoprism config file for docker-compose & Place it locally
> * Requires manual intervention to set custom values for its installation,
> * once that is done, it should be as easy as sending doker-compuse up -d command

2- Deploy vaultwarden container
- Pending to connect it to a also automated deployment of a proxy (mandatory for vaultwarden)


