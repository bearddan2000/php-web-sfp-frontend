# php-web-sfp-frontend

## Project purpose
Creates a web application to view movies.

## Project technologies
- APIs
  - The Movie DB
  - Youtube
- nodejs
- vuejs
  - axios
  - babel
  - jest
  - pug
  - router
  - scss
  - slots
  - vuex

## To run
### To start
```sudo ./install.sh -u```
accessible through localhost:8080

### To stop
```sudo ./install.sh -d```

## Project setup
This is used to make ajax calls

```npm i axios```
This is to fix IE problem with promises

```npm i es6-promise```
This enables pug as a template lang

Example template lang="pug"

```npm i pug pug-plain-loader```
This enables scss for style tags

Example style lang="scss"

scss files are found `src/assets/scss`

```npm i sass-loader node-sass```
This enables unit test

```npm i jest```
This enables unit test for vue components

```npm i vue-jest bable-jest```
This enables `mount` command for unit tests

```npm i @vue/cli-plugin-unit-jest @vue/test-utils```
A state management system basicaly a const variable

```npm i vuex```

### Compiles and hot-reloads for development
```npm run serve```

### Compiles and minifies for production
```npm run build```

### Lints and fixes files
```npm run lint```

### To run unit test
```npm run unit```
`unit` is an alias for `jest` this
can be change by doing a find for
`unit` in package.json


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
