### dragula
---
https://github.com/bevacqua/dragula
https://github.com/bevacqua/dragula/

```js
// test/cancel.js

var test = require('tape');
var dragula = require('..');

test('cancel does not throw when not dragging', function (t) {
  t.test('a single time', function once (st) {
    var drake = dragula();
    st.doesNotThrow(function () {
      drake.cancel();
    }, 'dragula ignores a single call to drake.cancel');
    st.end();
  });
  t.test('multiple times', function once (st) {
    var drake = dragula();
    st.doesNotThrow(function () {
      drake.cancel();
      
    });
  });
});

```

```
```

```
```


