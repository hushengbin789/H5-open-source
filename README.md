# H5-open-source
javaScript生成二维码开源demo
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
new QRCode(document.getElementById("qrcode"), "https://github.com/hushengbin789");
</script>
```

or with some options

```js
<div id="qrcode"></div>
<script type="text/javascript">
var qrcode = new QRCode(document.getElementById("qrcode"), {
	text: "https://github.com/hushengbin789",
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
qrcode.makeCode("https://github.com/hushengbin789/"); // make another code.
```

## 浏览器兼容性

IE6~10, Chrome, Firefox, Safari, Opera, Mobile Safari, Android, Windows Mobile, ETC.

###有疑问请留言
小白刚开始玩，大神请多多指点，谢谢
1259446122@qq.com

