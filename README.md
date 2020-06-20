<h1 align="center">
  <img src="https://camo.githubusercontent.com/d25397e9df01fe7882dcc1cbc96bdf052ffd7d0c/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67">

  Desafio 06: Banco de dados e upload de arquivos no Node.js
</h1>

# Indice
- [Sobre](#-sobre)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como baixar o projeto](#-como-baixar-o-projeto)

---

## 📖 Sobre

Desafio sobre a continuação da aplicação de gestão de transações, utilizando tudo que foi assimilado até agora no Node.js juntamente com o TypeScript, mas dessa vez utilizando banco de dados com o **TypeORM** e o envio de arquivos com o **Multer**.

Essa aplicação armazena transações financeiras de entrada e saída e permite o cadastro e a listagem dessas transações, além de permirit a criação de novos registros dentro do banco de dados através do envio de um arquivo csv.



---

## 🚀 Tecnologias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias

- [Express](https://expressjs.com/pt-br/)
- [Multer](https://www.npmjs.com/package/multer)
- [TypeScript](https://www.typescriptlang.org/)
- [jest](https://jestjs.io/)
- [TypeORM](https://typeorm.io/#/)

---

## 💻 Como baixar o projeto

```bash
  # Clonar repositório
  $ git clone https://github.com/diegoveigass/desafio-node-database-upload

  # Entrar no diretório
  $ cd desafio-node-database-upload

  # Instalar as dependências via yarn
  $ yarn

  # Instalar as dependências via npm
  $ npm install

  # Criar uma imagem postgres através do docker
  $ docker run --name ImageName -e POSTGRES_PASSWORD=mysecretpassword -p 5432:5432 -d postgres

  # Baixar postbird ou dbeaver para criação da database

  # Caso precise editar o nome da database no arquivo ormconfig.json e no './src/database/index.ts'

  # Rodar as migrations
  $ yarn typeorm migration:run

  # Iniciar o projeto
  $ yarn dev:server

  # Iniciar os testes
  $ yarn test
```

---

Desenvolvido por Diego Veiga 🚀 [Acesse meu LinkedIn](https://linkedin.com/in/diegoveigass)
