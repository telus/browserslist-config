# TELUS Shared Browserslist Config

[![version][npm-image]][npm-url] [![Build Status][circle-image]][circle-url]

## What is browserslist?

> "Share target browsers between different front-end tools, like Autoprefixer, Stylelint and babel-preset-env"

See [browserslist](https://github.com/browserslist/browserslist).

## Install

```sh
npm install @telusdigital/browserslist-config --save-dev
```

## Set up

Create a `browserslist` file in the root of your project.
Add the following line to extend from this config:

```config
extends @telusdigital/browserslist-config
```

You can also add your own queries after the `extends`, though this is not recommended.

## Which browsers do I support?

You can use the `browserslist` CLI to inspect the browsers targeted by the queries in your `browserslist` config.

```bash
npx browserslist              # Output a list of targeted browsers
npx browserslist --coverage   # Total coverage of targeted browsers
```

For local development, also run:
```bash
npm run setup-local
```

---
> Github: [@telus](https://github.com/telus) &bull; 
> Twitter: [@telusdigital](https://twitter.com/telusdigital)

[circle-url]: https://circleci.com/gh/telus/browserslist-config
[circle-image]: https://img.shields.io/circleci/project/github/telus/browserslist-config/master.svg?style=for-the-badge&logo=circleci

[npm-url]: https://www.npmjs.com/package/@telus/browserslist-config
[npm-image]: https://img.shields.io/npm/v/@telus/browserslist-config.svg?style=for-the-badge&logo=npm
