---
extends: _layouts.howto
date: 2017-12-17
link: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toString
---


```javascript
const value = {
    name: 'John'
};

Object.prototype.toString.call(value) === '[object Object]';
```
<pre class="output">true</pre>