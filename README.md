# JQuery Optional Number Step
Dynamic HTML5 number step.

Why?

HTML5 forms has own validation for `step` rule.

This plugin add `step` attribute to field temporarily while changes are made.

How to use
1. include `jquery.number-step.js` script to your web page. jQuery required!
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="jquery.number-step.js"></script>
```

2. Add `optionalNumberStep` function to your `input[type="number"]` fields.
```js
$('[name="width"]').optionalNumberStep(100);
```

3. To deactivate dynamic step use 'unset' value.
```js
$('[name="width"]').optionalNumberStep('unset');
```
