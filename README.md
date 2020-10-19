# Next.js + Preact + TypeScript

Another Next.js Preact boilerplate but TypeScript is included.

## Installation
There are 2 options available:
1. Click "Use this template" on GitHub
2. Clone this repository:
```sh
git clone https://github.com/wit03/Next-Preact-TypeScript.git
cd Next-Preact-TypeScript
yarn
```

## Running 
```sh
# start a development server:
yarn dev

# create a production build:
yarn build

# start a production server:
yarn start
```

## Few more included options
- [TSLint](https://github.com/palantir/tslint) and [Prettier](https://prettier.io/) are included.
- Images can be easily optimized by changing this:
```js
//...
module.exports = withPlugins([
  [optimizedImages, {
    handleImages: ['jpeg', 'png', 'webp'],
    optimizeImages: false, //Change from  false to true
    optimizeImagesInDev: true
  }]],
  withPrefresh(config));
```
