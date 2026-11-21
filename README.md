# 小小杜的三亚记忆 — GitHub Pages 静态站

单文件站：`index.html` + `assets/`（照片 25 张、视频 20 段、封面 20 张），
全部相对路径引用，直接推到 GitHub 公开仓库根目录即可开 Pages。

## 发布步骤

1. 新建公开仓库（例如 `sanya-album`），把本目录全部内容推到默认分支根目录。
2. 仓库 Settings → Pages → Build and deployment → Source 选 Deploy from a branch，
   Branch 选默认分支、根目录 `/`，保存。
3. 访问 `https://<用户名>.github.io/<仓库名>/`。

## 说明

- 不加密；已加 `<meta name="robots" content="noindex">`（链接可打开，不进搜索引擎）。
- 视频均为 H.264 MP4，`preload=metadata`，点开才加载；背景音乐为 Web Audio 合成钢琴，
  播放带声视频时自动避让。
- 内容：45 条（25 张照片 + 20 段视频），六段：抵达 / 逛吃 / 园子里 / 亚特兰蒂斯 /
  告别 / 花絮 · 会动的片段；封面为最后一天草坪全家福。
