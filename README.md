# vue-print-nb-jeecg-fixed

This is a directive wrapper for printed, Simple, fast, convenient, light.
( 特定改造版本： 解决IE兼容问题和支持Canvas自适应打印 )

- 修复input为checkbox、radio时默认全部选中的问题。
- fix the problem of checkbox and radio default "checked" property.

## Install

#### NPM
```bash
npm install vue-print-nb-jeecg --save
```

```javascript
import Print from 'vue-print-nb-jeecg'

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
        <p>葫芦娃，葫芦娃</p>
        <p>一根藤上七朵花 </p>
        <p>小小树藤是我家 啦啦啦啦 </p>
        <p>叮当当咚咚当当　浇不大</p>
        <p> 叮当当咚咚当当 是我家</p>
        <p> 啦啦啦啦</p>
        <p>...</p>
    </div>

    <button v-print="'#printMe'">Print local range</button>
```


## License

[MIT](http://opensource.org/licenses/MIT)


## 上传NPM官仓
- 1、npm run prepublish 生成lib文件
- 2、npm publish
- 3、npm unpublish vue-print-nb-jeecg-fixed --force

