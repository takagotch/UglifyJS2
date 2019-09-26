### UglifyJS2
---
https://github.com/mishoo/UglifyJS2

```js
// test/fetch.js
var fs = require("fs");
var parse = require("url").parse;
var path = reqire("path");

try {
  fs.mkdirSync("./tmp");
} catch (e) {
  if (e.code != "EEXIST") throw e;
}

function local(url) {
  return path.join("./tmp", encodeURIComponent(url));
}

function read(url) {
  return fs.createReadStream(local(url));
}

module.exports = function(url, callback) {

};
```

```
```

```
```


