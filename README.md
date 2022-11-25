# Trabalho-G2-SO
Entrega do trabalho G2 de Sistemas Operacionais 

PROJETO DE: BENHUR MACHADO, EDUARDO ROSSATTO, MURILO ZANETTE.

Com o objetivo de realizar o trabalho da G2 na matéria de Sistemas Operacionais, buscamos por uma API que utilize o Docker/Docker Compose.
Encontramos o GITEA, uma aplicação self-hosted prática que utiliza os serviços do GIT, uma aplicação similar ao GitHub, Bitbucket e GitLab, com seu código-fonte
feito em Go e disponibilizado sob a licença do MIT. O GITEA possui código aberto, fácil instalação, através de um executável ou pacote do Docker, é leve, podendo
rodar até mesmo no barato Raspberry Pi, e possui ainda é Multi-plataforma, podendo rodar em todos SO que o Go é capaz de compilar.

Como utilizar:
Com o Docker/Docker Compose instalado, utilizamos os seguintes comandos:

$ git clone https://github.com/docker/awesome-compose.git

$ cd awesome-compose/

$ cd gitea-postgres/

$ sudo docker compose up -d

Após o início dos containers utilizamos o seguinte comando para verificação dos mesmos:

$ sudo docker ps

Por fim navegamos para o link do host:

http://localhost:3000



Referências: https://gitea.io/pt-br/
