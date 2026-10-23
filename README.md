# 校园跑腿

校园内的顺路互助跑腿平台 —— 代取快递、带饭、打印、送文件，把零散需求和顺路的同学对上。

## 在线访问

**https://khris12138.github.io/campus-errand/**

> 该链接为长期固定地址，由 GitHub Pages 托管，请勿更换仓库名，否则链接路径会变化。

## 本地预览

纯静态页面，无需安装依赖：

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 部署方式

仓库 `main` 分支根目录 → GitHub Pages 自动发布。
推送到 `main` 后约 1 分钟生效：

```bash
git add .
git commit -m "更新内容"
git push
```

## 目录结构

```
.
├── index.html   # 入口页面
├── .nojekyll    # 关闭 Jekyll 处理，避免下划线开头的文件被忽略
└── README.md
```
