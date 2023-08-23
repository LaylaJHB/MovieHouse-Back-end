# Movie House

####

---

## 🕵Sobre

API REST desenvolvida para gerenciamento do Banco de Dados MySQL de um E-commerce de filmes chamado Movie House. É possível cadastrar, consultar ou deletar filmes e suas respectivas informações cadastradas no Banco de Dados da Movie House.

## 🛠Tecnologias

Esse projeto foi desenvolvido com as seguintes ferramentas e tecnologias:

* Node.js
* Typescript
* SQL
* MySQL
* API
* Postman
* Knex
* Cors
* Express

---



## 🧵Endpoints

---
#### <div>🔺 MÉTODO: PUT &curarr;</div>


* Cadastrar filme e suas informações   <span class="badge badge-success">Success</span>
  
  ```
  https://movie-house-ecommerce.onrender.com/character
  ```
---
#### <div>🔻 MÉTODO: GET &curarr;</div>
  
* Buscar todos os filmes e suas respectivas informações
  ```
  https://movie-house-ecommerce.onrender.com/character?name= 
  ```
* Buscar um filme em específico pelo título do filme
  ```
  https://movie-house-ecommerce.onrender.com/character?name=**movietitle**
  ```
---
#### <div>🔸 MÉTODO: DELETE &curarr;</div>

* Deletar filme e suas informações
  
  ```
  https://movie-house-ecommerce.onrender.com/character/**id**
  ```


- **Observação:** ** Nos endpoints de _"Buscar todos os filmes"_ e _"Deletar filmes e suas informações"_ substitua **_"movietitle"_** e **_"id"_** pelo nome do filme que deseja buscar e o id do filme que deseja deletar, respectivamente. Para mais informações, acesse a documentação.
---

## 🧭Status do Projeto

* ⏳ Fazendo

---

## 🎯Objetivo do Projeto

Desenvolver API para gerenciamento de um E-commerce

## ☑️Requisitos de Funcionalidade

- [✅] Obter todas as informações presentes no Banco de Dados (BD)
- [✅] Aplicar filtros na busca de informações presentes no BD
- [✅] Realizar busca ordenada de modo a obter resultados em ordem cresc/descrescente
- [✅] Adicionar informações no Banco de Dados
- [✅] Deletar informações do Banco de Dados

---

## 🔗Deploy 


* Render: [Render: Cloud Application Hosting for Developers](https://render.com)

---
## 🔗Documentação

* **Documentação da API no Postman:** [Documentação da API da Movie House](https://documenter.getpostman.com/view/22349688/2s9Y5VVQ87)
* **Ferramenta:** [Postman API Platform ](https://www.postman.com/)
---

## 🛰Rodando o Projeto

Para Rodar o projeto, siga as seguintes etapas :

* **Acesse o terminal:** GitBash, Windows PowerShell ou outro
  * **Clone esse repositório:**
    ```
    git clone https://github.com/LaylaJHB/MovieHouse-Back-end.git
    ```
  * **Instale as dependências do projeto:** rode o comando
    
    ```
    npm install
    ```
* **Crie um arquivo com nome .env no diretório raiz do projeto:**
  ```
  touch .env
  ```

* **Acesse o arquivo .env, adicione as variáveis de ambiente e preencha as credenciais de acesso do seu Banco de Dados:**
  * `DB_HOST = ` 
  * `DB_USER = `
  * `DB_PASS = `
  * `DB_NAME = `
  * `PORT = 3306`
* **Acesse novamente o terminal**
  * **Inicie o projeto:** rode o comando
    
     ```
    npm start
     ``` 

---
## 🧑‍🚀Desenvolvedor

* Layla Janaína Hissa Borges

## 📝Sobre a Licença

Este projeto esta sobe a licença [MIT](https://github.com/future4code/Barros-labEcommerce-backend27/blob/main/LICENSE). git
