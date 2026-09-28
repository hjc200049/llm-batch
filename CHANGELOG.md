# Changelog

All notable changes are documented here.
Format follows keepachangelog.com, versions are semver-ish.

## [0.2.0] - 2026-07-25

### Fixed
- off-by-one in the summary counter
- crash on paths containing spaces

### Changed
- faster directory walking, fewer syscalls

## [0.1.0] - 2026-06-08

### Added
- real rate limiting: sliding windows on requests/min and tokens/min
