# nezha-ui
##### 后台添加
###### 自用的探针更改 
```html
<meta name="referrer" content="no-referrer">
/* 自用的css格式 */
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/IonRh/nezha-ui@main/nezha-style.css">
/* 自用的探针修改 */
<script>
  /* 自定义字体 */
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
  window.CustomLinks = '[{\"link\":\"https://uptime.loadke.tech/\",\"name\":\"UPTime\"}]'; /* 自定义导航栏链接 */
  window.ForceTheme = 'light'; /* 强制主题色, 可选值为 light 或 dark */ 
</script>
```
###### 周期性流量进度条 
```html
/* 周期性流量进度条 */
<script>
  window.TrafficScriptConfig = {
    showTrafficStats: true,    // 显示流量统计
    insertAfter: true,         // 如果开启总流量卡片, 放置在总流量卡片后面
    interval: 60000,           // 60秒刷新缓存, 单位毫秒
    toggleInterval: 4000,      // 4秒切换流量进度条右上角内容, 0秒不切换, 单位毫秒
    duration: 500,             // 缓进缓出切换时间, 单位毫秒
    enableLog: false           // 开启日志
  };
</script>
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
