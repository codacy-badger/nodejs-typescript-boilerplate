# Node.js TypeScript Boilerplate

Basic boilerplate for Node.js development with TypeScript, ESLint, Prettier, Airbnb styleguide, Mocha, Chai, istanbul, pino, tsc-watch

[<img alt="npm" src="https://img.shields.io/david/alphabit1/nodejs-typescript-eslint-prettier-airbnb-mocha-chai-istanbul-boilerplate.svg?style=flat-square">](https://david-dm.org/alphabit1/nodejs-typescript-eslint-prettier-airbnb-mocha-chai-istanbul-boilerplate)

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/a43ae59fef3a4d0789c9eaf26648e976)](https://www.codacy.com/manual/alphabit1/nodejs-typescript-eslint-prettier-airbnb-mocha-chai-istanbul-boilerplate?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=alphabit1/nodejs-typescript-eslint-prettier-airbnb-mocha-chai-istanbul-boilerplate&amp;utm_campaign=Badge_Grade)

[<img alt="MIT Licence" src="https://badges.frapsoft.com/os/mit/mit.svg?v=103">](https://opensource.org/licenses/mit-license.php)

This boilerplate includes the following features:

-   Logging with [pino](https://github.com/pinojs/pino)
-   Easy development with [tsc-watch](https://github.com/gilamran/tsc-watch#readme) and [pino-pretty](https://github.com/pinojs/pino-pretty)
-   Linting with [ESLint](https://eslint.org/).
-   Formatting with [Prettier](https://prettier.io/) and [Airbnb styleguide](https://github.com/airbnb/javascript).
-   Testing with Test Coverage using [Mocha](https://mochajs.org/), [Chai](https://www.chaijs.com/) and [istanbul](https://istanbul.js.org/)

## install

```zsh
git clone https://github.com/alphabit1/nodejs-typescript-eslint-prettier-airbnb-mocha-chai-istanbul-boilerplate <project-name>
cd <project-name>
rm -rf .git && git init     # remove git and initialize new git
npm i                       # install dependencies
```

## Commands

> Run

```zsh
npm run clean       # remove all generated
npm run build       # clean and build dist
npm run start       # start node
npm run dev         # tsc-watch and start with debugger
```

> Test

```zsh
# Test
npm run test                           # Run all test
# Test Coverage
npm run coverage                       # Calculate the coverage of all
# Test consistent coding style (Lint)
npm run lint                           # Lint all sourcecode
```
