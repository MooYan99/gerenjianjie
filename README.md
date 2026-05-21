# 个人介绍网页

这是一个使用 HTML、CSS、JavaScript 制作的静态个人介绍网页，适合部署到 GitHub Pages。

## 文件结构

- `index.html`：页面内容
- `styles.css`：页面样式与响应式布局
- `script.js`：导航、年份等轻量交互
- `assets/`：放置头像、微信二维码等图片

## 替换个人信息

打开 `index.html`，替换以下内容：

- `Alex Chen`：个人姓名
- 一句话介绍
- 个人简介
- 业务/技能
- 项目案例
- 邮箱、电话、微信号、社交账号

如果有微信二维码图片，将图片命名为 `wechat-qr.png` 并放入 `assets/` 文件夹，然后把二维码占位区域替换为：

```html
<img src="assets/wechat-qr.png" alt="微信二维码" />
```

## GitHub Pages 部署方式

1. 创建一个 GitHub 仓库。
2. 将本项目文件推送到仓库的 `main` 分支。
3. 进入仓库 Settings → Pages。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待部署完成。

公开访问链接通常是：

```text
https://你的用户名.github.io/仓库名/
```
