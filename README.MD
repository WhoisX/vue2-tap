# vue2-tap 
> a v-tap directive of vue.js
## install
``` bash
npm install vue2-tap --save;
```
## How To use
- Available through npm as `vue2-tap`.
```bash
npm install v-tap --save; 
```
```js
//import vueTap from 'Vue2-tap'
var VueTap = require('vue2-tap')
Vue.use(vueTap)
````


```js
var VueTap = require('vue2-tap')
Vue.use(VueTap)
```
## Vue2.0 用法
```html
<p v-tap="{ handler:method, params:[a,b,$event]}">带参数</p>
<a v-tap="tap">不带参数</a>
```
```js
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
