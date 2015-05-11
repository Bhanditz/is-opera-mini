# is-opera-mini

Detect Opera Mini versions with limited JavaScript support using the official method [documented on Opera’s blog](https://dev.opera.com/articles/view/opera-mini-and-javascript/#detectingmini).

## Usage

```js
var isOperaMini = require('is-opera-mini');
```

It returns `true` for Opera Mini versions that are rendered on Operas Server having limited JavaScript support and return `false` for all other browsers and node as well as Opera Mini versions that have full JS support, e.g. Opera Mini set to “turbo” on iOS.
