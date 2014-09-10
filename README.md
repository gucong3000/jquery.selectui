jquery.selectui
===============

Modifying select appearance

本插件可以达到定制select标签外观的目的，而不改变原有任何事件，操作等机制，对键盘友好，对盲人友好。
但请注意，select会被新标签包裹。

本插件非常轻量，仅仅改变外观，select原有的弹出部分并未做任何修改，故不受页面可视区域限制。

## 用法与参数

```Javescript
$("select").selectui({
	// 是否自动计算宽度
	autoWidth: true,
	// 是否启用定时器刷新文本和宽度
	interval: true
});
```

##

## 浏览器支持

兼容IE6+和其他现代浏览器
