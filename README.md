# Ethereum Blockies Base64 in purse VanillaJS

A tiny vanillajs library for generating blocky identicons as base64 encoded PNGs.

![Sample of generated blockies](sample.png "Blockies")

[**See a live demo of it in action**](https://anoxxxy.github.io/ethereum-blockies-base64-vanillajs/)

## Use

### Include the files

```javascript
<script src="pnglib.js" ></script>
<script src="blockie.js" ></script>
```

### Vanilla JS
```
var img = new Image();
img.src = makeBlockie('0x7cB57B5A97eAbe94205C07890BE4c1aD31E486A8');

document.body.appendChild(img);
```

Note: In a real setting, we recommend saving to state and re-making the blockie on prop change for better re-render performance.


License
-------

[MIT](https://opensource.org/licenses/MIT)
