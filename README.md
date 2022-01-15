# pastebin-api

![License](https://img.shields.io/github/license/dev-caspertheghost/pastebin-api)
![Downloads](https://img.shields.io/npm/dw/pastebin-api)

A very simple npm package to interact with the pastebin api.

## Installation

### npm

```bash
npm i pastebin-api
```

### yarn

```bash
yarn add pastebin-api
```

## Usage

```js
import PasteClient from "pastebin-api";
// const PasteClient = require("pastebin-api").default; // using CommonJS

// Or (named imports)
import { PasteClient } from "pastebin-api";

const client = new PasteClient("DEV_KEY_HERE");

/* ... */
```

## Documentation

[You can checkout the documentation here](docs/README.md)

## Support

All stars/forks are appreciated! ⚡

Feel free to open a pull request with a new feature.

Made with ❤️ and TypeScript!

## License

[MIT © Dev-CasperTheGhost](./LICENSE)
