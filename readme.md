# get-port [![Build Status](https://travis-ci.org/sindresorhus/get-port.svg?branch=master)](https://travis-ci.org/sindresorhus/get-port)

> Get an available port


## Install

```
$ npm install --save get-port
```


## Usage

```js
const getPort = require('get-port');

getPort((err, port) => {
	console.log(port);
	//=> 51402
});
```


## CLI

```
$ npm install --global get-port
```

```
$ get-port --help

  Example
    get-port
    51402
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
