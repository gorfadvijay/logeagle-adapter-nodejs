# Log EAGLE adapter for NodeJS

Adapter to monitor NodeJS web servers.

## Usage

Install the adapter with `npm i --save @logeagle/adapter-nodejs` or `yarn add @logeagle/adapter-nodejs`.

## Configuration

Require the adapter at the top of your server and pass the configuration to the `init` function.

```javascript
const logeagle = require("@logeagle/adapter-nodejs");

logeagle.init({ ticket: "2ATNP1AD70" });
```

## Documentation

Visit our [documentation](https://docs.logeagle.io/docs/nodejs-adapter) for more.
