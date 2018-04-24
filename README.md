# browserslist-config

## What is browserslist?

> "Share target browsers between different front-end tools, like Autoprefixer, Stylelint and babel-preset-env"

See https://github.com/browserslist/browserslist

## Install

(Not available as an npm package yet)

## Set up

Create a `browserslist` file in the root of your project.
Add the following line to extend from this config:

```
extends @telusdigital/browserslist-config
```

You can also add your own queries after the `extends`, though this is not recommended.

## Which browsers do I support?

You can use the `browserslist` CLI to find out the browsers targeted by the queries in your `browserslist` config.

```bash
npx browserslist              # Ouput a list of targeted browsers
npx browserslist --coverage   # Total coverage of targeted browsers
```
