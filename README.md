# fis-optimizer-html-minifier

A optimizer plugin for fis to compress html by using html-minifier.

### Installation

``` bash
$ npm install -g BelinChung/fis-optimizer-html-minifier
```

### Usage

``` javascript
fis.config.set('modules.optimizer.html', 'html-minifier');

fis.config.set('settings.optimizer.html', {
    removeComments: true,
    removeCommentsFromCDATA: true
});
```

更多可选配置，参考 [html-minifier](https://github.com/kangax/html-minifier)
