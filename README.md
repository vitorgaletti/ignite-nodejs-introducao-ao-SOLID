# Desafio 01 - Introdução ao SOLID

## :computer: Sobre o desafio

<hr>

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no Node.js!

Essa será uma aplicação de listagem e cadastro de usuários. Para que a listagem de usuários funcione, o usuário que solicita a listagem deve ser um admin (mais detalhes ao longo da descrição).

## Rotas da aplicação

### POST `/users`

A rota deve receber `name`, e `email` dentro do corpo da requisição para que seja possível cadastrar um usuário.

### PATCH `/users/:user_id/admin`

A rota deve receber, nos parâmetros da rota, o `id` de um usuário e transformar esse usuário em admin.

### GET `/users/:user_id`

A rota deve receber, nos parâmetros da rota, o `id` de um usuário e devolver as informações do usuário encontrado pelo corpo da resposta.

### GET `/users`

A rota deve receber, pelo header da requisição, uma propriedade `user_id` contendo o `id` do usuário e retornar uma lista com todos os usuários cadastrados. O `id` deverá ser usado para validar se o usuário que está solicitando a listagem é um admin. O retorno da lista deve ser feito apenas se o usuário for admin.

## :rocket: Techs

<ul>
  <li> Javascript </li>
  <li> Typescript </li>
  <li> Node.js </li>
  <li> Express </li>
  <li> uuid </li>
  <li> Swagger </li>
</ul>

## Desenvolvimento

---

### Pré-requisitos

- Instalar [Node.js](https://nodejs.org)

- Instalar [Yarn](https://yarnpkg.com/)

### Clone o repositório

```bash
$ git clone https://github.com/vitorgaletti/ignite-nodejs-introducao-ao-SOLID.git
```

### Executar Projeto

```bash
# Mudar para directório
$ cd ignite-nodejs-introducao-ao-SOLID/
```

- Instalar dependências

```bash
$ yarn install
```

- Execute

```bash
$ yarn run dev
```

- Executar scripts

|        Ação        |   Utilização   |
| :----------------: | :------------: |
| Iniciar o servidor | `yarn run dev` |
|  Executar testes   |  `yarn test`   |

URL da API = http://localhost:3333

<br>

## API Documentation

Acesse `http://localhost:3333/api-docs` para ter acesso a documentação da API.

## Autor

- [@vitorgaletti](https://github.com/vitorgaletti)
