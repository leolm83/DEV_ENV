# Na primeira execucao para obter a senha do usuario root

sudo docker exec -it gitlab grep 'Password:' /etc/gitlab/initial_root_password