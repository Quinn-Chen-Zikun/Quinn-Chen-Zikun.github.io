# Zikun Chen — Personal Homepage

我的个人学术主页源码。

- 线上地址：https://quinn-chen-zikun.github.io/
- 研究方向：AI Safety · Agentic AI
- 站点基于 [PRISM](https://github.com/xyjoey/PRISM) 模板（MIT License，见 [LICENSE](LICENSE)）构建

## 内容维护

所有文字内容都在 `content/` 目录：

| 文件 | 内容 |
| --- | --- |
| `content/config.toml` | 姓名、头衔、联系方式、社交链接 |
| `content/bio.md` | 首页自我介绍 |
| `content/news.toml` | 首页 News 动态 |
| `content/cv.md` | CV 页面 |
| `public/bio.jpg` | 个人照片（整张显示，不裁剪） |

## 本地开发

```bash
npm install
npm run dev      # http://localhost:3000
```

修改 `content/` 下的文件后页面会自动刷新。

## 部署

推送到 `main` 分支后，GitHub Actions 会自动构建并部署到 GitHub Pages（约 1–2 分钟）。
