# Docker

## Basic Comands

`docker version` -> Verifica a versão do docker <br>
<br>

`docker container run contanerName ` -> Executa um container <br>
`docker container run -it contanerName /bin/bashgd` -> Executa um container no modo iterativo, ou seja acessamos o container <br>
`docker container ls` -> lista os container em execução <br>
`docker container ls -a` -> lista os container inclusive os parados <br>
`docker container inspect contanerName` -> traz detalhes de determinada imagem <br>
`docker container stop contanerName` ->  Parar um container<br>
`docker contaner start contanerName` -> iniciar um container <br>
`docker container restart contanerName` -> Restartar um container<br>
`docker container rm contanerName` -> Remove um container<br>
`docker container rm -f contanerName` -> remove um container em execução<br>
`docker container top contanerName` -> traz os processos em execução <br>
`docker container status contanerName` -> traz informações sobre o consumo de recursos como CPU e memória<br>
`docker container exec contanerName` -> Executa algo no container<br>
`docker container exec -it contanerName /bin/bash` -> entra no container para executar algum outro comando.<br>
`docker container attach contanerName` -> Conecta com o container<br>

### Parametros

`-it` -> para entrar no container <br>
`-d` -> para instanciar container e liberar o terminal EX: *docker container run -d nginx* <br>
`-p` -> para mapear portas do container - **... -p localhost:containerPort** *ex: docker container run -p 8080:80 nginx* <br>


## Services

`docker service create` -> Cria um service <br>
`docker service ls` -> lista os serviços <br>
`docker service inspect` -> traz detalhes do service <br>
`docker service scale` -> Aumenta/diminui a quantide de réplicas de um serviço <br>
`docker service ps` -> lista os pogs de um service <br>
`docker service logs` -> logs de um service <br>
`docker service rm ` -> remove um service <br>


## Stack

`docker stack deploy` -> Realiza o deploy de uma stack <br>
`docker stack ls` -> lista as stacks <br>
`docker stack services` -> lista os services de uma stack <br>
`docker stack rm` -> Remove uma stack <br>
`docker stack inspect` -> Traz detalhes sobre uma stack <br>


## Swarm

`docker swarm init` -> inicia um cluster Swarm <br>
`docker swarm join` -> Comando para adicionar novos nodes no cluster <br>
`docker swarm ls` -> lista os nodes de um cluster <br>
`docker swarm join-token manager` -> Lista os tokens para adicionar novos managers ao cluster <br>
`docker swarm join-token worker` -> Lista o token para adicionar novos workers ao cluster  <br>
`docker swarm leave` -> Para que o node saia do cluster <br>
`docker swarm leave --force` -> Para que um node manager saia do cluster 
<br>

`docker node inspect ` -> Traz detalhes sobre o node <br>
`docker node promote` -> Promove um node para manager <br>
`docker node demote` -> Muda um node manager para worker <br>
`docker node rm` -> Remove um node <br>
<br>




<style>
code {
  color: #4ED0FB
}

h1, h2, h3 {
  color: green
}

body{
    color: #D3D3D3;
    font-size: 15px
}

</style>