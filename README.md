## Installation

### Node

```bash
npm install web3
```

### Yarn

```bash
yarn add web3
```

### In the Browser

Use the prebuilt `dist/web3.min.js`, or
build using the [web3.js][repo] repository:

```bash
npm run build
```

Then include `dist/web3.min.js` in your html file.
This will expose `Web3` on the window object.

Or via jsDelivr CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/web3@latest/dist/web3.min.js"></script>
```

UNPKG:

```html
<script src="https://unpkg.com/web3@latest/dist/web3.min.js"></script>
```

### Building (webpack)

Build the web3.js package:

```bash
npm run build
```

### Testing (mocha)

```bash
npm test
```