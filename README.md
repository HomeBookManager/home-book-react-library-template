# home-book-react-library-template

Home Book React Library Template is prepared library template to create set of components for react version >= 17.

## Table of Contents

- [Installation](#Installation)
- [Launch](#Launch)
- [Public-NPM](#Public-NPM)
- [Instruction](#InstructionM)
- [Libraries](#Libraries)

## Installation

```
npm install or npm i
```

## Launch

```
npm start
```

## Public NPM

Before publish you have to bump up package.json version & change description in README.md which is use in npm as description. Last thing wchich you have to do is change name with prefix home-book-{name}.

```
npm run build:publish
```

## Instruction

Before commit are call actions:

- branch name lint
- style lint
- eslint ts
- eslint tsx
- prettier
- unit test
- commit syntax

If you need skip tests, after the commit message you have to put command:

```
git commit -m "<message>" --no-verify
```

## Libraries

- react - https://pl.reactjs.org/docs/getting-started.html
- sass - https://sass-lang.com/
- lodash - https://lodash.com/docs/4.17.15
- enzyme - https://enzymejs.github.io/enzyme/
- prettier - https://prettier.io/
- eslint - https://eslint.org/
- husky - https://github.com/typicode/husky
- rollup.js - https://rollupjs.org/guide/en/
- storybook - https://storybook.js.org/
- commit-lint - https://commitlint.js.org/#/
- branch-lint - https://github.com/barzik/branch-name-lint
- style-lint - https://stylelint.io/
