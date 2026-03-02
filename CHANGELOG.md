# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1] - 2026-03-02

### Fixed
- Resolved mypy type annotation errors across the codebase
- Fixed ruff f-string formatting warnings
- Added `from __future__ import annotations` for forward-compatible type hints

### Changed
- CI workflow now passes all lint and type checks cleanly
- Published to PyPI as `suy-sideguy`

## [0.1.0] - 2026-03-02

### Added
- Initial release of Suy Sideguy
- Runtime process, file, and network monitoring via `psutil`
- YAML-based policy engine with SAFE / FLAGGED / KILLED verdicts
- `suy-warden` CLI entrypoint for live agent monitoring
- `suy-forensic-report` CLI for post-incident forensic reports
- PID and process-name targeting modes
- Evidence logging (JSONL actions log + JSON incident files)
- Example scope policies (`scope.openclaw.yaml`, `scope.low-disruption.yaml`)
- Audit checklist and layered implementation plan
- Test suite with pytest
- CI and publish GitHub Actions workflows
- Security disclosure policy (`SECURITY.md`)
- Contributing guide and Code of Conduct

[0.1.1]: https://github.com/roli-lpci/suy-sideguy/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/roli-lpci/suy-sideguy/releases/tag/v0.1.0
