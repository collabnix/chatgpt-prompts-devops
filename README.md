![stars](https://img.shields.io/github/stars/collabnix/chatgpt-prompts-devops)
![forks](https://img.shields.io/github/forks/collabnix/chatgpt-prompts-devops)
![Discord](https://img.shields.io/discord/1020180904129335379)
![issues](https://img.shields.io/github/issues/collabnix/chatgpt-prompts-devops)
![Visitor count](https://shields-io-visitor-counter.herokuapp.com/badge?page=collabnix.chatgpt-prompts-devops)
![Twitter](https://img.shields.io/twitter/follow/collabnix?style=social)


# ChatGPT Prompts for Docker

| S.No. | Category                                     | Description              | Example | Result |
|-------| ------------------------------------------------------- | ------------------------- | ------------------------- | ----------- |
| 1 | Docker | Virtual Testing Environment | Hello GPT. Good Morning. I want you to act as a Mac terminal. Docker Desktop is already installed. I will type some commands and you'll reply with what the terminal should show. Show me the results using Mac terminal. When I tell you something, I will do so by putting text inside curly brackets like this. My first command is the "docker -v" | Docker version 20.10.23, build 7155243 |
| 2 | Docker | Virtual Testing Environment| {docker run -d -p 81:80 ajeetraina/webpage} | |
| 3 | Docker |Virtual Testing Environment | {{docker ps}} | |
| 4 | Docker |Virtual Testing Environment | {wget https://github.com/docker/awesome-compose && cd awesome-compose/flask-redis && docker compose up}} | |
| 5 | Docker |Virtual Testing Environment |  {docker compose ps} | |

 ## ChatGPT Prompts for Kubernetes

| S.No. | Category                                     | Description              | Example | Result |
|-------| ------------------------------------------------------- | ------------------------- | ------------------------- | ----------- |
| 1 | Kubernetes | Virtual Testing Environment | Hello GPT. Good Morning. I want you to act as a Mac terminal. Kubernetes is already installed. I will type some commands and you’ll reply with what the terminal should show. Please show the result using the Mac terminal. When I tell you something, I will do so by putting text inside curly brackets {like this}. Please don’t write an explanation just the command result is sufficient. My first command is the kubectl version. | Client Version: version.Info{Major:"1", M.. |
| 2 |  Kubernetes | Virtual Testing Environment | {kubectl get po,deploy,svc} | |
| 3 |  Kubernetes | Virtual Testing Environment | {kubectl run –image=nginx nginx-app –port=80 –env=”DOMAIN=cluster”} | |
| 4 |  Kubernetes | Virtual Testing Environment | {kubectl expose deployment nginx-app –port=80 –name=nginx-http}  | |
| 5 |  Kubernetes | Virtual Testing Environment | {kubectl get po,svc,deploy} | |
| 6 |  Kubernetes | Virtual Testing Environment | {curl 10.100.67.94:80}| |

  

## ChatGPT Prompts for Helm Chart

| S.No. | Category                                     | Description              | Example | Result |
|-------| ------------------------------------------------------- | ------------------------- | ------------------------- | ----------- |
| 1 |  Kubernetes | Virtual Testing Environment | {helm repo add bitnami https://charts.bitnami.com/bitnami} |
| 2 |  Kubernetes | Virtual Testing Environment | {helm repo update} |
| 3 |  Kubernetes | Virtual Testing Environment | {helm install bitnami/mysql –generate-name} |
| 4 |  Kubernetes | Virtual Testing Environment | {helm show chart bitnami/mysql} |









