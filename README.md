# jq-scrollto

Assigns a scrollTo method to jQuery.

## Usage

```js
window.$ = window.jQuery = require('jquery')
require('jq-scrollto')

$.scrollTo('#target')
```

## Functions

<a name="scrollTo"></a>

### $.scrollTo(target, [time], [easing], [callbackFn])
Scroll to the target selector.

| Param | Type | Default |
| --- | --- | --- |
| target | <code>string</code> |  | 
| [time] | <code>number</code> \| <code>function</code> | <code>1500</code> | 
| [easing] | <code>string</code> \| <code>function</code> | <code>&#x27;easeInOutCubic&#x27;</code> | 
| [callbackFn] | <code>function</code> |  | 
