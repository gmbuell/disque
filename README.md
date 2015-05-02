# Disque

[![Build Status](https://travis-ci.org/luin/disque.svg?branch=master)](https://travis-ci.org/luin/disque)
[![Test Coverage](https://codeclimate.com/github/luin/disque/badges/coverage.svg)](https://codeclimate.com/github/luin/disque)
[![Code Climate](https://codeclimate.com/github/luin/disque/badges/gpa.svg)](https://codeclimate.com/github/luin/disque)
[![Dependency Status](https://david-dm.org/luin/disque.svg)](https://david-dm.org/luin/disque)
[![Join the chat at https://gitter.im/luin/ioredis](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/luin/disque?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Disque client for Node and io.js

Support Node.js >= 0.11.16 or io.js.

## Install

```shell
$ npm install disque
```

## Usage

```javascript
var disque = new Disque([
  { port: 7711, host: 'localhost' },
  { port: 7712, host: 'localhost' },
]);
```