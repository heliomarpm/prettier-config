
# Personal Prettier Configuration

This is my personal configuration for the [Prettier](https://prettier.io) code formatter.

## Installation

```sh 
yarn add --dev @heliomarpm/prettier-config

# or 

npm i --D @heliomarpm/prettier-config

```


## Usage

Add the following keys to your `package.json` file:

```js
{
  // ...
  "scripts": {
    "format": "prettier --write '**/*.{css,html,js,json,jsx,less,md,scss,ts,tsx,vue,yaml,yml}'"
  },
  "prettier": "@heliomarpm/prettier-config"
}
```

You can now run `yarn format` or `npm run format` to format your code.
