# astronomer [![CircleCI](https://circleci.com/gh/segmentio/analytics-node.svg?style=svg&circle-token=68654e8cd0fcd16b1f3ae9943a1d8e20e36ae6c5)](https://circleci.com/gh/segmentio/analytics-node)

A Node.js client for [Astronomer](https://astronomer.io) — The hassle-free way to integrate analytics into any application.

Based off of [Segment's](https://segment.com) `analytics-node`



## Installation

```bash
$ npm install astronomer
```


## Usage

```js
const Analytics = require('astronomer');

const client = new Analytics('write key');

client.track({
  event: 'event name',
  userId: 'user id'
});
```


## Documentation

Documentation is available at [https://docs.astronomer.io/v2/clickstream/sources/nodejs.html](https://docs.astronomer.io/v2/clickstream/sources/nodejs.html).


## License

Copyright &copy; 2017 Segment Inc. \<friends@segment.com\>
