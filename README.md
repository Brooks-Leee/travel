# 行程卡网页版部署说明（GitHub Pages）

> ✅ 已部署上线：**https://brooks-leee.github.io/travel/**
> 仓库：https://github.com/Brooks-Leee/travel
> 每次推送到 `main` 分支，GitHub Actions 会自动重新部署，1-2 分钟生效。

## 手机端使用

- **发微信**：把上面的链接发给家人，点开即看（本机实测 github.io 可直连）
- **iPhone 桌面图标**：Safari 打开 → 底部「分享」→「添加到主屏幕」→ 命名"行程卡"，之后点图标全屏打开，像 App 一样
- **离线版**：电脑上的 `赤壁-广州惠州-3天2晚行程卡-手机版.pdf`（10页，晴雨两套全含），微信文件传输助手发手机即可

## 更新流程

1. 在电脑上改主文件 `赤壁-广州惠州-3天2晚行程卡-PC版.html`
2. 让 AI 助手重新导出手机版 PDF，并把最新内容同步成本文件夹的 `index.html`，然后帮你推送到 GitHub（本机 SSH 已配好，不需要令牌）
3. 推送后约 1-2 分钟，手机刷新链接就是新版；链接不变、桌面图标不用重加

## 备忘（历史方案）

- Gitee Pages 已于 2026 年前后停服；仓库 `gitee.com/lee_oops/travel` 已不再使用，可删除
- 腾讯云托管 / EdgeOne Pages 为备选方案，拖拽包见 `网页版部署包.zip`
