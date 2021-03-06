# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Changed
- Upgraded build/test images to use Golang 1.13 instead of 1.11 ([#27](https://github.com/cyberark/summon-aws-secrets/issues/27))

## [0.4.0] - 2020-09-11
### Added
- Update aws-sdk-go to v1.34.20

## [0.3.0] - 2019-03-06
### Added
- Converted to go modules
- Added ability to use `#` as a delimiter for variable IDs

## [0.2.0] - 2018-08-30
### Added
- Fetch AWS config from ec2metadata if on an ec2 instance [PR#5](https://github.com/cyberark/summon-aws-secrets/pull/5)

## 0.1.0 - 2018-04-04
### Added
- Initial release

[Unreleased]: https://github.com/cyberark/conjur-api-go/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/cyberark/conjur-api-go/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/cyberark/conjur-api-go/compare/v0.1.0...v0.2.0
