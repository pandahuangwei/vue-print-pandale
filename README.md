# vue-print-pandale
The directive wrapper for printed,fast,Simple,light.

## Install

#### NPM
```bash
npm install vue-print-pandale --save
```

```javascript
import Print from 'vue-print-pandale'

Vue.use(Print);
```


## Description

#### Print the entire page:

```
<button v-print>Print the entire page</button>
```


#### Print local range:

HTML:
```
    <div id="printMe" style="background:red;">
        <p>怀瑾握瑜兮，穷不知所示</p>
        <p>青黛 </p>       
        <p>...</p>
    </div>

    <button v-print="'#print'">Print local range</button>
```


## License

[MIT](http://opensource.org/licenses/MIT)