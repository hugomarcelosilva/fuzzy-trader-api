# Fuzzy Trader API

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=Fuzzy%20Trader&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fhugo-marcelo%2Ffuzzy-trader-api%2Fmaster%2FInsomnia.json)

## Deploy

- [https://fuzzy-trader-api.herokuapp.com/](https://fuzzy-trader-api.herokuapp.com/)

## 💼 Sobre o projeto

Requisitos:

Você está responsável por desenvolver uma ferramenta de apoio a decisão de investimento. Uma pessoa precisa não apenas acompanhar quanto custa seus investimentos (carteira) como precisa de apoio antes de fazê-lo.
Para isso queremos construir uma aplicação que permita ao usuário:

- Informar um valor (em dólar) que deseja aplicar.
- Com base neste valor, devemos apresentar um conjunto de ativos sugeridos (entre criptomoedas e ações) com informações de apoio a esta decisão.
- Então o usuário deve escolher qual ativo investirá o montante. Este fará parte da sua carteira.
- Deve-se então consolidar a sua carteira mostrando a quantidade total de cada ativo e o valor atual do mesmo (e a soma da carteira)
- Para a escolher dos ativos, pode-se usar um subconjunto limitado de criptomoedas e ações a sua escolha.

## ⚙️ Tecnologias

- [Node.js](https://nodejs.org/)
- [Knex](http://knexjs.org/)
- [Jest](https://jestjs.io/en/)

## 💻 Executando o projeto

**Clone o projeto e acesse a pasta**

```bash
$ git clone https://github.com/hugo-marcelo/fuzzy-trader-api && cd fuzzy-trader-api
```

1. Utilizando Npm

```sh
$ npm install
$ npm run test
$ npm dev
```

2. Utlizando yarn

```sh
$ yarn
$ yarn test
$ yarn dev
```

Made by Hugo Marcelo 👋 [Veja meu linkedin](https://www.linkedin.com/in/hugo-marcelo-dev/)
