# Docker Todo List!

#### Linguagens utilizadas

    * Docker

#### A pasta todo-app é de propriedade intelectual da [Trybe](https://www.betrybe.com/)! ⚠️

---

## Descrição

Temos, neste projeto, uma série de comandos com diferentes níveis de complexidade que devem ser resolvidos cada um em seu arquivo próprio. As habilidade utilizadas nesse projeto foram:

  * Usar comandos dockers no CLI - Interface de linha de comando;
  
  * Criar um contêiner Docker para uma aplicação de front-end;
  
  * Criar um contêiner Docker para uma aplicação de back-end;
  
  * Criar um contêiner Docker para uma aplicação de testes;
  
  * Orquestrar os três contêineres utilizando o Docker compose.
  

#### Status do projeto: em desenvolvimento ⚠️

---

## Como rodar o projeto localmente

1. Clone o repositório
  * `git@github.com:Murilo-Carrijo/Projeto-BackEnd-Doker-Todo-List-Docker.git`
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd Projeto-BackEnd-Doker-Todo-List-Docker`

2. Instale as dependências e inicialize o projeto
  * Instale as dependências:
    * `npm install`

---

## Desenvolvimento

O projeto foi realizado durante o curso da Trybe e os seguintes requisitos precisariam ser cumpridos: 

  - [X] 1 - _Crie um novo container de modo interativo sem roda-lo nomeando-o como '01container' e utilizando a imagem 'alpine' usando a versão '3.12'_

  - [X] 2 - _Inicie o container '01container'_

  - [X] 3 - _Liste os containers filtrando pelo nome '01container'_

  - [X] 4 - _Execute o comando 'cat /etc/os-release' no container '01container' sem se acoplar a ele_

  - [X] 5 - _Remova o container '01container' que está em andamento_

  - [X] 6 - _Faça o download da imagem 'nginx' com a versão '1.21.3-alpine' sem criar um container_

  - [X] 7 - _Rode um novo container com a imagem 'nginx' com a versão '1.21.3-alpine' em segundo plano nomeando-o como '02images' e mapeando sua porta padrão de acesso para porta '3000' do sistema hospedeiro_

  - [X] 8 - _Pare o container '02images' que está em andamento_

  - [X] 9 - _Gere uma build a partir do Dockerfile do back-end do 'todo-app' nomeando a imagem para 'todobackend'_

  - [X] 10 - _Gere uma build a partir do Dockerfile do front-end do 'todo-app' nomeando a imagem para 'todofrontend'_

  - [ ] 11 - _Gere uma build a partir do Dockerfile dos testes do 'todo-app' nomeando a imagem para 'todotests'_
  
  ### Requisitos Bônus:

  - [ ] 12 - _Suba uma orquestração em segundo plano com o docker-compose de forma que back e front end consigam se comunicar_


  