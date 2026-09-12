# docuum

[中文版本](./README.cn.md)

Docuum performs least recently used (LRU) eviction of Docker images. 🗑️

![docuum](https://repo.x-cmd.io/docuum.svg)

## Install

```sh
x install docuum
```

## Code insight

Total: **1,974** lines of code across **11** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Rust | 1,514 | 201 | 237 | 4 |
| Yaml | 260 | 40 | 19 | 3 |
| Sh | 156 | 69 | 41 | 2 |
| Toml | 35 | 0 | 4 | 1 |
| Dockerfile | 9 | 7 | 5 | 1 |

## OpenSSF Scorecard

Overall score: **4.1 / 10**

Lowest-scoring checks:

- **Code-Review** (0/10) — Found 1/30 approved changesets -- score normalized to 0
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## Source

- **Upstream**: <https://github.com/stepchowfun/docuum>
- **License**: NOASSERTION

## Release

- **Latest**: `v0.27.1` (2026-09-02)
- **Last commit**: 2026-09-02
- **Assets in release**: 8

## Popularity

- **Stars**: 709 · **Forks**: 43 · **Open issues**: 55 · **Contributors**: 21

## Totals (cumulative)

- **Releases**: 51 · **Merged PRs**: 343 · **Open PRs**: 0 · **Closed issues**: 43 · **Open issues**: 12 · **Commits**: 754

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 1 | 7 | 0 | 0 | 0 | 7 |
| last60d | 2026-07-14 | 1 | 18 | 0 | 0 | 0 | 18 |
| 90d | 2026-06-14 | 1 | 36 | 0 | 0 | 0 | 36 |
| last180d | 2026-03-16 | 2 | 49 | 0 | 1 | 0 | 56 |
| 360d | 2025-09-17 | 5 | 61 | 0 | 3 | 1 | 69 |
| last720d | 2024-09-22 | 5 | 79 | 0 | 5 | 3 | 131 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [docuum-aarch64-apple-darwin](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-aarch64-apple-darwin) | 2.9 MiB | `native/darwin/arm64` |
| [docuum-aarch64-pc-windows-msvc.exe](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-aarch64-pc-windows-msvc.exe) | 2.2 MiB | `native/win/arm64` |
| [docuum-aarch64-unknown-linux-gnu](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-aarch64-unknown-linux-gnu) | 3.4 MiB | `native/linux/arm64/glibc` |
| [docuum-aarch64-unknown-linux-musl](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-aarch64-unknown-linux-musl) | 3.4 MiB | `native/linux/arm64/musl` |
| [docuum-x86_64-apple-darwin](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-x86_64-apple-darwin) | 3.0 MiB | `native/darwin/x64` |
| [docuum-x86_64-pc-windows-msvc.exe](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-x86_64-pc-windows-msvc.exe) | 2.6 MiB | `native/win/x64` |
| [docuum-x86_64-unknown-linux-gnu](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-x86_64-unknown-linux-gnu) | 3.4 MiB | `native/linux/x64/glibc` |
| [docuum-x86_64-unknown-linux-musl](https://github.com/stepchowfun/docuum/releases/download/v0.27.1/docuum-x86_64-unknown-linux-musl) | 3.6 MiB | `native/linux/x64/musl` |

## Distribution status

Reported by **26** distros on [repology.org](https://repology.org/project/docuum). **2** are ✅ on the latest upstream release, **24** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `0.27.1` | ✅ latest |
| Nix unstable | `0.27.1` | ✅ latest |
| Alpine edge | `0.26.0` | ⚠️ outdated |

## Improve this data

Install metadata for docuum lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `docuum` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/docuum.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260912.yml` · 2026-09-12T05:51:12Z._
