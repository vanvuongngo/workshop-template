# How to setup slide github action with reveals.js

## Requisites

- pnpm package manager

```sh
npm i -g pnpm
```

## Installation

see basic setup: https://revealjs.com/installation/#basic-setup

or

see full setup:https://revealjs.com/installation/#full-setup

## Get started

```sh
cd doc
```

- Clone reveal.js template
```sh
pnpx degit https://github.com/hakimel/reveal.js.git
```

- Install node packages
```sh
pnpm install
```

- Serve the presentation
```sh
pnpm start
```

- Open http://localhost:8000 to view your presentation
