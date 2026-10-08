# 《千山獨行》网站 · Beyond a Thousand Mountains

本仓库是文刃诗集《千山獨行》网站的**唯一一份源码**。仓库名 `leonliu1726.github.io` 即网址，不能改名。

| | |
|---|---|
| 正式网址 | **https://leonliu1726.github.io/beyondathousandmountains/** |
| 托管 | GitHub Pages（`main` 分支根目录），推送后约一分钟上线 |
| 维护铁律 | `beyondathousandmountains/MAINTENANCE.md`（改之前先读） |

## 目录

- `beyondathousandmountains/`：《千山獨行》网站本体
  - 卷首 `index.html`、作者 `poet.html`、作品 `book.html`、畫卷 `scroll.html`、詩評 `reviews.html`、鑑賞 `poems/`（17 首）、行者 `wayfarer.html`、結卷 `colophon.html`
  - `网站图片/畫卷/`：98 幅诗意图折页的网页图（`NN-2` 画页、`NN-3` 诗页、`NN-4` 英文页、`NN-t` 缩略图），源文件在桌面「文学\千山独行 发布\01_诗意图折页_定稿」
  - `网站图片/作者/qizhi-seal*.webp`：全站题头所用「其志」印，与画卷所钤为同一方
- `index.html`（根目录）：「文刃 · 诗文天地」入口页
- `thepalmpoetryclub/`：掌心旧网址的跳转页，一律跳到 https://palmpoetry.org/ ，不得改回完整网站
- `training-log.txt`：Leon 第一次亲手提交（2026-07-23），留作纪念

## 只此一份

2026-10-08 以前，`palm-poetry-sites` 仓库里还有一份《千山獨行》副本（`上线包_千山独行/`），本站有 100 多张图和音视频是从那份副本的网址借用的。当天已把被引用的 106 个文件收回本仓库、改为站内路径，副本随即撤除。**以后只改这里，不再同步到任何别处。**

## 发布

GitHub Desktop → Commit → Push。不需要构建。

---

## Leon 的五个仓库

| 仓库 | 可见性 | 管什么 | 发布到 |
|---|---|---|---|
| `leonliu1726.github.io` | 公开 | 《千山獨行》诗集网站（唯一一份）+ 根目录入口页 + 掌心旧网址跳转 | GitHub Pages：https://leonliu1726.github.io/beyondathousandmountains/ |
| `palm-poetry-sites` | 公开 | 掌心诗社官网 | Cloudflare Pages：https://palmpoetry.org/ |
| `vtrust-website` | 私有 | V-Trust Corporation 官网 | Cloudflare Pages：https://vtrustcorporation.com/ |
| `poem-tools` | 私有 | 千山独行配画、翻译、发布脚本 | 不发布（本地工具） |
| `homer` | 私有 | 荷马 Homer 文刃风格写作助手 | Google Cloud Run |
