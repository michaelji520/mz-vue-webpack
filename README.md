My Personal Vue Template
========================

This is a Vue project

### Project Structure

```
project
|-- build: webpack config files
|   |-- webpack.base.js
|   |-- webpack.dev.js
|   |-- webpack.prod.js
|   └-- webpack.dll.js
|-- public
|   |-- index.html
|   └-- favicon.ico
|-- dll: pre-build dll modules, suggested in `development` mode
|-- src
|   |-- api: async request definitions
|   |-- assets: static file, eg. fonts, images, etc.
|   |-- common: global common files, eg. util, mixin, etc.
|   |-- components: universal components
|   |-- router: vue-router
|   |-- store: vuex
|   |-- views: page components
|   |-- main.js: global entry file
|   └-- App.vue: Vue instance
|-- .babellrc: babel config
|-- .browserslistrc: config for `browserslist`
|-- .gitignore: ignore files/directorys
|-- postcss.config.js
|-- package.json
|-- package-lock.json
└-- README.md
```

### Project setup

```
npm install
```

### Compiles and hot-reloads for development

If using dll, you need to run following command for the first time.

```
$ npm run dll
```

> NOTE: You need to run dll command again when dll modules change.

```
$ npm run dev
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```
