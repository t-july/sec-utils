# Changelog
All notable changes to this project will be documented in this file.

## [0.0.3] - 2019-09-29
### Added
- Added ability to define run through yaml config object
- Added method `secutils.utils.generate_config` to generate sample config file
### Bug Fixes
- Removed pickling of SECContainer - logging is written to file
- Fixed progress bar updating when downloading files

[0.0.3]: https://github.com/datawrestler/sec-utils/releases/tag/v0.0.3

## [0.0.2] - 2019-09-22
### Added
- Minor refactoring of package import and documentation names

[0.0.2]: https://github.com/datawrestler/sec-utils/releases/tag/v0.0.2

## [0.0.1] - 2019-09-22
### Added
- Added Multi-threaded downloading
- Added Caching of index files
- Added Automatic directory structure buildout (i.e. downloading multiple file types w/dir structure: ftype --> year --> quarter --> files)
- Added Resume downloading
- Added Built in logging and download success tracker
- Added README, CHANGELOG, CONTRIBUTE

[0.0.1]: https://github.com/datawrestler/sec-utils/releases/tag/v0.0.1