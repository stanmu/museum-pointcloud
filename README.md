# 器物四观｜数字文物互动展

四件文物的三维点云、互动光影、来源依据与关联事件展陈。

源码保存在 museum-source.zip；图片和三维模型保存在 museum-assets-1.zip、museum-assets-2.zip、museum-assets-3.zip。GitHub Actions 自动解压源码与资源、构建并发布到 GitHub Pages。

本地还原项目：解压 museum-source.zip，将三个 museum-assets 压缩包解压到项目的 public/ 文件夹，然后运行：

```bash
pnpm install --frozen-lockfile
pnpm build:pages
pnpm preview:pages
```

使用 Node.js 24、pnpm 11.25.0。原展览为桌面布局，建议用电脑浏览。
