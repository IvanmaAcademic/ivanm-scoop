# ivanm-scoop

Personal Scoop bucket: 自维护工作流核心应用精选。

[![Tests](https://github.com/IvanmaAcademic/ivanm-scoop/actions/workflows/ci.yml/badge.svg)](https://github.com/IvanmaAcademic/ivanm-scoop/actions/workflows/ci.yml)
[![Excavator](https://github.com/IvanmaAcademic/ivanm-scoop/actions/workflows/excavator.yml/badge.svg)](https://github.com/IvanmaAcademic/ivanm-scoop/actions/workflows/excavator.yml)

收录原则:只放自己实际在用的、且官方大桶缺失或维护不佳的应用。版本由 Excavator 每 4 小时自动跟进。

## Apps

| App | 说明 |
| --- | --- |
| obsidian | 笔记 (extras 同步) |
| zotero | 文献管理 (extras 同步) |
| yazi | 终端文件管理器 (main 同步) |
| scoop-search | scoop 快速搜索 (main 同步) |
| pot-desktop | 划词翻译 (extras-cn 同步) |
| vscode-insiders-portable | VS Code Insiders 便携版 (自定义 manifest,数据持久化到 persist) |

## How do I install these manifests?

```pwsh
scoop bucket add ivanm-scoop https://github.com/IvanmaAcademic/ivanm-scoop
scoop install ivanm-scoop/<app>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
