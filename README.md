## Ansible labs 2023


### Collection of all the labs I will be making during my Ansible learning path.

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white)

<!-- ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)
# ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
# ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white) -->


### base directory
1. First contents - Rocky linux target (VM)
- Getting into ansible.cfg file & inventory definition
- Installing software to use VM as web server
- Updating packages
- Managing Services (httpd)
- Hardening SSH access by disabling password authentication (regex)
- To-do: Apply cron-job

2. (to-do) One Step further - Local irl server (HP EliteDesk 800 G2 Micro). [1]
- Installing software to use docker containers
- Hardening SSH by passing config file directly*
- Idea/Concept: Deploy a local jenkins server for CI/CD learning.
- Idea/Concept: Use shell/command to get server status at Ansible execution and save as custom log files, if able.


> *Previously retrieved by using scp command from same server.


[1] https://support.hp.com/mx-es/document/c04850298

Intel i5 6500

16GB ram

480GB internal storage

OS: Ubuntu Server 22.04.03 LTS

Side-project: Add external usb drive HDD drive to be used as containers volume storage