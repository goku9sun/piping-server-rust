# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)

## [Unreleased]

## [0.2.2] - 2019-07-28
### Changed
* Generalize ReceiverResBody as FinishDetectableBody

## [0.2.1] - 2019-07-28
### Fixed
* Not close sender's connection when transferring throw Caddy reverse proxy

## [0.2.0] - 2019-07-27
### Changed
* Use req-res handler like Node.js
* Return non-2xx status codes when rejecting

## 0.1.0 - 2019-07-17
### Added
* Implement basic Piping Server

[Unreleased]: https://github.com/nwtgck/piping-server-rust/compare/v0.2.2...HEAD
[0.2.2]: https://github.com/nwtgck/piping-server-rust/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/nwtgck/piping-server-rust/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/nwtgck/piping-server-rust/compare/v0.1.0...v0.2.0