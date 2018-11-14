----  仿 webpack-template

# vue-webpack-boilerplate

> A full-featured Webpack setup with hot-reload, lint-on-save, unit testing & css extraction.

> This template is Vue 2.0 compatible. For Vue 1.x use this command: `vue init webpack#1.0 my-project`


# Vue-cli 3 is here, so this template is now considered deprecated.

This template was the main template for vue-cli verison 2.*.

Now that we have released a [stable version of vue-cli 3](https://cli.vuejs.org), which incorporates all features that this template offers (and much more), we think that this template doesn't have any significant use for the future, so we won't put much resource in developing it further.

We will try and fix major issues should they arise, but not much more.

Feel free to fork this template if you want to keep it alive.

## Documentation

- [For this template](http://vuejs-templates.github.io/webpack): common questions specific to this template are answered and each part is described in greater detail
- [For Vue 2.0](http://vuejs.org/guide/): general information about how to work with Vue, not specific to this template

## Usage

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli). **It is recommended to use npm 3+ for a more efficient dependency tree.**

``` bash
$ npm install -g vue-cli
$ vue init zhangyh007/vue-webpack-template my-project
$ cd my-project
$ npm install
$ npm run dev
```
## What's Included
启动项目：8080端口
- npm run dev

- `npm run build`: Production ready build.
  - JavaScript minified with [UglifyJS v3](https://github.com/mishoo/UglifyJS2/tree/harmony).
  - HTML minified with [html-minifier](https://github.com/kangax/html-minifier).
  - CSS across all components extracted into a single file and minified with [cssnano](https://github.com/ben-eb/cssnano).
  - Static assets compiled with version hashes for efficient long-term caching, and an auto-generated production `index.html` with proper URLs to these generated assets.
  - Use `npm run build --report`to build with bundle size analytics.

### Fork It And Make Your Own

You can fork this repo to create your own boilerplate, and use it with `vue-cli`:

``` bash
vue init username/repo my-project
```
