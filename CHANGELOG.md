# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## Unreleased

### Added

- Documentation: Added Book
- Type System: Added JSON schema identifier to all types

### Changed

- Refactored into new mono repo `reactive-graph/net`
- Moved plugins http and git from `reactive-graph/std` -> `reactive-graph/net`
- Prefix plugins with `net` (e.g. `libreactive_graph_net_http`)
- Refactored usages of `net` to its new namespace
- Configure lints on workspace level
- Replaced lazy_static with LazyLock

### Fixed

### Distribution

- CI: Release plugins on GitHub Releases
- CI: Update rust nightly toolchain to nightly-2025-08-05

### Infrastructure

- CI: Synchronize labels from config file
- CI: Automatically merge successful dependabot PR's
