# react-offline-cache
#### Create a cache to offline connection
A basic cache for React applications. Offline cache to applications. It also serves as a reference for more advanced caching implementations.

<!-- `WARNING: Do not use the development server in a production environment.` -->

## Install [<img src="https://github.com/natancabral/react-offline-cache/blob/main/images/npm-tile.png">](https://www.npmjs.com/package/react-offline-cache)

```shell
npm install react-offline-cache
```

## src/index.js

```js
import React from "react";
import ReactDOM from "react-dom";
import App from "./App";
// react-offline-cache
import * as roc from 'react-offline-cache';

ReactDOM.render(<App />, document.getElementById("root"));

// init faster
roc.register();
```

## How to remove

```js
roc.unregister();
```

## Is online

```js
console.log('online:', roc.isOnline());
```

## Is offline
```js
if(roc.isOffline()) {
  window.alert('Your internet is offline. Sorry.');
}
```

## License

The MIT License.

## Author

<table>
  <tr>
    <td>
      <img src="https://github.com/natancabral.png?s=100" width="100"/>
    </td>
    <td>
      Natan Cabral<br />
      <a href="mailto:natancabral@hotmail.com">natancabral@hotmail.com</a><br />
      <a href="https://github.com/natancabral/">https://github.com/natancabral/</a>
    </td>
  </tr>
</table>

## Thank you