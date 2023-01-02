# Development

Thank you very much for trying to improve our design system! To get you up on
lightning speed with your contribution, here are some requirements that are
needed for getting started.

## TLDR;

1. install [Node.js](https://nodejs.org/en/)
1. start coding 🚀

## Create a local development setup

### Install Node.js

To start contributing you need [Node.js](https://nodejs.org/en/) installed on
your machine. For macOS users, we recommend doing that with
[nvm](https://github.com/nvm-sh/nvm) a node version manager. While Windows users
should go with the LTS version of Node.js.

**npm** (Node Package Manager) is shipped with Node.js.

### Building

```
chmod ug+x .husky/\*
yarn install
yarn build
```

## Repository structure

The Barista repository has the following structure:

- **src**:
  - **components**: test app to run UI/e2e tests.
- **docs**: additional documentation files.
- **libs**:
  - **components**: the Barista components library source code. There's
    a separate library for each component.
  - **shared**: various shared libraries.

## Developing

Start it using one of the following commands

```
yarn install && yarn run dev
```

## Tests and stylelint

Preferrably, let the CI run all of the checks for consistency. If you really
need to run these locally make sure if it needs to be run yarn.

### Runs test files:

`yarn run test`

### UI Tests

`yarn run e2e`

### Lint

`yarn run lint`
