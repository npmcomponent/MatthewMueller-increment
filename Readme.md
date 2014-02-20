*This repository is a mirror of the [component](http://component.io) module [matthewmueller/increment](http://github.com/matthewmueller/increment). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/matthewmueller-increment`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# increment

  increment strings

## Example

```js
increment('user', '-') // user-1
increment('user-1', '-') // user-2
increment('user-999', '-') // user-1000
```

## Installation

    $ npm install increment

or in the browser...

    $ component install matthewmueller/increment

## API

### increment(str, [ prefix ])

Increment `str` by 1. Give an optional `prefix`.

## License

  MIT
