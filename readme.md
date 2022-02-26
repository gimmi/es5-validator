## Use in browser

```html
<script src="src/validator.js"></script>
<script type="text/javascript">
    new Validator({ str: 123 }).checkKey('str', Number)
</script>
```

Also see [In browser spec runner](http://gimmi.github.io/es5-validator/spec-runner.html)

## Use in NodeJS

Install package

```
npm i @gimmi/es5-validator
```

use it

```js
const Validator = require('@gimmi/es5-validator')

new Validator({ str: 123 }).checkKey('str', Number)
```

Also see nodejs test by running `npm test`
