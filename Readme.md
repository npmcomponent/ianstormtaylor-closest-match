*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/closest-match](http://github.com/ianstormtaylor/closest-match). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-closest-match`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# closest-match

  Find the closest match for a string from an array of matches, using string distance.

## Installation

    $ component install ianstormtaylor/closest-match

## Example
    
```js
var closest = require('closest-match');
var animals = ['dog', 'cat', 'bird'];

closest('dag', animals); // 'dog'
```

## API

### closest(string, matches)
  Match the given `string` against an array of possible `matches`.

### closest.threshold
  Change the string distance `threshold` used to match. Default is `3`.

### closest.distance
  Change the distancing method. Default is the [`timoxley/sift`](https://github.com/timoxley/sift) component.

## License

  MIT
