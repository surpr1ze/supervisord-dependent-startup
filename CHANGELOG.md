# Changelog

## [1.0.0](https://github.com/bendikro/supervisord-dependent-startup/releases/tag/v1.0.0) - _2018-01-03_
[Commit history](https://github.com/bendikro/supervisord-dependent-startup/compare/54e32080e673f1548c5d97ed483805d63754656a...v1.0.0)

#### Initial release of supervisord_dependent_startup
The plugin code is based on [ordered-startup-supervisord](https://github.com/jasoncorbett/ordered-startup-supervisord/)

### Added
- Support for starting supervisor services after given services reaches certain states
- Unit tests
- Command line arguments parsing with argparse