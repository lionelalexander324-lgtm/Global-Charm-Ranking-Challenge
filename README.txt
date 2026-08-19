Global Charm Ranking H5 - Single HTML Code Version

这个版本按你的要求调整为：
1. CSS 和网页内容全部写在 index.html 里。
2. 不再有独立 css/ 或 js/ 文件。
3. 后续如果只修改网页文案、颜色、间距、字体、卡片样式，只需要更新 index.html。
4. assets 文件夹只保留两张图片：
   - hero-banner.webp：你最新上传的头图
   - ranking.webp：排行榜图一

本次修改：
- 头图已替换为最新上传图片，并保持原图比例，不拉伸、不裁切。
- “🗓️ EVENT TIME” 左对齐。
- Event Time 板块整体缩小。
- Event Time 改成暖黄色卡片，与其他区域区分。
- “The top 3 users on the ranking will receive extra rewards:” 左对齐。
- Rewards 继续使用一个大卡片框住全部内容。
- 排行榜图片使用 lazy loading。
- 头图使用 WebP + preload + fetchpriority=high，提高首屏加载速度。
- HTML 设置 no-cache，减少 GitHub Pages 更新后手机端仍显示旧版的问题；图片使用版本号避免图片缓存不刷新。

上传 GitHub Pages 时：
把 index.html 和 assets 文件夹放在同一级目录即可。
以后如果你只改文字/CSS，只需要替换 index.html。
