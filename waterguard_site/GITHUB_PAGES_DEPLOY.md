# GitHub Pages 发布说明（水安卫士）

## 已准备好
- 站点目录：`waterguard_site/`
- GitHub Actions 工作流：`.github/workflows/deploy-waterguard-pages.yml`

## 你现在要做的

### 1. 在 GitHub 上新建一个仓库
建议仓库名：
- `waterguard-site`
- 或 `shuianweishi-site`

### 2. 把本地仓库连接到 GitHub
把下面的 `YOUR_GITHUB_REPO_URL` 换成你的仓库地址：

```bash
cd /Users/hero/.openclaw/workspace-main
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin master
```

如果你的默认分支是 `main`，用：

```bash
cd /Users/hero/.openclaw/workspace-main
git branch -M main
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```

### 3. 在 GitHub 仓库里开启 Pages
进入：
- Settings
- Pages

确认 Source 使用 GitHub Actions。

### 4. 等待 Actions 自动部署
部署完成后，正式链接通常会是：

```text
https://你的GitHub用户名.github.io/仓库名/
```

例如：

```text
https://yourname.github.io/waterguard-site/
```

## 说明
这个工作流会把 `waterguard_site/` 目录作为 Pages 站点发布。

## 如果你要我继续帮你
把以下任意一个发我：
- GitHub 仓库地址
- 你 push 后的报错
- 部署完成后的 Pages 链接
