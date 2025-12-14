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
cd docs
```

- Clone the latest reveal.js template
```sh
pnpx degit https://github.com/hakimel/reveal.js.git
```

- Install node packages
```sh
pnpm install
```

- Serve the presentation to test that it is running locally
```sh
pnpm start
```

- Open http://localhost:8000 to view your presentation

- `Ctrl+C` to close the node app

- append not needed directories from reveals to the `docs/.gitignore`

```
examples/
```

## Setup github pages

- go to `Settings`

- choose <a href="settings/pages">Pages</a>

Build and deployment | `Deploy from branch`

Branch | `main` and folder `/docs`

Click `Save`

That is it. A github action will be triggered initially and on all git pushes.

Ope your own deployed github page https://USER.github.io/YOUR-PROJECT/

`USER` is your github user account

`YOUR-PROJECT` is your github repository
