# prettier-config
Prettier config used at [www.woda.at](https://www.woda.at)

## Usage

Install the package using `npm` (or `yarn`)

```sh
npm install --save-dev @wwwoda/prettier-config
```

Add the `prettier` key to your `package.json`

```diff
{
    ...
    "keywords": [
        "prettier"
    ],
+   "prettier": "@github/prettier-config",
    "license": "MIT",
    "author": {
        "name": "Woda",
        "email": "hello@woda.at",
        "homepage": "https://www.woda.at"
    },
    "main": "index.js"
    ...
}
```

[Check out the `prettier` documentation for more info on sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations).