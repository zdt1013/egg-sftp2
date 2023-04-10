# egg-sftp

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/egg-sftp.svg?style=flat-square
[npm-url]: https://npmjs.org/package/egg-sftp
[travis-image]: https://img.shields.io/travis/zdt1013/egg-sftp.svg?style=flat-square
[travis-url]: https://travis-ci.org/zdt1013/egg-sftp
[codecov-image]: https://img.shields.io/codecov/c/github/zdt1013/egg-sftp.svg?style=flat-square
[codecov-url]: https://codecov.io/github/zdt1013/egg-sftp?branch=master
[david-image]: https://img.shields.io/david/zdt1013/egg-sftp.svg?style=flat-square
[david-url]: https://david-dm.org/zdt1013/egg-sftp
[snyk-image]: https://snyk.io/test/npm/egg-sftp/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/egg-sftp
[download-image]: https://img.shields.io/npm/dm/egg-sftp.svg?style=flat-square
[download-url]: https://npmjs.org/package/egg-sftp

<!--
Description here.
-->

## Install

```bash
$ npm i egg-sftp --save
```

## Usage

```js
// {app_root}/config/plugin.js
exports.sftp = {
  enable: true,
  package: 'egg-sftp',
};
```

## Configuration

```js
// {app_root}/config/config.default.js
exports.sftp = {
};
```

see [config/config.default.js](config/config.default.js) for more detail.

## Example

<!-- example here -->

## Questions & Suggestions

Please open an issue [here](https://github.com/zdt1013/egg-sftp/issues).

## Thanks
[ssh2-sftp-client](https://github.com/theophilusx/ssh2-sftp-client)

## License

[MIT](LICENSE)
