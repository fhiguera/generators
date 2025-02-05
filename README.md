# Rest/GraphQL APIs + React Components Generator 🔥

[![Follow on Twitter](https://img.shields.io/twitter/follow/andrewpierno.svg?label=follow)](https://twitter.com/andrewpierno)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/sugarkubes/generators.svg)](http://isitmaintained.com/project/sugarkubes/generators "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/sugarkubes/generators.svg)](http://isitmaintained.com/project/sugarkubes/generators "Percentage of issues still open")
[![npm package](https://img.shields.io/npm/v/sugar-generate/latest.svg)](https://www.npmjs.com/package/sugar-generate)
[![NPM Downloads](https://img.shields.io/npm/dt/sugar-generate.svg?style=flat)](https://npmcharts.com/compare/sugar-generate?minimal=true)


![Sugar Generator - API Edition](https://github.com/sugarkubes/generators/blob/master/logo.png?raw=true)

[![App Demo](https://img.youtube.com/vi/E7_ABK7nZT8/0.jpg)](https://www.youtube.com/watch?v=E7_ABK7nZT8)

# Quick Start


1. Install the npm module

```sh
# install
npm i -g sugar-generate
```

2. Create a json schema save, this to **monkey.json**


```json
{
  "schema": {
    "name": {
      "type": "String",
      "default": ""
    },
    "alive": {
      "type": "Boolean",
      "default": false
    },
    "age": {
      "type": "Number",
      "default": false
    }
  }
}
```

3. Generate your api and app

```sh
sugar-generate \
--schema monkey.json \
--destination ./my-monkeys
```

Boom, you now have:

API:
- GraphQL API
- REST API
- Working Tests

APP:
- React create item form
- React table that supports
  - search
  - sort
  - filter
  - pagination
  - edit item
  - create item


### Start the API

```sh
cd ./my-monkeys/api
npm i
npm run start

# http://localhost:7777
```

### Start the APP

```sh
cd ./my-monkeys/app
npm i
npm run dev

# http://localhost:3000
```

### Behold Magic

A fully functioning react table and form with searching sorting filtering, editing, adding, global search, download, and refresh.

![SugarKubes Generated App](https://github.com/sugarkubes/generators/blob/master/table-component.png?raw=true)

# Links

[GraphQL is on localhost:7777/graphql](http://localhost:7777/graphql)

[Swagger is on localhost:7777](http://localhost:7777)

[APP is on localhost:3000](http://localhost:3000)

[API is on localhost:7777](http://localhost:3000)

# Documentation

[API Documentation (generated back end)](https://github.com/sugarkubes/generators/wiki/API)


[App Documentation (generated front end)](https://github.com/sugarkubes/generators/wiki/APP)
