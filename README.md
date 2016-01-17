# set-map

[![master branch build status][build-icon]][build-link]

Ensures that a given input can be used as a set.

## Example

```js
import SetMap from 'set-map';

const map = new SetMap();
map.set([3, 1, 4, 1, 5, 9], 'foobar');

console.log(map.get([1, 1, 3, 4, 5, 9])); // => "foobar"
```

## Installing

```sh
$ npm install --save j-/set-map
```

## Building

Will output to [dist/set-map.js](dist/set-map.js).

```sh
$ npm install && npm run build
```

## Testing

```sh
$ npm install && npm test
```

## License

[MIT license](LICENSE).

[build-icon]: https://travis-ci.org/j-/set-map.svg?branch=master
[build-link]: https://travis-ci.org/j-/set-map
