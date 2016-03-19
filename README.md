# wowza-cloud (work in progress)

[![Wercker][wercker-image]][wercker-url]
[![NPM version][npm-image]][npm-url]
[![NPM downloads][npm-downloads]][npm-url]
[![MIT License][license-image]][license-url]

NodeJS module for interacting with Wowza Streaming Cloud.

## Usage

There's a NPM package available:

```npm install --save wowza-cloud```

## Development

The module uses Babel. You may test the source using [mocha](https://mochajs.org/):

```npm test```

The above will compile the JS & run [mocha](https://mochajs.org/) with the [options in the file](https://github.com/matiasinsaurralde/wowza-cloud/blob/master/test/mocha.opts).

## API Documentation

I found the API documentation [here](https://sandbox.cloud.wowza.com/apidocs/v1/).

## TODO

## License

[MIT][license-url]

[wercker-image]: https://app.wercker.com/status/dcca84bf62ec57f136f3a1eb40de8143/s/master
[wercker-url]: https://app.wercker.com/project/bykey/dcca84bf62ec57f136f3a1eb40de8143
[npm-image]: http://img.shields.io/npm/v/wowza-cloud.svg?style=flat
[npm-url]: https://npmjs.org/package/wowza-cloud
[npm-downloads]: http://img.shields.io/npm/dm/wowza-cloud.svg?style=flat
[license-url]: LICENSE
[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
