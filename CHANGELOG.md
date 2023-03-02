# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Fixed
- Do not close the physical channel on `closePhysicalChannel()` method because in the case of an HSM plugin
  the physical channels are managed by the reader allocation and de-allocation processes.

## [2.0.1] - 2022-10-04
### Added
- `CHANGELOG.md` file (issue [#19]).
- CI: Forbid the publication of a version already released (issue [#17]).
### Changed
- More accurate logging.
### Upgraded
- "Keyple Util Library" to version `2.2.0`
### Upgraded examples
- "Calypsonet Terminal Calypso API" to version `1.2.+`
- "Keyple Service Library" to version `2.1.0`
- "Keyple Service Resource Library" to version `2.0.2`
- "Keyple Card Calypso Library" to version `2.2.1`
- "Keyple Plugin PCSC Library" to version `2.1.0`
### CI
- Automation of the right to execute (x) shell scripts.

## [2.0.0] - 2021-10-07
### Changed
- Upgrade the component to comply with the new internal APIs of Keyple 2.0

## [0.8.1] - 2020-05-14
This is the initial release.

[unreleased]: https://github.com/calypsonet/keyple-plugin-cna-spirtech-hsm-java-lib/compare/2.0.1...HEAD
[2.0.1]: https://github.com/calypsonet/keyple-plugin-cna-spirtech-hsm-java-lib/compare/2.0.0...2.0.1
[2.0.0]: https://github.com/calypsonet/keyple-plugin-cna-spirtech-hsm-java-lib/compare/0.8.1...2.0.0
[0.8.1]: https://github.com/calypsonet/keyple-plugin-cna-spirtech-hsm-java-lib/releases/tag/0.8.1

[#19]: https://github.com/calypsonet/keyple-plugin-cna-spirtech-hsm-java-lib/issues/19
[#17]: https://github.com/calypsonet/keyple-plugin-cna-spirtech-hsm-java-lib/issues/17