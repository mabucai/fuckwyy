# fuckwyy

一个纯静态互动点击网页，针对 GitHub Pages 制作。黑红配色，支持手机和电脑。

- 11 张表情图，支持点击选择和随机切换。
- 点击大按钮、图片或按空格加一。
- 连击动画、可选音效、最高连击、今日点击和表情热力榜。
- 计数只保存在当前浏览器的 localStorage，不是全站共享计数。清理浏览器数据会清空记录；浏览器禁用存储时显示“临时模式”。
- 无框架、无需安装依赖、无外部字体和统计脚本。

## GitHub Pages

仓库的 `main` 分支根目录作为发布来源；`.nojekyll` 禁用 Jekyll 处理。所有素材都使用相对路径，支持 `https://用户名.github.io/fuckwyy/` 和以后绑定的独立域名。

## 本地打开

直接打开 `index.html` 即可查看页面。分享链接功能需要 HTTPS 或本地 HTTP。也可在本目录运行 `python -m http.server 8080`，然后打开 `http://localhost:8080`。

## 修改

- `index.html`：页面文案和结构。
- `style.css`：响应式样式。
- `app.js`：点击、表情切换、音效和本机存档。
- `assets/`：图片资源，原始文件未被修改。

参考 [fuck-dario.dog](https://fuck-dario.dog/) 的点击站形式，页面代码为独立实现。
