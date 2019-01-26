### themer
---
https://github.com/mjswensen/themer

```
npm installer themer
npm install themer themer-colors-default themer-vim themer-wallpaper-block-wave
npm run build
```

```js
module.exports.colors = {
  dark: {
    accent0: '#FF4050',
    shade0: '#282629',
  },
  light: { ... },
};

module.exports.render = function(colors, options){
};
```

```
"scripts": {
  "build": "themer -c themer-colors-default -t themer-vim -t themer-wallpaper-block-wave - o gen"
},

```


