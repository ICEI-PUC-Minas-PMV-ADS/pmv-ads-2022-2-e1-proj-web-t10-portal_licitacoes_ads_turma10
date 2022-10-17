# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

A solução proposta é alcançada através do processamento de dados por uma interface WEB interativa. O detalhamento da mesma é desenvolvido a seguir:

![Arquitetura da Solução](https://user-images.githubusercontent.com/114961595/196012704-ac8ea017-4d55-483a-81bd-2c5a71580643.jpg)


## Diagrama de componentes

Diagrama que permite a modelagem física de um sistema, através da visão dos seus componentes e relacionamentos entre os mesmos.


A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema;  
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
   - **Local Storage** - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
     - **Notícias** - seções de notícias apresentadas 
     - **Processos** - registro de dos processos de arquivados pelo usuário e acesso posterior
     - **Comentários** - registro de comentários dos usuários sobre as notícias
 - **News API** - plataforma que permite o acesso às notícias exibidas no site.
 - **Hospedagem do site** - Heroku. Local na Internet onde as páginas são mantidas e acessadas pelo navegador. 
 - **Hospedagem dos arquivos** - Github. Local onde são armazenados os arquivos e códigos da aplicação.


## Tecnologias Utilizadas

- HTML;
- CSS;
- JAVASCRIPT;
- BOOTSTRAP;
- VS CODE;
- MARVELAPP;
- TRELLO;
- GOOGLE DOCS;
- GIT HUB;

![UserFlowInternet](https://user-images.githubusercontent.com/114961595/196013058-d963a4c8-275e-46d0-a9ac-59a6d3501338.jpg)


## Hospedagem

Optamos por utilizar a plataforma Heroku para hospedagem do site. 


