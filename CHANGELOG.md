# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.1.1] - 2020-04-24
### Fixed
- Correct version number in wp-fe-sanitize-title.js

## [1.1.0] - 2020-04-24
### Added
- Add code to handle HTML entities (e.g. &nbsp; or &reg;)

## [1.0.4] - 2020-04-24
### Fixed
- Non-breaking spaces are now properly encoded as dashes (-).

## [1.0.3] - 2020-02-28
### Fixed
- Bumped versions of assets being loaded in order to properly cache bust

## [1.0.2] - 2020-02-28
### Added
- Added .editorconfig for coding standard consistency. See #9
- Added version number to wp-fe-sanitize-title.js
### Fixed
- Fixed issue with en dashes and em dashes not being properly encoded. See #8

## [1.0.1] - 2019-11-29
### Added
- Added CHANGELOG.md
### Fixed
- Fixed error where period (.) and forward slash (/) were wrongly stripped, instead of encoded as dashes (-)

## [1.0.0] - 2017-09-07
### Added
- Initial Release
