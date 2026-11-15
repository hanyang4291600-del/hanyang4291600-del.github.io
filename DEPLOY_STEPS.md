# 补齐包部署说明（覆盖 push 即可）

> 生成 2026-11-15 · 内容层 8 页 + 合并版 llms.txt / sitemap.xml
> **不动**你已上线的 index.html / index.md / robots.txt / CNAME

## 文件清单
- faq.html（+ .md）          常见问题与口径说明
- methodology.html（+ .md）   方法与口径
- answers/index.html（+ .md） 24 条封存问句索引
- answers/a1~d1-*.html（+ .md）4 篇答案型内容（每篇带一手来源链接）
- llms.txt                    合并版：Pages 节 = 内容层 7 条；Optional 节 = 你的 index.md + 各页镜像
- sitemap.xml                 合并版：首页 + 7 条内容层 URL
- DEPLOY_STEPS.md             本文件（可不上传）

## 操作（在你的 GitHub Pages 仓库）
```bash
# 把本目录内容（除本文件）复制进仓库根目录后：
git add -A
git commit -m "add GEO content layer: faq/methodology/answers + llms/sitemap merge"
git push
```

## 上线后验证（3 分钟）
1. 浏览器打开 https://hanyang4291600-del.github.io/llms.txt —— 应看到 Pages 节 7 条链接
2. 打开 https://hanyang4291600-del.github.io/sitemap.xml —— 应有 8 个 URL
3. 打开任意一篇 https://hanyang4291600-del.github.io/answers/a1-ai-agent-training.html —— 无 { 残留

## 待韩拍板（不阻塞上线）
1. llms.txt / index.md 里「服务 50 座油企」「8 期×15 人」「近百座油站使用」——能兜底就保留；
   「近百座」建议改为可兜底数字（如「约 90 座」）或删掉模糊量词，AI 引用时会把模糊变精确。
2. 营业执照全称：我这边一直没有。schema 里已按 fail-closed 不写 legalName；
   你给我全称后我 5 分钟补上（对信任度有帮助）。
