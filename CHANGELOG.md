# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html)

## [v1.1.1]
### Fixed
- :bug: fix wrong latest version in changelog

## [v1.1.0]
### Added
- :white_check_mark: remove some directories from coveralls ignore

I need to write proper tests/mocks for this instead of ignoring and faking
the coveralls
- :construction_worker: update ci config
- :white_check_mark: Added tests after changelogs
- :construction: Add Changelog generation, no tests for now
- :art: move migration instructions to a separate doc
- :sparkles: update ok monad definition and usage
- :sparkles: move code in repo
- :sparkles: update code a bit
- :art: apply mix format to the repo

### Uncategorised
- :clap: Bump version to 1.1.0

## [v1.0.0]
### Added
- :sparkles: Refactor hook running, make git_cli optional dependency
- :sparkles: update how config works

Macros are cleaned up,
Git config values are now in their separate namespace.

### Uncategorised
- :pencil: update docs for config module
- :clap: Bump version to 1.0.0

## [v0.2.1]
### Uncategorised
- :pencil: Update readme a little
- :clap: Bump version to 0.2.1

## [v0.2.0]
### Added
- :white_check_mark: update coveralls config

as some things wont be covered with tests
- :sparkles: Added basics of git hooks, updated config
- :white_check_mark: Add tests for `mix bump` task
- :construction_worker: add some ignores to coverage
- :white_check_mark: add tests for Versioce.Bumper
- :construction_worker: add coverage
- :art: Add badges to README
- :construction_worker: add ci to project

### Fixed
- :bug: fix post hook in config

### Uncategorised
- ✅ Add tests for Inspect hooks
- :clap: Bump version to 0.2.0

## [v0.1.1]
### Added
- :art: Clean up html doc generation

### Fixed
- :bug: Make a proper working defaults

### Uncategorised
- :clap: Bump version to 0.1.1

## [v0.1.0]
### Added
- :sparkles: make docs even better
- :sparkles: allow ignoring hooks in bump task
- :sparkles: add simple test for bump.version task
- :sparkles: add behaviours for hooks
- :sparkles: update docs

### Uncategorised
- :clap: Bump version to 0.1.0

## [v0.0.2]
### Added
- :sparkles: Get ready for publishing on hex

### Uncategorised
- :clap: Bump version to 0.0.2

## [v0.0.1]
### Added
- :sparkles: add main machinery for bumping
- :sparkles: Make a skeleton for the project
- :sparkles: make a proper readme first
- :bulb: Initial commit

### Uncategorised
- :clap: Bump version to 0.0.1

[v1.1.1]: https://github.com/mpanarin/versioce/compare/v1.1.0...v1.1.1
[v1.1.0]: https://github.com/mpanarin/versioce/compare/v1.0.0...v1.1.0
[v1.0.0]: https://github.com/mpanarin/versioce/compare/v0.2.1...v1.0.0
[v0.2.1]: https://github.com/mpanarin/versioce/compare/v0.2.0...v0.2.1
[v0.2.0]: https://github.com/mpanarin/versioce/compare/v0.1.1...v0.2.0
[v0.1.1]: https://github.com/mpanarin/versioce/compare/v0.1.0...v0.1.1
[v0.1.0]: https://github.com/mpanarin/versioce/compare/v0.0.2...v0.1.0
[v0.0.2]: https://github.com/mpanarin/versioce/compare/v0.0.1...v0.0.2
[v0.0.1]: https://github.com/mpanarin/versioce/compare/b1906a8872637a871ebf46ff5fb0b52b020e8879...v0.0.1