# 路迹 RoadTrace

自驾旅行记录工具的网页版交互原型，展示路线、海拔曲线、旅程节点和道路影像查看入口。

## 当前状态

这是静态界面原型，使用 HTML、CSS 和原生 JavaScript，无需安装依赖。

- 路线地图与海拔数据为示意数据，不可用于导航。
- “开始记录”使用计时器模拟状态，尚未接入 GPS，也不会持久保存轨迹。
- “道路实景”使用示例照片与模拟进度条，尚未接入视频或街景服务。
- 历史路线选择目前仅改变选中状态；导入、分享等入口尚未实现。

## 本地运行

在仓库目录执行：

```sh
python3 -m http.server 4173 --directory dist
```

浏览器打开 http://localhost:4173 。也可直接打开 `dist/index.html`；示例图片需要联网加载。

## 文件

- `dist/index.html`：页面、样式和交互源码。
- `.openai/hosting.json`：现有 Sites 站点配置。
- `work/`、`outputs/`：本地中间文件和导出文件，不提交到 Git。

## 预览

现有私有预览：https://roadtrace.yujingnai.chatgpt.site （需要获准访问的账号）。

## 图片来源

道路示例照片：[Luke Miller / Unsplash](https://unsplash.com/photos/a-white-car-driving-down-a-mountain-road-N4evy1PZjaw)。照片仅用于界面示意，不代表页面标注的川西路段。
