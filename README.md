# C++ 笔记汇总

本仓库收集了作者的 C++ 学习笔记与书籍摘录（Markdown 格式），便于阅读、检索与长期保存。

## 仓库概览
仓库中主要的文件/目录（按当前结构列举）：

- `C++-Primer/` - 《C++ Primer》相关笔记（章节化的 Markdown 文件与图片资源）。
- `Effective-Modern-C++/` - 《Effective Modern C++》摘录与笔记。
- `Modern-Cpp-templates-tutorial/` - 现代 C++ 模板教程笔记。
- `Pre-knowledge/` - 先修知识与基础概念汇总。
- `assets/`、子目录下的图片资源等。

（仓库中以 Markdown 为主，包含大量配图，目录可能随时间更新。）

## 如何查看
- 推荐使用 Visual Studio Code 打开仓库，然后在编辑器中使用 Markdown 预览（Windows 下快捷键：`Ctrl+Shift+V`），或右键选择“在侧边打开预览”。
- 本地将 Markdown 转成 PDF/HTML（可选，需安装 pandoc）：

```powershell
# 安装 pandoc（若未安装）请根据系统去官网下载并安装
# 将某个章节目录（例如 C++-Primer）下的 md 合并为单个 PDF（示例）
pandoc -s -o C++-Primer.pdf .\C++-Primer\*.md
```

- 若需要网站式浏览，可使用诸如 MkDocs、Jekyll 或 Docsify 将本仓库构建成静态站点（需额外配置）。

## 贡献与使用指南
- 本仓库为个人学习笔记。欢迎提交改进、校正或补充的 PR。
- 请保持 Markdown 的可读性，图片放在 `assets/` 或各章节对应的 `assets/` 目录中，引用相对路径。
- 若要大量重构或自动化生成文档，请先在 issue 中简要说明目的与变更计划。

## 目录结构示例
```
C++-Primer/
  01_泛型算法.md
  02_关联容器.md
  ...
Effective-Modern-C++/
  CHAPTER_1_Deducing Types.md
  ...
Modern-Cpp-templates-tutorial/
  01_函数模板.md
  ...
Pre-knowledge/
  01_Element-knowledge.md
  ...
assets/ (共享图片资源)
```

## 建议的后续改进
- 添加 `LICENSE` 文件以明确许可。 
- 增加一个顶层的 `SUMMARY.md` 或 `toc.md`（目录索引），方便生成电子书或侧边导航。
- 若希望对外发布为静态文档站点，可添加 `mkdocs.yml` 并配置 CI 自动部署。

## 联系
在仓库内提交 Issue 或 PR 即可。

---

