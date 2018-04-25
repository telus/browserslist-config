# browserslist-config

![npm](https://img.shields.io/npm/v/@telusdigital/browserslist-config.svg?style=flat-square)
![Travis](https://img.shields.io/travis/telusdigital/browserslist-config.svg?style=flat-square)

## What is browserslist?

> "Share target browsers between different front-end tools, like Autoprefixer, Stylelint and babel-preset-env"

See https://github.com/browserslist/browserslist

## Install

```
yarn add @telusdigital/browserslist-config --dev
```

## Set up

Create a `browserslist` file in the root of your project.
Add the following line to extend from this config:

```
extends @telusdigital/browserslist-config
```

You can also add your own queries after the `extends`, though this is not recommended.

## Which browsers do I support?

You can use the `browserslist` CLI to inspect the browsers targeted by the queries in your `browserslist` config.

```bash
npx browserslist              # Ouput a list of targeted browsers
npx browserslist --coverage   # Total coverage of targeted browsers
```
