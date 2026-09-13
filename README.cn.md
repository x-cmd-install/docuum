# docuum

[English version](./README.md)

Docuum performs least recently used (LRU) eviction of Docker images. 🗑️

![docuum](https://repo.x-cmd.io/docuum.svg?lang=zh)

## 安装

```sh
x install docuum
```

## 代码洞察

合计: **1,974** 行代码（覆盖前 5 种语言、共 **11** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Rust | 1,514 | 201 | 237 | 4 |
| Yaml | 260 | 40 | 19 | 3 |
| Sh | 156 | 69 | 41 | 2 |
| Toml | 35 | 0 | 4 | 1 |
| Dockerfile | 9 | 7 | 5 | 1 |

## OpenSSF Scorecard 评分

总评分: **4.1 / 10**

评分最低的几项:

- **Code-Review** (0/10) — Found 1/30 approved changesets -- score normalized to 0
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## 源代码

- **上游仓库**: <https://github.com/stepchowfun/docuum>
- **许可证**: NOASSERTION

## 发布

- **最新版本**: `v0.27.1` (2026-09-02)
- **最近提交**: 2026-09-02
- **Release 含资产**: 8 个

## 流行度

- **Star**: 709 · **Fork**: 43 · **开放 issue**: 55 · **贡献者**: 21

## 累计统计

- **发布数**: 51 · **已合并 PR**: 343 · **开放 PR**: 0 · **已关闭 issue**: 43 · **开放 issue**: 12 · **提交数**: 754

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-14 | 1 | 7 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-15 | 1 | 18 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-15 | 1 | 36 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-17 | 2 | 49 | 0 | 1 | 0 | 0 |
| 360d | 2025-09-18 | 5 | 61 | 0 | 3 | 1 | 0 |
| last720d | 2024-09-23 | 5 | 79 | 0 | 5 | 3 | 131 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [docuum-aarch64-apple-darwin](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-aarch64-apple-darwin) | 2.9 MiB | `native/darwin/arm64` |
| [docuum-aarch64-pc-windows-msvc.exe](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-aarch64-pc-windows-msvc.exe) | 2.2 MiB | `native/win/arm64` |
| [docuum-aarch64-unknown-linux-gnu](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-aarch64-unknown-linux-gnu) | 3.4 MiB | `native/linux/arm64/glibc` |
| [docuum-aarch64-unknown-linux-musl](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-aarch64-unknown-linux-musl) | 3.4 MiB | `native/linux/arm64/musl` |
| [docuum-x86_64-apple-darwin](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-x86_64-apple-darwin) | 3.0 MiB | `native/darwin/x64` |
| [docuum-x86_64-pc-windows-msvc.exe](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-x86_64-pc-windows-msvc.exe) | 2.6 MiB | `native/win/x64` |
| [docuum-x86_64-unknown-linux-gnu](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-x86_64-unknown-linux-gnu) | 3.4 MiB | `native/linux/x64/glibc` |
| [docuum-x86_64-unknown-linux-musl](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-x86_64-unknown-linux-musl) | 3.6 MiB | `native/linux/x64/musl` |

## 发行版状态

在 [repology.org](https://repology.org/project/docuum) 上共有 **26** 个发行版报告此项目。**2** 个 ✅ 已是最新上游版本，**24** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Homebrew | `0.27.1` | ✅ latest |
| Nix unstable | `0.27.1` | ✅ latest |
| Alpine edge | `0.26.0` | ⚠️ outdated |

## 改进这些数据

docuum 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `docuum` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/docuum.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260913.yml` · 2026-09-13T06:06:13Z._
