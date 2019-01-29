hqx
===

**hqx Pixel Art Scaling Algorithm for JavaScript/Canvas**

This project is a fork of
[phoboslab/js-hqx](https://github.com/phoboslab/js-hqx), adding support to Node,
through [node-canvas](https://github.com/Automattic/node-canvas).

Results
---

**Original:**

<img src="test/test.png?raw=true" />

**Transformed (3x):**

<img src="test/test-3.png?raw=true" />

CLI Usage
---

Install hqx:

```
npm install -g hqx
```

Run with input + scale ratio:

```
hqx test.png 2 > test-2x.png
hqx test.png 3 > test-3x.png
hqx test.png 4 > test-4x.png
```

Usage
---

```javascript
var scaledCanvas = hqx( originalImage, 3 );
```

The second argument is the scaling factor. hqx supports 2, 3 and 4. See index.html for an example.

License
---

Please see LICENSE file.
