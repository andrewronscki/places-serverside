

<h1 align="center">
     🌍 <a href="#" alt="site do places"> Places Serverside</a>
</h1>

<h3 align="center">
    🧳 Sua api para gerenciar lugares para se conhecer ao redor do mundo. 💚
</h3>

<div align="center">
<p align="center">
<a><img alt="GitHub package.json version" src="https://img.shields.io/github/package-json/v/andrewronscki/places-serverside"></a>
<a href='https://coveralls.io/github/andrewronscki/places-serverside?branch=main'><img src='https://coveralls.io/repos/github/andrewronscki/places-serverside/badge.svg?branch=main' alt='Coverage Status' /></a>
<a><img alt="GitHub" src="https://img.shields.io/github/license/andrewronscki/places-serverside"></a>
<a><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/andrewronscki/places-serverside"></a>
<a><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/andrewronscki/places-serverside"></a>
<a><img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/andrewronscki/places-serverside"></a>
</p>
</div>

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre o projeto](#-sobre-o-projeto)
   * [Funcionalidades](#-funcionalidades)
   * [Como executar o projeto](#-como-executar-o-projeto)
     * [Pré-requisitos](#pré-requisitos)
     * [Rodando o Backend (servidor)](#user-content--rodando-o-backend-servidor)
   * [Tecnologias](#-tecnologias)
     * [Server](#user-content-server--nodejs----typescript)
   * [Autor](#-autor)
   * [Licença](#user-content--licença)
<!--te-->


## 💻 Sobre o projeto

🌍 Places Serverside - é uma forma de gerenciar lugares para você conhecer, podendo cadastrar, atualizar, buscar e remover lugares.


É uma API rest que permita o CRUD de lugares para se conhecer ao redor do mundo para alimentar seu clientside.

Swagger da aplicação disponível em: http://api.places.andrewronscki.com/docs

<div align="center">
  <img alt="Swagger Places Api" src="./swagger.png">
</div>

---

## ⚙️ Funcionalidades

- [x] Lugares:
  - [x] Cadastrar lugar
  - [x] Atualizar lugar
  - [x] Buscar um lugar
  - [x] Buscar todos os lugares
  - [x] Remover um lugar

---

## 🚀 Como executar o projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/), [Docker](https://docs.docker.com/desktop/), [NestJS](https://nestjs.com/).
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲 Rodando o Backend (servidor)

```bash

# Clone este repositório
$ git clone git@github.com:andrewronscki/places-serverside.git

# Acesse a pasta do projeto no terminal/cmd
$ cd places-serverside

# Instale as dependências
$ npm install

# Crie um arquivo .env com o conteúdo do .env.example
$ cp .env .env.example

# Faça as alterações no arquivo .env caso tenha necessidade

# Execute a aplicação com docker-compose
$ docker-compose up

# O servidor inciará na porta:9001 - acesse http://localhost:9001/docs

```
<p align="center">
  <a href="https://github.com/andrewronscki/places-serverside/blob/main/insomnia.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### [](https://github.com/tgmarinho/Ecoleta#server-nodejs--typescript)**Server**  ([NestJS](https://nodejs.org/en/))
-   **[Typescript](https://www.typescriptlang.org/)**
-   **[Postgres](https://www.postgresql.org/)**
-   **[TypeORM](https://typeorm.io/)**
-   **[Jest](https://jestjs.io/pt-BR/)**
-   **[dotENV](https://github.com/motdotla/dotenv)**

> Veja o arquivo  [package.json](https://github.com/andrewronscki/places-serverside/blob/main/package.json)

---

## 🦸 Autor

<a href="https://andrewronscki.com">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/32884775?v=4" width="100px;" alt=""/>
 <br />
 <sub><b>André Wronscki Ricardo</b></sub></a> <a href="https://andrewronscki.com" title="André Wronscki">🚀</a>
 <br />
 <br />


[![Linkedin Badge](https://img.shields.io/badge/-André-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/andr%C3%A9-wronscki-ricardo-13694bb7/)](https://www.linkedin.com/in/andr%C3%A9-wronscki-ricardo-13694bb7/)
[![Gmail Badge](https://img.shields.io/badge/-andrewronscki@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:andrewronscki@gmail.com)](mailto:andrewronscki@gmail.com)

---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE.md).
