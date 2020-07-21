# QRCode.js

js是用于制作QRCode的javascript库。js在DOM中支持HTML5 Canvas和表格标签的跨浏览器。js没有依赖关系。

##### 里面有四个文件,你可以参考

- index-1.html
- index-2.html
- index-3.html

## 基本用法

```
<div id="qrcode"></div>
<script type="text/javascript">
new QRCode(document.getElementById("qrcode"), "http://jindo.dev.naver.com/collie");
</script>
```

or with some options

```js
<div id="qrcode"></div>
<script type="text/javascript">
var qrcode = new QRCode(document.getElementById("qrcode"), {
	text: "http://jindo.dev.naver.com/collie",
	width: 128,
	height: 128,
	colorDark : "#000000",
	colorLight : "#ffffff",
	correctLevel : QRCode.CorrectLevel.H
});
</script>
```

*你可以使用这些方法*

```js
qrcode.clear(); // clear the code.
qrcode.makeCode("http://naver.com"); // make another code.
```

## 浏览器兼容性

IE6~10, Chrome, Firefox, Safari, Opera, Mobile Safari, Android, Windows Mobile, ETC.

### 有疑问请留言邮箱
第一次做开源小demo，有错的地方纠正一下，谢谢各位大神
1259446122@qq.com

