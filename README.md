# zhangzhongze 的技术博客

个人技术博客，基于 [Astro](https://astro.build) + [Fuwari](https://github.com/saicaca/fuwari) 主题。

- 域名: `zhangzhongze.pages.dev`（Cloudflare Pages 免费子域，跑通后切换付费域名）
- 内容分类: 智能照明与嵌入式 / 量化与数据 / AI 工程 / 独立站与出海 / 学习与备考

## 本地开发

```bash
pnpm install
pnpm dev        # 本地预览 http://localhost:4321
pnpm build      # 构建到 dist/（含搜索索引）
```

## 发布流程

`git push` → Cloudflare Pages 自动构建部署。

## ⚠️ 内容红线（必须遵守）

- 公司（爱普华顿）相关内容一律不写：不写客户、不写内部数据、不写未公开产品参数
- 只写：行业通用方法论 + 公开标准（IEC/GB）+ 自己业余项目（量化/嵌入式学习/Mojin/SceneCraft）
- 量化文章：写方法不写实盘金额（百分比表达）
- 所有文章个人身份署名，不署公司

## 文章规范

- frontmatter: `title / date / tags / series(可选) / draft(草稿) / description(SEO)`
- 新文章: `pnpm new-post "文章标题"`（生成带模板的 md）

## 致谢

主题模板: [saicaca/fuwari](https://github.com/saicaca/fuwari)（MIT License）
