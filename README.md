# 公募FOF基金跟踪系统 - 展示仓库

这个目录用于发布给其他人查看，不在这里做数据更新。

## 发布内容

- `index.html`
- `styles.css`
- `app.js`
- `data/fof_tracker_snapshot.js`
- `data/fof_tracker_snapshot.json`

## 推荐使用方式

1. 先在主项目中更新数据：
   - `fof-tracker/scripts/build_fof_tracker_snapshot.py`
2. 再运行同步脚本：
   - `/Users/menyao/Documents/trae_projects/sync_fof_tracker_pages.sh`
3. 将本目录推送到单独的 GitHub 仓库
4. 在 GitHub Pages 中发布

## GitHub Pages

建议单独建立一个展示仓库，例如：

- `fof-tracker-pages`

仓库推送后，在 GitHub 仓库设置中打开：

- `Settings`
- `Pages`
- `Deploy from a branch`
- `Branch: main`
- `Folder: /(root)`

之后即可得到一个固定网页链接，用于分享给其他人查看。
