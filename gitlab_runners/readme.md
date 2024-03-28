# Registrar o runner no gitlab
para registrar o runner execute:
docker exec -it gitlab-runner gitlab-runner register

# Configurando o runner

docker exec -it gitlab-runner gitlab-runner register
Runtime platform                                    arch=amd64 os=linux pid=26 revision=81ab07f6 version=16.10.0
Running in system-mode.                            
                                                   
Enter the GitLab instance URL (for example, https://gitlab.com/):
http://gitlab
Enter the registration token:
<INSIRA AQUI O SEU TOKEN>
Enter a name for the runner. This is stored only in the local config.toml file:
[gitlab-runner]: shellrunner
Enter an executor: custom, shell, parallels, docker, docker-windows, docker+machine, ssh, virtualbox, kubernetes, docker-autoscaler, instance:
docker 
Enter the default Docker image (for example, ruby:2.7):
alpine:3.19.1                
Runner registered successfully. Feel free to start it, but if it's running already the config should be automatically reloaded!
 
Configuration (with the authentication token) was saved in "/etc/gitlab-runner/config.toml"