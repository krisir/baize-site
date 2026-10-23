# baize-site

白泽（Baize Agent）的项目主页与助手示例页。

- 主页：`index.html`
- 助手示例：`examples.html`
- 样式：`assets/style.css`（无外部依赖、无 CDN、支持深色模式）
- 部署：推送到 `main` 后由 `.github/workflows/pages.yml` 发布到 GitHub Pages

## 这个仓库的来源

源文件维护在 `baize-agent` 的 `site/` 目录（应用源码仓库保持私有）。修改流程：

```bash
# 在 baize-agent 仓库里改 site/ 下的文件，然后：
scripts/publish-site.sh          # 同步到本站点仓库并推送
```

不要直接在本仓库手改，下次同步会被覆盖。
