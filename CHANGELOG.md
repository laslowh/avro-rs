# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.0] - 2018-05-29
### Changed
- Move from string as errors to custom fail types

### Fixed
- Avoid reading the first item over and over in Reader

## [0.2.0] - 2018-05-22
### Added
- `from_avro_datum` to decode Avro-encoded bytes into a `Value`
- Documentation for `from_value`

## [0.1.1] - 2018-05-16
- Initial release
