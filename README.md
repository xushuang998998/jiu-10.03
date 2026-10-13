# 商品横滑卡片工作室：PNG 上传版

本文件夹共 40 个文件。图片都是真正的 PNG，不再嵌入大体积 JavaScript 文件。最大单个文件约 2.6 MiB。

## 上传

上传本文件夹内的 `index.html`、整个 `assets` 文件夹、`.nojekyll` 和本说明，保留目录结构。不要压缩成 `assets.zip` 上传；仓库里的 ZIP 不会自动解压成网页资源。

如果整批上传失败，可以分批：先传网页及其他资源，再到仓库的 `assets/product-library` 目录每次上传 8 张产品 PNG。最终目录结构应与本文件夹一致。

## 保留的素材

- `assets/product-library`：16 张独立产品 PNG，与原文件一致。
- `assets/logo-library`：7 个独立 LOGO PNG。
- `assets/card-atlases`：9 张 PNG 图集，包含页面实际使用的 126 张切图，合并前后像素一致。
- `assets/product-effect.png`：商品效果图。
- `assets/fonts`：原方正兰亭中黑字体。

PNG 图集由页面自动取出对应切图，不需要手动裁切。`asset-map.js` 是小型位置索引，仍需一起上传。

完整原素材备份文件夹和独立产品 PNG 文件夹仍保留。编辑数据保存在当前浏览器。导出尺寸为 196 × 384 px，支持 PNG / JPG。

商品卡片设置集中在右侧工具栏，左侧保留组件目录和原有列表。只显示样式一，按钮和 LOGO 可独立开关，保留四种组合。右侧列表支持上移、下移和删除，商品图片支持上传、拖入、移除及恢复默认图片。

直接打开 HTML 可预览；导出请通过 GitHub Pages 或本地 HTTP 预览地址使用。
