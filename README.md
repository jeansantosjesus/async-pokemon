# Pokemon Async - API REST
![](https://i.imgur.com/xG74tOh.png)

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/KarlaSilvaEng/biblioteca-online?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/KarlaSilvaEng/biblioteca-online">
  
  <a href="https://github.com/KarlaSilvaEng/biblioteca-online/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/KarlaSilvaEng/biblioteca-online">
  </a>
  
  <!-- <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen"> -->
  
   <a href="https://cubos.academy/">
    <img alt="Feito por Jean Jesus" src="https://img.shields.io/badge/feito-por%Jean%20Jesus-D818A5">
   </a>
   
   <a href="https://github.com/cubos-academy/academy-template-readme-projects/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/cubos-academy/academy-template-readme-projects?style=social">
  </a>
   
<h4 align="center"> 
	🚧 Pokemon Async 🚧
</h4>

<p align="center">
	<img alt="Status Em Desenvolvimento" src="https://img.shields.io/badge/STATUS-CONCLUÍDO-green">
</p>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
<a href="#-entidade">Entidade</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a>
</p>

---
## 💻 Sobre o projeto

O projeto Pokemon Async foi desenvolvido após a aula de API REST do curso de Javascript com foco em backend da [Cubos Academy](https://cubos.academy/). A aplicação fornece uma série de informações sobre pokemon, basta digitar o nome ou id do pokemon desejado.

---
## ⚙ Funcionalidades

- [x] Consultar Pokemons


---
## 📘 Entidade
- [x] Pokemon 
      - id, name, height, weight, base_experience, forms, abilities, species

---
## 🛣 Como executar o projeto

Este projeto consiste apenas no Backend e não trabalha com banco de Dados no momento.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲 Rodando o Servidor

```bash

# Clone este repositório
$ git clone https://github.com/JeanNewb/async-pokemon.git

# Acesse a pasta do projeto no terminal/cmd
$ cd async-pokemon

# Instale as dependências
$ npm install
$ npm install express

# Execute a aplicação em modo de desenvolvimento
$ npm run dev

# O servidor inciará na porta:3000 - acesse http://localhost:3000

```

#### Utilizando o Insomnia para Acessar as Funcionalidades
#### Consultar Pokemon
- Método: GET
- Endpoint: '/pokemon'
- Resposta: Listagem da coleção pokemon por página (id) ou por nome.
- Exemplo:
  - URL Completa: http://localhost:3000/pokemon
  - Resposta:
    
    ![image](https://github.com/JeanNewb/async-pokemon/assets/59174015/cd9bfcc8-1aa5-4642-99d0-7b3b1fb57c33)


    
#### Consultar um Livro através do ID
- Método: GET
- Endpoint: '/pokemon/:idOuNome'
- Resposta: Retorna o objeto livro que corresponde ao id fornecido
- Exemplo:
  - URL Completa: http://localhost:3000/pokemon/ivysaur
  - Resposta:
    
    ![image](https://github.com/JeanNewb/async-pokemon/assets/59174015/f3c77224-791b-4512-822b-db5f62d21e25)


---
## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### [](https://github.com/JeanNewb/async-pokemon#server-nodejs--typescript)**Server**  ([NodeJS](https://nodejs.org/en/) 

-   **[Express](https://expressjs.com/)**

> Veja o arquivo  [package.json](https://github.com/JeanNewb/async-pokemon/blob/master/package.json)

#### [](https://github.com/cubos-academy/academy-template-readme-projects#utilit%C3%A1rios)**Utilitários**

-   Editor:  **[Visual Studio Code](https://code.visualstudio.com/)** 
-   Markdown:  **[StackEdit](https://stackedit.io/)**,  **[Markdown Emoji](https://gist.github.com/rxaviers/7360908)**
-   Teste de API:  **[Insomnia](https://insomnia.rest/)**
---

## 💪 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`

---
