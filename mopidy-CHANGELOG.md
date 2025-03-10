# Change log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.4.4] - 2022-02-19
### Fixed
- change of code for 2022.6 warning introduced issue where an int was added to a string.

## [1.4.3] - 2022-01-07
### Fixed
- git version tag added before last PR

## [1.4.2] - 2022-01-03
- mopidy play instruction is slow on streming media. now waiting for status to change into `playing` asynchronously
- update code to comply with 2022.6 deprecation (thanks, [VDRainer](https://github.com/VDRainer))

## [1.4.1] - 2021-05-23
### Changed
- bugfix: snapshot and restore player state (thanks [AdmiralStipe](https://community.home-assistant.io/u/AdmiralStipe))
- better messages when device detected through zeroconf is not a mopidy server
- formatting (pylint, pep8, pydocstyle)
- fix zeroconf issues on docker (thanks, [@guix77](https://github.com/guix77))
- set name to zeroconf name and port

## [1.4.0] - 2021-04-05
### Changed
- fixed issue with logging on detected non-mopidy zeroconf http devices
- added service `search`
- change service targetting
- sort the sourcelist
- modifications to pass tests to add to core

## [1.3.2] - 2021-03-14
### Changed
- refactored media library routines
- provide home assistant logger to MopidyAPI

## [1.3.1] - 2021-03-13
### Changed
- fixed issue with snapshot/restore track index

## [1.3.0] - 2021-03-12
### Added
- snapshot service
- restore service
- dutch translation
- french translation

### Changed
- fixed typo in english translation

## [1.2.0] - 2021-03-08
### Added
- Support for zeroconf discovery

## [1.1.4] - 2021-03-06
### Changed
- Handle connection errors in a better way

## [1.1.3] - 2021-03-06
### Changed
- uids based on hostname and port number instead of hostname only, thenks @Burningstone91

