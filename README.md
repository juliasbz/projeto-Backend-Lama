# projeto-Backend-Lama

## 💻 Sobre o projeto

Labenu Music Awards é um show anual de músicas que conta com a participação de bandas super famosas nacionais e internacionais! Ele sempre acontece durante uma semana inteira, começando na manhã de segunda e encerrando na noite de domingo.

O LAMA (Labenu Music Awards) está previsto para acontecer no fim do ano e ainda não existe um back-end construído para gerenciar os eventos e ingressos do festival.

Para gerenciar o evento é necessário organizar e centralizar as informações dos shows em um servidor, que então disponibiliza os dados para o website no front-end. Além de controlar os eventos com suas bandas e datas do show, a aplicação também deve gerenciar os ingressos de cada show. A arena tem uma capacidade máxima de 5000 pessoas, portanto deve ser respeitado um limite máximo de ingressos por show.

---

## ⚙️ Funcionalidades

### Endpoint signup

Endpoint para cadastrar o usuário através da inserção dos dados nome, e-mail e senha.

### Endpoint login

Endpoint para logar o usuário já cadastrado no sistema através da inserção do e-mail e da senha.

### Endpoint createShow 

Endpoint para criar show através da inserção dos dados nome e tag. Somente admins podem utilizá-lo.

### Endpoint getShows

Endpoint para listar todos os shows já cadastrados no sistema.

### Endpoint buyTicket

Endpoint para criar reserva de ingresso.

### Endpoint deleteTicket

Endpoint para deletar uma reserva de ingresso. A pessoa só pode deletar suas próprias reservas.

---

## 🚀 Como executar o projeto

```bash
# Criar arquivo .env e adicionar os dados do seu banco de dados

PORT = 3003
DB_HOST = 
DB_USER = ""
DB_PASSWORD = ""
DB_DATABASE = ""

JWT_KEY = ""
JWT_EXPIRES_IN = ""

BCRYPT_SALT_ROUNDS = 12

# Instalar as dependências
$ npm install

# Inserir as tabelas no banco de dados
$ npm run migrations

# Executar a aplicação em modo de desenvolvimento
$ npm run start

# Executar testes
$ npm run test

```
---

## 🛠 Tecnologias Utilizadas

TypeScript

Node

Express

MySQL

Jest

---

## 🛠 API



---

## 🛠 Deploy



---

## Autor do Projeto

Labenu
