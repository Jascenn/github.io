# LingYi Static Pages

凌一的轻量静态页面仓库，通过 GitHub Pages 发布。页面均为纯 HTML、CSS 和 JavaScript，不需要构建步骤。

## 在线页面

- 首页：[https://jascenn.github.io/github.io/](https://jascenn.github.io/github.io/)
- 网盘链接转换工具：[https://jascenn.github.io/github.io/netdisk-link-converter.html](https://jascenn.github.io/github.io/netdisk-link-converter.html)

## 文件结构

```text
.
├── index.html                    # 网易云音乐年度报告展示页
├── netdisk-link-converter.html   # 网盘分享文案转公众号链接工具
└── .github/workflows/verify.yml  # 静态页面与本地链接检查
```

## 本地预览

在仓库根目录运行：

```bash
python3 -m http.server 8080
```

然后打开 <http://127.0.0.1:8080/>。

## 发布方式

GitHub Pages 直接读取 `main` 分支根目录。合并到 `main` 后，GitHub Pages 会自动发布最新静态文件。

## 维护说明

- 页面依赖 Tailwind CSS、AOS 和图标 CDN，离线环境下样式或动画可能不完整。
- 修改页面后至少检查桌面和手机宽度，并确认所有本地链接可访问。
- 本仓库用于个人展示和工具发布，未授予开源许可；如需复用页面代码或文案，请先联系作者。
