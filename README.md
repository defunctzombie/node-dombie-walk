# dombie-walk

recursively walk a [dombie](https://github.com/shtylman/node-dombie) dom tree and call a function for each node

```javascript
var dombie = require('dombie');
var walk = require('dombie-walk');

dombie(src, function(err, dom) {

    walk(dom, function(node) {
        // called for each node
    });
});
```
