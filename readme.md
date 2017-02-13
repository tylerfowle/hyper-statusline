# Modified hyper-statusline 

removed git info since it causes git locks in large repos.  this is a stop gap until the offical gets fixed.

# hyper-statusline [![npm](https://img.shields.io/npm/v/hyper-statusline.svg?maxAge=86400?style=flat-square)](https://www.npmjs.com/package/hyper-statusline) [![npm](https://img.shields.io/npm/dt/hyper-statusline.svg?maxAge=86400?style=flat-square)](https://www.npmjs.com/package/hyper-statusline)

> Status Line Plugin for [Hyper](https://hyper.is). Shows clickable & useful information. Matches any theme.

![hyper-statusline](https://cloud.githubusercontent.com/assets/1430576/21891665/14d29070-d8d4-11e6-9e98-b12ed28be93a.png)


## Install

Add following to your `~/.hyper.js` config.

```javascript
module.exports = {
  ...
  plugins: ['hyper-statusline']
  ...
}
```


## Config

Add following to `~/.hyper.js`.

### Disable Footer Transparency
Default value is set to `true`

```javascript
module.exports = {
  config: {
    ...
      hyperStatusLine: {
        footerTransparent: false,
      }
    ...
  }
}
```

### Change Font Size
Default value is set to `12`

```javascript
module.exports = {
  config: {
    ...
      hyperStatusLine: {
        fontSize: 13,
      }
    ...
  }
}
```

### Change Font Family
Default value is set to `-apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif`

```javascript
module.exports = {
  config: {
    ...
      hyperStatusLine: {
        fontFamily: '"Fira Code"',
      }
    ...
  }
}
```


## Theme

* [hyper-chesterish](https://github.com/henrikdahl/hyper-chesterish)


## License

MIT © Henrik
