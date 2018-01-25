Some color related Javascript methods that I keep coming back to.

Handy functions include:

- `colorIsLight(r, g, b)` detect whether a color is "light" or "dark"
- `random(lightness)` generate a random Hex color at the given lightness value, [0, 1]
- `hslToHex(h, s, l)` convert HSL color space to CSS-style hex color string
- hex-to-rgb and rgb-to-hex conversion functions

Includes `Color.js`, which can be dropped into an ES6 compatible project, like something created by `create-react-app`.

Also includes `color.glitch.js`, which can be dropped into a [Glitch.com](https://glitch.com) project as a client script. Can probably also be used anywhere else you might need it as a browser friendly drop in client side script.



