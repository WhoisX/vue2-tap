# vue2-tap 
[![npm](https://img.shields.io/npm/v/v-tap.svg)](https://www.npmjs.com/package/v-tap) [![npm](https://img.shields.io/npm/dm/v-tap.svg)](https://www.npmjs.com/package/v-tap)

> a v-tap directive of vue.js
## How To use
> * ES6


# install v-tap  
``` bash
npm install v-tap --save; 

> * 直接引入
```html
<script src="./vue.js"></script>
<script src="./vue-tap.js"></script>

## Vue2.0 用法
```html
<a  v-tap></a>

<p v-tap="{ handler:method, params:[a,b,$event]}">带参数</p>
<a v-tap="tap">不带参数</a>

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
