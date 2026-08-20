# 旅行档案网页版（GitHub Pages）

> ✅ 已上线：
> - 档案首页（目录）：**https://brooks-leee.github.io/travel/**
> - 广州行程：**https://brooks-leee.github.io/travel/guangzhou.html**
> 仓库：https://github.com/Brooks-Leee/travel
> 每次推送到 `main` 分支，GitHub Actions 自动重新部署，1-2 分钟生效。

## 目录结构（每个行程一个文件）

```
travel/
├── index.html        ← 档案首页（行程卡片列表，总入口）
├── guangzhou.html    ← 广州惠州行（示例行程）
├── beijing.html      ← 以后新增的行程，照此格式
└── ...
```

## 新增一条行程记录怎么弄

1. 把新行程的内容（日期/交通/每天安排/预算）发给 AI 助手
2. AI 按同款样式生成 `xxx.html`（手机自适应排版现成），并在 `index.html` 里加一张入口卡片
3. 推送后约 1-2 分钟生效，档案首页自动出现新行程；家人不用改任何东西，刷新即见

## 手机端使用

- **档案首页**：Safari 打开 → 分享 → 添加到主屏幕，图标命名"旅行档案"，以后所有行程都从这里进
- **单个行程**：也可以单独收藏/添加到主屏幕
- **离线版**：各行程另有 PDF 版（如 `赤壁-广州惠州-3天2晚行程卡-手机版.pdf`），微信文件传输助手发手机即可

## 备忘

- 本文件夹（`网页部署源`）是部署源：`index.html`=档案首页，`guangzhou.html`=广州行程
- 主编辑文件仍是 `赤壁-广州惠州-3天2晚行程卡-PC版.html`，改完让 AI 同步到 `guangzhou.html` 并推送
- Gitee 仓库 `lee_oops/travel` 已弃用，可删除
