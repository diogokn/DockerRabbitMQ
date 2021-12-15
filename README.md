# Docker com container RabbitMQ

Criação de um Docker e Baixar a imagem para instanciar o RabbitMQ

1) Acessar a página do Docker, fazer download e instalar

https://www.docker.com/products/docker-desktop

2) Como resolver o erro start engine
Seguir passo a passo para habilitar

https://docs.microsoft.com/pt-br/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package
Lembrando que o Docker precisa do WSL2

3) Agora vamos baixar a imagem do Container do RabbitMQ.
Vamos precisar criar uma pasta RabbitMQ e um arquivo:

docker-compose.yml
(ver no repositório)

4) Após segui os processos, fazer o restar do Docker Desktop
![image](https://user-images.githubusercontent.com/41928681/146240721-8225dfb8-c090-411e-856d-9704f97f9cbb.png)

5) Abrir o PoweShell, acessar a pasta do arquivo docker-compose.
Dentro da pasta:
![image](https://user-images.githubusercontent.com/41928681/146241596-b6d2960f-a217-4d73-aec3-4f6ab6ca5fa2.png)

6) Acessar a pagina do RabbitMQ

http://localhost:15672/#/

username: admin
password: 123456

![image](https://user-images.githubusercontent.com/41928681/146241743-80dbc1ae-e5bf-4680-aa30-f3bbdada248d.png)

