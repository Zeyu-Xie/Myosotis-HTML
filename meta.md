# Meta Labels in HTML

默认编码方式为 UTF-8

```
<meta charset = "UTF-8">
```

作者、关键词、页面描述

```
<meta name="author" content="Acan">
<meta name="keywords" content="Education, Academy, MAthematics">
<meta name="description" content="An article on mathematics education">
```

根据 Open Graph 协议，页面在社交媒体上展示的标题，图片和页面描述

```
<meta property="og:description" content="Acan's standard web template. ">
<meta property="og:image" content="./ogImage.jpg">
<meta property="og:title" content="Myosotis Config - Web">
```

浏览器属性：页面渲染引擎、移动设备上的显示、主题色

```
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#ffffff">
```

系统属性：页面添加到操作系统系统中的快捷方式的属性

```
<meta name="apple-mobile-web-app-title" content="Wisteria Blog - A Snowy Day">
<meta name="msapplication-TileColor" content="#ffffff">
```

搜索引擎爬虫行为：允许收录、遵循原链接

```
<meta name="robots" content="index, follow">
```

引用行为：始终发送引用者信息

```
<meta content="always" name="referrer">
```

