gestalt-cli
-----------

[![npm version](https://badge.fury.io/js/gestalt-cli.svg)](https://badge.fury.io/js/gestalt-cli)

Gestalt CLI includes the command line tools for using Gestalt:

`npm install -g gestalt-cli`

and then

- `gestalt init {name}` - scaffolds a new project
- `gestalt migrate`
  - updates `schema.json` from `schema.graphql`
  - generates and runs database schema migrations based on changes to your
    `schema.graphql` file.
