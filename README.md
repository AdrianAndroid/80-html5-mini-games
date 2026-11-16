# 80 HTML5 Mini Games

一个包含 80 个游戏入口的 HTML5 小游戏合集，涵盖益智、动作、射击、消除、休闲和棋牌等类型。其中部分游戏是同一玩法的不同版本。

## 在线体验

[打开 H5 小游戏合集](https://adrianandroid.github.io/80-html5-mini-games/)

`main` 分支更新后，GitHub Actions 会自动将 `80h5` 目录部署到 GitHub Pages。

## 本地运行

无需安装依赖或构建项目。在本目录运行：

```bash
python3 -m http.server 8000 --directory 80h5
```

然后在浏览器中打开 <http://localhost:8000>。

## 项目结构

```text
80h5/
├── index.html       # 合集首页
├── link/            # 全部游戏及分类页面
├── yxmb/            # 80 个游戏目录，编号为 1～80
├── images/          # 首页及游戏封面图片
├── css/             # 合集页面样式
└── js/              # 合集页面脚本
架设教程.html         # 原有部署说明
```

完整游戏名称和入口可查看 [`80h5/link/0.html`](80h5/link/0.html)。各游戏支持的操作方式和设备可能不同，请以游戏内说明为准。

## 版权说明

本仓库为第三方小游戏合集，游戏代码及图片、音频等素材的权利归各自作者或权利人所有。公开传播或用于其他项目前，请自行确认相应的授权和许可条件。
