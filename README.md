# nezha-ui
##### 后台添加
###### 自用的探针更改 
```html
<meta name="referrer" content="no-referrer">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/IonRh/nezha-ui@main/nezha-style.css">
<script>
  var link = document.createElement('link');
  link.rel = 'stylesheet';
  link.href = 'https://font.sec.miui.com/font/css?family=MiSans:400,700:MiSans'; // MiSans
  document.head.appendChild(link);
  /* ==================== 全局配置 ==================== */
  window.ShowNetTransfer = "true";      // 卡片显示上下行流量
  window.CustomLogo = '/apple-touch-icon.png'; /* 页面左上角和标题栏展示的 Logo, 换成你自己的 */
  // window.DisableAnimatedMan = "true";   // 关闭动画人物插图
  window.CustomDesc = "稳定求签";       // 自定义描述
  window.CustomIllustration = 'https://s2.loli.net/2024/12/24/fj3EXY7umsyR9NW.webp'; /* 把基佬图换成你想换的图, 此处图抄袭自 https://misaka.se/ */
  window.CustomLinks = '[{\"link\":\"https://blog.loadke.tech/\",\"name\":\"Blog\"}]'; /* 自定义导航栏链接 */
  window.ForceTheme = 'light'; /* 强制主题色, 可选值为 light 或 dark */ 
</script>
<script src="https://cdn.jsdelivr.net/gh/IonRh/nezha-ui@main/netstatus-autoshow.js"></script>
<script src="https://cdn.jsdelivr.net/gh/IonRh/nezha-ui@main/traffic-progress.js"></script>
```
###### 周期性流量进度条 
```html
<script src="https://cdn.jsdelivr.net/gh/IonRh/nezha-ui@main/traffic-progress.js"></script>
```

###### 哪吒详情页直接展示网络波动卡片 
```html
/* 源自https://www.nodeseek.com/post-349102-1 */
<script src="https://cdn.jsdelivr.net/gh/IonRh/nezha-ui@main/netstatus-autoshow.js"></script>
```
###### 仪表板的自定义代码 
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/IonRh/nezha-ui@main/nezha-dashboard.css">
<script src="https://cdn.jsdelivr.net/gh/IonRh/nezha-ui@main/nezha-dashboard.js"></script>
```
###### 页面时间修改 
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/IonRh/nezha-ui@main/nezha-time.css">
```
