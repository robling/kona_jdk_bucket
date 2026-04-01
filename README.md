# Kona JDK Scoop Bucket

[![Tests](https://github.com/robling/kona_jdk_bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/robling/kona_jdk_bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/robling/kona_jdk_bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/robling/kona_jdk_bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for [Tencent Kona JDK](https://github.com/Tencent) — Tencent's long-term-support distributions of OpenJDK for Windows.

## Available Packages

| Package | Version | Description |
|---------|---------|-------------|
| `konajdk8` | 8.0.25 | Tencent Kona JDK 8 (OpenJDK 8 LTS) |
| `konajdk11` | 11.0.30 | Tencent Kona JDK 11 (OpenJDK 11 LTS) |
| `konajdk17` | 17.0.18 | Tencent Kona JDK 17 (OpenJDK 17 LTS) |

## How do I install these packages?

```pwsh
scoop bucket add kona_jdk https://github.com/robling/kona_jdk_bucket
scoop install kona_jdk/konajdk17
```

Or install a specific version:

```pwsh
scoop install kona_jdk/konajdk8
scoop install kona_jdk/konajdk11
scoop install kona_jdk/konajdk17
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
