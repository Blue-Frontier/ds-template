# ds-template

Blue-Frontier 组织文档 / Issue / PR 模板 **单一真相源（SSOT）**。

## 三位一体

| 仓库 | 职责 | 地址 |
|------|------|------|
| **ds-core** | 内核 | https://github.com/Blue-Frontier/ds-core |
| **ds-cli** | CLI | https://github.com/Blue-Frontier/ds-cli |
| **ds-gui**（后续） | GUI | https://github.com/Blue-Frontier/ds-gui |
| **ds-template**（本仓） | 模板 SSOT | https://github.com/Blue-Frontier/ds-template |
| 历史 monorepo | 只读参考 | https://github.com/docmirror/dev-sidecar |

## 同步方式

1. **推荐**：将本仓内容同步到组织默认仓 [Blue-Frontier/.github](https://github.com/Blue-Frontier/.github)（若存在），使未自带模板的仓库自动继承。
2. 或在各业务仓用 workflow 从本仓 `main` 复制 `ISSUE_TEMPLATE/`、`PULL_REQUEST_TEMPLATE.md`。

页脚标识：`<!-- ssot: Blue-Frontier/ds-template -->`

## 内容

- `ISSUE_TEMPLATE/` — Bug 等 issue 模板（含三仓归属勾选）
- `PULL_REQUEST_TEMPLATE.md` — PR 模板（含 submodule / tag 检查项）
