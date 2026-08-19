Global Charm Ranking Challenge - H5 Resource Pack

文件说明
1. index.html                主页面
2. css/style.css             页面样式
3. js/app.js                 轻量交互动效 + service worker 注册
4. js/sw.js                  本地缓存脚本
5. assets/hero-banner.jpg    头图占位图（可直接替换成你的正式banner）
6. assets/ranking.webp       排行榜图片（已使用你提供的图一并压缩为 WebP）

你可以直接部署到 GitHub Pages 或任意静态服务器。

缓存与加载速度优化
- 所有静态资源都加了版本号 ?v=20260819-1
- 使用 preload 预加载头图和排行榜图
- 排行榜图已转为 WebP，体积更小
- 使用极简 CSS/JS，减少首屏负担
- 内置 service worker，用于静态资源缓存

如果你后续更新了图片或样式，建议同步修改这些位置的版本号：
- index.html 里的 ?v=20260819-1
- js/sw.js 里的 CACHE_NAME 和资源列表版本号

替换头图方法
- 把你正式的 banner 图片替换 assets/hero-banner.jpg
- 如果文件名不变，不需要改 HTML
- 推荐尺寸：1044 × 252

排行榜图片
- 当前使用你提供的图一
- 文件路径：assets/ranking.webp

页面结构
1. 头图
2. Event Time
3. Event Details（含排行榜图片）
4. Rewards（一个大卡片，包含三档奖励）
5. WhatsApp 联系区域


更新说明
- 已替换为你最新上传的正式 banner 图
- banner 文件路径：assets/hero-banner.jpg
