*This repository is a mirror of the [component](http://component.io) module [component/jpeg-size](http://github.com/component/jpeg-size). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-jpeg-size`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# jpeg-size

  Read JPEG image dimensions from a File or Blob

## Installation

    $ component install component/jpeg-size

## Example

```js
var size = require('jpeg-size');
var s = size(buf);
// => { width: 200, height: 400 }
```

## License

  MIT
