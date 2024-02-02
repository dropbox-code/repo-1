<!-- trunk-ignore-all(markdownlint/MD024) -->

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres
to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

<!-- ### Added -->

### Changed

- Trunk Upgrade CI job is now compliant with commitlint.
- Disable issue MD024 in changelog.

<!-- ### Deprecated -->

### Removed

- Enforce Changelog CI job won't run on push because it's not supported.

### Fixed

- Go version discrepancy in CodeQL CI job.

<!-- ### Security -->

## [0.1.0] - 2024-02-01

### Added

- `selproj` utility for selecting a project from a list of projects, moved from
  [aiven/terraform-provider-aiven](https://github.com/aiven/terraform-provider-aiven).
- CI pipeline for running tests and linting.
- `CODEOWNERS` file for defining code owners.
- `.gitignore` file for ignoring files and directories.

### Changed

- Docs of the repository, Cf. [aiven/aiven-public](https://github.com/aiven/aiven-public).

[unreleased]: https://github.com/aiven/go-utils/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/aiven/go-utils/releases/tag/v0.1.0
