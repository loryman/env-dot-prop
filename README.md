# env-dot-prop
[![Travis CI](https://travis-ci.org/simonepri/env-dot-prop.svg?branch=master)](https://travis-ci.org/simonepri/env-dot-prop) [![Codecov](https://img.shields.io/codecov/c/github/simonepri/env-dot-prop/master.svg)](https://codecov.io/gh/simonepri/env-dot-prop) [![npm](https://img.shields.io/npm/dm/env-dot-prop.svg)](https://www.npmjs.com/package/env-dot-prop) [![npm version](https://img.shields.io/npm/v/env-dot-prop.svg)](https://www.npmjs.com/package/env-dot-prop) [![npm dependencies](https://david-dm.org/simonepri/env-dot-prop.svg)](https://david-dm.org/simonepri/env-dot-prop) [![npm dev dependencies](https://david-dm.org/simonepri/env-dot-prop/dev-status.svg)](https://david-dm.org/simonepri/env-dot-prop#info=devDependencies)
> ♻️ Get, set, or delete nested properties of process.env using a dot path


## Install

```
$ npm install --save env-dot-prop
```

## Usage

```js
```

## API

### get(path, [defaultValue])

Returns the values of env keys at the path specified.

#### path

Type: `string`

Dot separated path.

#### defaultValue

Type: `any`

Default value to return if there aren't keys in the path provided

### set(path, value)

Returns the values of env keys at the path specified.

#### path

Type: `string`

Dot separated path.

#### value

Type: `any`

Value to set.

### del(path)

Deletes an env key at the path specified. If nested keys are present they will be deleted too.

#### path

Type: `string`

Dot separated path.

### has(path)

Returns whether an env key exists at the path specified.

#### path

Type: `string`

Dot separated path.


## Authors
* **Simone Primarosa** - [simonepri](https://github.com/simonepri)

See also the list of [contributors](https://github.com/simonepri/env-dot-prop/contributors) who participated in this project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
