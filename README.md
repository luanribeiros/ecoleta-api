![Logomarca Ecoleta](https://raw.githubusercontent.com/luanribeiros/ecoleta/master/src/assets/images/logo.svg?token=ADYW574VQY7MBPOGQYWRABS64ZQAS)

[![Build Status](https://img.shields.io/travis/npm/npm/latest.svg?style=flat-square)](https://travis-ci.org/npm/npm) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/your/your-project/blob/master/LICENSE)

### O **Ecoleta** é uma aplicação Web e Mobile para ajudar pessoas a encontrarem pontos de coleta para reciclagem.

Essa aplicação foi construída na trilha **Booster** da **Next Level Week** distribuída pela **[Rocketseat](https://rocketseat.com.br/)** :rocket: . A ideia de criar uma aplicação voltada ao meio ambiente surgiu da coincidência da data do curso e a data da semana do meio ambiente.

Recicle! O meio ambiente agradece! ♻️

> Encontre a front desta aplicação [aqui]() e o mobile [aqui]()

## Installing / Getting started

Tecnologias utilizadas:

- Node.js
- Knex
- Database sqlite
- Yup
- Celebrate
- Api IBGE

## Dependencies:

- Node.js `>=` v12.16.1;

## Up and running

- Clone this repository: `git clone git@github.com:luanribeiros/ecoleta.git`;
- Remove `.git` directory;
- Install dependencies: `yarn` (or `npm install`);
- Run yarn `(or`npm start`) to develop on`http://localhost:3000`
- Run `yarn build` (or `npm run build`) for production build (files will be generated on `build-prod` directory)

## Api Reference

[Api IBGE](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1#api-_)

- Municípios por UF: https://servicodados.ibge.gov.br/api/v1/localidades/estados/{UF}/municipios

- UFs: https://servicodados.ibge.gov.br/api/docs/localidades?versao=1#api-UFs-estadosGet

## Database

Consumindo [api]() com o database sqlite

## License

[MIT](https://github.com/luanribeiros/ecoleta/blob/master/LICENSE.md) &copy; Luan Ribeiro
