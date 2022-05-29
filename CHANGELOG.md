# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [1.0.4] - 2022-01-27
### Fixed
* Fix issue in .NET versions earlier than 5.0, when creating large glossaries or
 translating texts larger than 64 KiB.


## [1.0.3] - 2022-01-19
### Added
* Add contribution guidelines -- currently we are unable to accept Pull Requests.
### Changed
* Improve README tests section.


## [1.0.2] - 2022-01-03
### Changed
- Include additional information with error status codes.


## [1.0.1] - 2021-12-07
### Fixed
- Use default HTTP version in requests rather than always using HTTP/2.


## [1.0.0] - 2021-11-18
### Changed
- Add missing properties in package, e.g. icon.
- Introduce GlossaryEntries class to encapsulate glossary entries.
- SplitSentences enum renamed to SentenceSplittingMode.
- Exceptions thrown by some functions were changed to use standard exceptions.
- Improvements to tests, README and documentation.


## [0.1.0] - 2021-11-05
Initial release.


[1.0.4]: https://github.com/DeepLcom/deepl-dotnet/compare/v1.0.3..v1.0.4
[1.0.3]: https://github.com/DeepLcom/deepl-dotnet/compare/v1.0.2..v1.0.3
[1.0.2]: https://github.com/DeepLcom/deepl-dotnet/compare/v1.0.1..v1.0.2
[1.0.1]: https://github.com/DeepLcom/deepl-dotnet/compare/v1.0.0..v1.0.1
[1.0.0]: https://github.com/DeepLcom/deepl-dotnet/compare/v0.1.0...v1.0.0
[0.1.0]: https://github.com/DeepLcom/deepl-dotnet/releases/tag/v0.1.0
