# concat-files

## example

```js
  var concat = require('concat-files');

  concat([
    '/my/first/file',
    '/another/file',
    '/one/last/file'
  ], '/to/destination', function() {
    console.log('done');
  });
```

## tests

```shell
npm test
```

## benchmarks

```shell
node bench
```

## license

MIT