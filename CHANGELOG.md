# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.1](https://github.com/baptiste-le-m/reqwest-vcr/compare/v0.3.0...v0.3.1) - 2026-03-02

### Added

- support both reqwest 0.12 and 0.13 via feature flags

### Fixed

- add reqwest with default-tls to dev-dependencies

### Other

- Remove default features from reqwest dependency
- Update README.md
- release v0.2.1

## [0.3.0](https://github.com/Gaelik-git/reqwest-vcr/releases/tag/v0.3.0) - 2025-03-20

### Other

- Set version to 0.3.0
- Adding Release plz
- Fork to reqwest-vcr
- Update deps versions
- Add Cargo.lock file
- Fix clippy issues for 0.2.1 release
- Bump version: 0.2.1
- Merge pull request #14 from amosjyng/easier-debug
- Use tracing instead of eprintln!, and add test
- Make debugging unmatched requests easier
- v0.1.5
- Add integration tests for request/response modifiers
- Cargo fmt
- Make VCRMode Clone
- Add feature: Filtering sensitive information
- Bump Cargo version: 0.1.4
- Rm unused import, cargo fmt
- Panic when cassette cannot be read
- Update record documentation
- Bump cargo version
- Implement ZIP compression for VCR files
- Bump cargo version
- Unpin chrono dependency
- Update crates badge
- Add crates.io badge
- Set publish=true
- Set package classifiers
- Implement VCRReplaySearch modes: SearchAll, SkipFound
- Fix tests running in ci
- Initial commit
