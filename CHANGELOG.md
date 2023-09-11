# changelog

[![Keep a Changelog](https://img.shields.io/badge/Keep%20a%20Changelog-1.0.0-informational)](https://keepachangelog.com/en/1.0.0/)
[![Semantic Versioning](https://img.shields.io/badge/Sematic%20Versioning-2.0.0-informational)](https://semver.org/spec/v2.0.0.html)
![clq validated](https://img.shields.io/badge/clq-validated-success)

Keep the newest entry at top, format date according to ISO 8601: `YYYY-MM-DD`.

Categories, defined in [changemap.json](.github/clq/changemap.json)):

- *major* release trigger:
   - `Changed` for changes in existing functionality.
   - `Removed` for now removed features.
- *minor* release trigger:
   - `Added` for new features.
   - `Deprecated` for soon-to-be removed features.
- *bug-fix* release trigger:
   - `Fixed` for any bug fixes.
   - `Security` in case of vulnerabilities.

## [1.0.1] - 2023-09-11

### Fixed

- Bump actions/checkout from v3 to v4

## [1.0.0] - 2023-07-09

### Added

- CI
- emits csv with repository name, size and size per language
