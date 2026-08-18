# 元吾氏微信答疑｜GitHub Pages 临时发布版

本目录是独立的网页发布副本，不包含原始微信数据库和处理脚本。

## 目录结构

```text
index.html
assets/
.nojekyll
README.md
```

## 使用 GitHub Desktop 上传（推荐）

1. 安装并登录 GitHub Desktop。
2. 选择 `File → Clone repository`，选择已经创建的仓库并克隆到电脑。
3. 把本目录中的全部内容复制到刚克隆的仓库根目录。应当让 `index.html` 直接位于仓库最外层，不要在外面再套一层文件夹。
4. 回到 GitHub Desktop，在左下角填写提交说明，例如 `Publish temporary preview`。
5. 点击 `Commit to main`，再点击顶部的 `Push origin`。
6. 打开 GitHub 仓库网页，进入 `Settings → Pages`。
7. 在 `Build and deployment` 中选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/(root)`，然后保存。
8. 等待几分钟，在 Pages 设置中点击 `Visit site`。

项目站点地址通常类似：

```text
https://你的GitHub用户名.github.io/仓库名/
```

## 临时展示结束后

进入仓库的 `Settings → Pages`，取消发布（Unpublish）。如仓库也不再需要，可再将仓库改为私有或删除。

## 搜索引擎说明

`index.html` 已加入 `noindex`、`nofollow`、`noarchive` 等指令，要求常见搜索引擎不要收录或建立快照。但页面仍是公开链接；任何获得链接的人仍可访问或转发。
