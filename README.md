# DOES NOT WORK WITH HYPER v2...YET. If you're interested in making this work with v2, let me know in a comment on https://github.com/Aaronius/hyper-cat/issues/11

Turn your [Hyper](https://hyper.is/) terminal into nyan cat while typing. Audio included!

![Screen Capture](capture.gif?raw=true "Screen Capture")

To install, edit `~/.hyper.js` and add `hyper-cat` to `plugins`:

```js
module.exports = {
  ...
  plugins: [
    "hyper-cat"
  ]
  ...
};
```

You may then need to reload your terminal.

## Configuration

Configuration can by applied by editing `~/.hyper.js` as follows:

```js
module.exports = {
  config: {
    ...
    hyperCat: {
      staggerHeight: 2, // The number of pixels the cat and rainbow should jump up and down.
      rainbowMaxAlpha: 1, // The max opacity of the rainbow.
      audioEnabled: true // Whether audio should play while typing.
    }
    ...
  }
}
```
