# laravel-elixir-requirejs

Simple extension to *laravel elixir* to build javascript bundle with *requirejs*.

## Install

```
npm install --save-dev laravel-elixir-requirejs
```

## Usage

### Example *Gulpfile*:

```javascript
var elixir = require('laravel-elixir');

require('laravel-elixir-requirejs');

elixir(function(mix) {
    mix.requirejs('app.js');
});
```

You can also use advanced options.

```javascript
mix.requirejs(src, options, output);
```


