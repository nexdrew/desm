# desm

The missing one-liner utility to get the dirname from `import.meta.url`.

Requires Node 12.17.0 or Node 14.0.0.

## Install

```
npm i desm
```

## Usage

```js
import desm from 'desm'

console.log(desm(import.meta.url))
```

or

```js
import { dirname, join } from './index.js'

console.log(dirname(import.meta.url))
console.log(join(import.meta.url, 'routes'))
```

## License

MIT
