# metarouter

A Node.js client for [Metarouter](https://metarouter.io) — The hassle-free way to integrate analytics into any application.


Based off of [Astronomer](https://astronomer.io) and [Segment's](https://segment.com) `analytics-node`



## Installation

```bash
$ npm install metarouter
```


## Usage

```js
import Analytics from 'metarouter';

const client = new Analytics('<METAROUTER_KEY>');

client.track({
  event: 'event name',
  userId: 'user id'
});
```


## Documentation

Documentation is available at [https://docs.metarouter.io/v2/clickstream/sources/nodejs.html](https://docs.metarouter.io/v2/clickstream/sources/nodejs.html).


## License

Copyright &copy; 2017 Segment Inc. \<friends@segment.com\>
