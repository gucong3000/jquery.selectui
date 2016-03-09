jquery.selectui
===============

Modifying select appearance

本插件可以达到定制select标签外观的目的，而不改变原有任何行为、操作等机制，对触屏、键盘、盲人浏览器等友好，可访问性一流。
但请注意，select会被新标签包裹。

本插件非常轻量，仅仅改变外观，select原有的弹出部分并未做任何修改，故不受页面可视区域限制。

## 用法与参数默认值

```Javescript
$("select").selectui({
	// 设置从<option>何处获取占位字符，String或Function，默认"label"，设置为函数时，取函数返回值。
	label: "label",
	// 是否自动计算宽度，设置为false时可css设置宽度，默认`true`
	autoWidth: true,
	// 是否启用定时检测select当前选中项，当改变时更新文本，默认`true`
	interval: true
});

// $.fn.selectui.options 可修改参数默认值
```

## 浏览器支持

兼容IE6+和其他现代浏览器

## 其他

著名的IE6下select无法被div遮盖的bug，由于外观被改变而正好得到解决。
