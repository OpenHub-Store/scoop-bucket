# Komi Store Scoop Bucket

[![Tests](https://github.com/kurikomi-labs/komi-store-scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/kurikomi-labs/komi-store-scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/kurikomi-labs/komi-store-scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/kurikomi-labs/komi-store-scoop-bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for [Komi Store](https://komistore.app) — a cross-platform app store for GitHub, Codeberg and Forgejo releases, by [Kurikomi](https://github.com/kurikomi-labs).

## Install

```pwsh
scoop bucket add komi-store https://github.com/kurikomi-labs/komi-store-scoop-bucket
scoop install komi-store
```

## Update

```pwsh
scoop update komi-store
```

The bundled Windows portable build (launcher + JRE) is installed; no system installer runs.
