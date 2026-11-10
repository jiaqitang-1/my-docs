# 使用指南

1. 在 `docs/` 中修改对应页面。如果增删页面，同步检查 `mkdocs.yml` 中的导航配置。
2. 在仓库根目录运行严格构建，检查是否有失效链接或配置警告。
3. 启动本地预览，点击导航检查四个页面。
4. 将文档修改提交并推送到 `main`。
5. 在仓库的 Actions 页面确认构建和部署成功，再打开公开网站核对更新。

## 常用命令

在装好依赖的 Python 环境中运行：

```powershell
python -m mkdocs build --strict
python -m mkdocs serve
```

打开终端显示的预览地址。检查完成后，按 `Ctrl+C` 停止预览。
