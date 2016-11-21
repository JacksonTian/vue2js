.vue to .js
=================

A tool for Compile `.vue` file to `.js` file.

The `.vue` means use [.vue Spec file](https://vue-loader.vuejs.org/en/start/spec.html).

> `*.vue` file consists of three types of top-level language blocks: `<template>`, `<script>` and `<style>`.

## Install

```sh
$ npm i vue2js -g
```

## Usage

You can use it as command line tool or scripting with it.

### Shell

```sh
$ vue2js
Usage: vue2js <filename>
```

### Scripting

```
const vue2js = require('vue2js');

var content = fs.readFileSync('*.vue', 'utf8');
console.log(vue2js(content));
```

## License

The MIT license
