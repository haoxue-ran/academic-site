# Haoxue Ran Academic Homepage

这是一个简洁的静态学术主页，风格参考 al-folio，直接部署在 GitHub Pages。

## 页面

- `index.html`：首页，包含个人简介、联系方式、新闻和代表性论文
- `publications/index.html`：论文列表
- `projects/index.html`：研究方向
- `cv/index.html`：CV 页面

## 常用修改

### 更新个人照片

替换 `assets/img/profile.png`，保持图片为正方形效果最佳。

### 更新邮箱 / 学术主页链接

打开 `index.html`，在页面底部的 `social` 区域修改：

```html
<a href="mailto:haoxue.r@xauat.edu.cn" title="email">...</a>
<a href="https://scholar.google.com/citations?user=PS_CX0AAAAAJ" title="Google Scholar">...</a>
<a href="https://github.com/haoxue-ran" title="GitHub">...</a>
```

### 更新新闻

编辑 `index.html` 中 `news` 表格里的 `<tr>`。

### 新增论文

编辑 `publications/index.html`，复制一个 `<li>` 条目，替换标题、作者、期刊和链接。

### 更新 CV

编辑 `cv/index.html`，按现有 `cv-card` 结构补充教育、经历和技能。

## 部署

将本目录内容提交到 GitHub 仓库 `haoxue-ran/academic-site` 的 `main` 分支即可。仓库里的 `.nojekyll` 会让 GitHub Pages 直接发布静态文件，不需要安装 Jekyll。

上线地址会是 `https://haoxue-ran.github.io/academic-site/`。
