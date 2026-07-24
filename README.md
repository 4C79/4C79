# 4c79.github.io

Personal website — plain static HTML, no build step, no dependencies.

## 部署(一次性,约 5 分钟)

1. GitHub 上新建 public repo,名字必须是 **`4C79.github.io`**(旧的已改名为 `4C79.github.io-old`,不冲突)
2. 把本文件夹的内容推上去:

```bash
git init && git add -A && git commit -m "Personal website" && git branch -M main && git remote add origin https://github.com/4C79/4C79.github.io.git && git push -u origin main
```

3. repo → Settings → Pages → Source 选 `Deploy from a branch`,分支 `main` / 根目录 `/`
4. 等 1–2 分钟,访问 https://4c79.github.io

## 部署前要补的东西

- [ ] `assets/photo.jpg` — 照片(≥300px 宽的方形图),然后取消 `index.html` 里 `<img>` 那行的注释
- [ ] `assets/cv.pdf` — Overleaf 编译好的两页 CV,导出后改名放进来
- [ ] 核对 `index.html` 里所有 `TODO` 注释(News 各条月份、博士毕业年份、Semantic Prompting 作者顺序、SoG 标题)

## 日常更新

改 `index.html` → commit → push,1 分钟后线上生效。常改的三处:News 顶部加一条、Publications 加一条、`assets/cv.pdf` 换新版。

论文中了之后记得同时更新:这个网站、Google Scholar、简历 `.tex`、GitHub profile README。
