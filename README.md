# Boomerang

A boomerang file is compiled and published to an s3 bucket.

## Setup

**Grunt**

Boomerang uses `grunt-cli` for building a boomerang file for ingestion.

```
$ <npm | pnpm> i grunt-cli
```

## Build

```
$ grunt clean build
```

## Plugins

Boomerang uses different plugs for measurement. You can add or see the current ones in [`plugins.json`](./plugins.json)

[**Original Boomerang Readme**](./Boomerang.md)
