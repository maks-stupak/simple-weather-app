# Simple weather app

[![Maintainability](https://api.codeclimate.com/v1/badges/9f5d9a6f9c1474a8da0b/maintainability)](https://codeclimate.com/github/maks-stupak/simple-weather-app/maintainability)
[![CI](https://github.com/maks-stupak/simple-weather-app/workflows/ci/badge.svg](https://github.com/maks-stupak/simple-weather-app/actions)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

Weather widget made with Angular

## Development

Prerequisites:

- Install [Node.js](https://nodejs.org/) which includes [Node Package Manager][https://www.npmjs.com/get-npm]
- Install [Angular CLI](https://angular.io/cli)
- Install [GIT](https://git-scm.com/) and clone this repository
- Run `npm install` or `yarn install` to install dependencies

### Run development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/` (the application will automatically reload if you change any of the source files).

### Code scaffolding

To generate a new component, directive, service, pipe, etc. You can use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

### Running tests, linters, prettier checker

- Run `npm run test` to execute the unit tests via [Karma](https://karma-runner.github.io).
- Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.
- Run `npm run test:ci:coverage` to get test coverage report.
- Run `npm run lint` to check code with [eslint](https://eslint.org/).
- Run `npm run lint:styles` to check styles with [stylelint](https://stylelint.io/).
- Run `npm run prettier:check` to check code formatting with [prettier](https://prettier.io/).

### Integrated

- [Husky 🐶](https://typicode.github.io/husky/) pre-commit hook with [lint-staged](https://github.com/okonet/lint-staged):

  - to check code formating,
  - to run eslint and stylelint,
  - to execute the unit tests.

- [Commitlint](https://commitlint.js.org/) on commit-msg hook to check if your commit messages meet the [conventional commit format](https://www.conventionalcommits.org/en/v1.0.0/).
