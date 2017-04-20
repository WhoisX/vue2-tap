# vue2-tap 
[![npm](https://img.shields.io/npm/v/v-tap.svg)](https://www.npmjs.com/package/v-tap) [![npm](https://img.shields.io/npm/dm/v-tap.svg)](https://www.npmjs.com/package/v-tap)

> a v-tap directive of vue.js
## How To use
- Available through npm as `vue2-tap`.
```bash
npm install v-tap --save; 
```

```js
var VueTap = require('vue2-tap')
Vue.use(VueTap)
```
## Vue2.0 用法
```html
<p v-tap="{ handler:method, params:[a,b,$event]}">带参数</p>
<a v-tap="tap">不带参数</a>
```

```javascript
new Vue({
	el: "#app",
	methods : {
		method : function(a,b,event) {
			
		},
        tap:fucntion(){

        }
	}
});
```
