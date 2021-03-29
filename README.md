## Pegjs Transformer for Jest.

Simple module to compile [pegjs](https://pegjs.org/) files for Jest testing.


#### Installation

```
$ npm i -D pegjs-jest
```

or

```
$ yarn add --dev pegjs-jest
```


#### Jest configuration

Under transform object, and a mapper to the transformer. Below is an example of mapping `pegjs` files.

```JSON
  "transform": {
    "^.+\\.pegjs?$": "pegjs-jest"
  }
```
