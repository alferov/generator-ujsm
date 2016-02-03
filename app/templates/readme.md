# <%= moduleName %>
[![Build Status][travis-image]][travis-url]
[![Coveralls Status][coveralls-image]][coveralls-url]
[![Dependency Status][depstat-image]][depstat-url]

> Description

## Installation

```
$ npm install --save <%= moduleName %>
```

## Usage
```js
var <%= camelizedModuleName %> = require('<%= moduleName %>');
```

## API

### `<%= camelizedModuleName %>(data, [options])`
Description

#### Parameters
- **Array** `data`: An array of data
- **Object** `options`: An object containing the following fields:

#### Return
- **Array** - Result

## Development
- `npm run build` - Build task that generates both minified and non-minified scripts;
- `npm run test-server` - Run Mocha tests once;
- `npm run test-browser` - Run Mocha tests in the browser using Karma once;
- `npm run test` - Shortcut for `npm run test-server && npm run test-browser`;
- `npm run tdd` - Run Mocha tests & watch files for changes;
- `npm run tdd-browser` - Run Karma (w/ Mocha) tests & watch files for changes;
- `npm run coverage` - Run Isparta, a code coverage tool;

## License
MIT © [<%= name %>](http://github.com/<%= username %>)

[travis-url]: https://travis-ci.org/<%= username %>/<%= moduleName %>
[travis-image]: https://img.shields.io/travis/<%= username %>/<%= moduleName %>.svg?style=flat-square

[coveralls-url]: https://coveralls.io/r/<%= username %>/<%= moduleName %>
[coveralls-image]: https://img.shields.io/coveralls/<%= username %>/<%= moduleName %>.svg?style=flat-square

[depstat-url]: https://david-dm.org/<%= username %>/<%= moduleName %>
[depstat-image]: https://david-dm.org/<%= username %>/<%= moduleName %>.svg?style=flat-square
