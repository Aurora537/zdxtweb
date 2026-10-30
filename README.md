# 智达星图官网

智达星图官方网站的静态页面源码。

## 目录结构

```
index.html          首页
assets/css/style.css    样式
assets/js/app.js        交互逻辑
assets/js/data.js       页面数据
assets/fonts/           本地字体子集（思源系书法体）
assets/img/             封面图
```

## 本地预览

纯静态站点，直接用浏览器打开 `index.html`，或在项目根目录启动任意静态服务器：

```
python -m http.server 8080
```

然后访问 <http://localhost:8080/>。

## 部署

站点为纯静态资源，可直接托管到任意静态站点服务（对象存储 / CDN / Pages）。

客户端安装包不在本仓库内，统一通过 Release 资源分发，页面下载按钮指向固定直链。
