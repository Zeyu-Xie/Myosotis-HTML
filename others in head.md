# Meta Labels in HTML

## Base

Base 标签用来指定页面的基础 URL，例如我们在 ```<head>``` 中添加如下代码：

```
<base href="https://zeyu-xie.github.io/Wisteria-Blog/">
```

则页面的基础 URL 就是 https://zeyu-xie.github.io/Wisteria-Blog/，换句话说，当我在后续 HTML 代码中使用相对链接（如 ./relative），基础 URL 就会是 https://zeyu-xie.github.io/Wisteria-Blog/，此时合成的绝对路径为 https://zeyu-xie.github.io/Wisteria-Blog/relative

**⚠️ 上述代码中 ```href``` 内的 URL 应以“/”结尾，否则会发生错误**

## Title

Title 标签指定页面的标题，如：

```
<title>Wisteria Blog - A Snowy Day</title>
```

## Link

Link 标签主要具有以下几个作用

1. 页面图标 ```<link rel="icon" href="./favicon.ico">```
2. CSS 样式表 ```<link rel="stylesheet" href="./index.css">```
3. 苹果触摸图标（将网页添加到 iOS 设备的主屏幕时显示的图标） ```<link rel="apple-touch-icon" href="./apple-touch-icon.ico">```
4. 外部资源预获取（可提高响应速度），例如引入一个字体文件 ```<link rel="preload" href="https://example.com/font.woff2" as="font" type="font/woff2" crossorigin>```
5. 替代页面
   1. 其它语言版本 ```<link rel="alternate" hreflang="es" href="https://example.com/page-es.html">```
   2. RSS 或 Atom 源 ```<link rel="alternate" type="application/rss+xml" title="RSS Feed" href="https://example.com/rss-feed.xml">```
6. DNS 预解析 ```<link rel="dns-prefetch" href="https://example.com">```

## 
