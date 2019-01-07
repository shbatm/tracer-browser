## tracer-browser: A Browserify-ied version of the [tracer](https://www.npmjs.com/package/tracer) Node.js Module

### Use:

1. Copy `/dist/tracer-bundle.js` to your site's source directory.
2. Include the following in your HTML page code:

```html
<script src="/path/to/scripts/tracer-bundle.js"></script>
```

3. The `Tracer` global variable will be exposed, and you can use it just like if you used the following in your Node.JS file:

```js
const Tracer = require('tracer');
```

See the `tracer` [documentation](https://www.npmjs.com/package/tracer) for details on configuration.