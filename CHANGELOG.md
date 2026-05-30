# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Operational independence with graceful degradation when sister services are unavailable
- ASBB budget query integration (Phase 3B) for budget-aware decision making
- GoReleaser automation for consistent cross-platform releases
- CI workflow and project status/quality badges

### Changed
- Documentation updated for the complete three-project ecosystem (ASBA / ASBX / ASBB)

## [0.3.0] - 2025-09-13

### Added
- **Phase 2 — Sister Project Integration & Intelligence Engine**: execution-plan
  generation for the ASBX (`aws-slurm-burst`) plugin, research-domain detection,
  and MPI communication-pattern optimization
- Roadmap and documentation for `aws-slurm-burst` integration

## [0.1.0] - 2025-09-13

### Added
- **Phase 1 — Historical job analysis and resource optimization**: personal job
  history (SQLite), CPU/memory efficiency analysis, AWS instance intelligence
- Real-time queue analysis, live AWS pricing, and local cost modeling
- Batch-script (`sbatch`) parsing and multiple input methods
- MIT License (Copyright 2025 Scott Friedman) and academic-research-focused docs

[Unreleased]: https://github.com/scttfrdmn/aws-slurm-burst-advisor/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/scttfrdmn/aws-slurm-burst-advisor/compare/v0.1.0...v0.3.0
[0.1.0]: https://github.com/scttfrdmn/aws-slurm-burst-advisor/releases/tag/v0.1.0
