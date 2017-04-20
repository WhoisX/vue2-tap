# vue2-tap 
> a v-tap directive of vue.js

##install
``` bash
	npm install vue2-tap --save; 
## How To use
> * ES6
```js
import vueTap from 'Vue2-tap'
Vue.use(vueTap)
# install v-tap  


> * 直接引入
```html
<script src="./vue.js"></script>
<script src="./vue-tap.js"></script>

## Vue2.0 用法
```html
<a  v-tap></a>

<p v-tap="{ handler:method, params:[a,b,$event]}">带参数</p>
<a v-tap="tap">不带参数</a>

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
