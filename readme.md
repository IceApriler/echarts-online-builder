# echarts-online-builder 在线构建

### 说明
echarts官方在线定制网址：`https://echarts.apache.org/zh/builder.html`
由于官方现在已经不能选择版本号，而且手动传版本号也不行，Apache的源已经没有历史版本，所以只能自己下载源码，并修改了echarts源。现在已可以正常使用。

### 使用步骤
使用定制网址获取原链接，比如：
```
https://echarts.apache.org/zh/builder/echarts.html?charts=bar,pie&components=gridSimple,title,legendScroll,tooltip&source=true
```
替换为本地新链接，并传版本号（新版本的用在小程序上有问题，所以用5.3.3版本）：
```
http://127.0.0.1:5502/echarts.html?version=5.3.3&charts=bar,pie&components=gridSimple,title,legendScroll,tooltip&source=true
```