# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [1.0.0] - 2015-11-09
### Added
- Configuration property to plugins arguments
- Ability to specify file paths manually that are external to the files array
- Tests to cover external file / normalized path variations

### Changed
- Split arguments object into two properties: files / config -- files now need
  to be part of the "files" property rather than passed directly.

## [0.0.1] - 2014-05-31
### Added
- Plugin allows you to add metadata to the global object from json/yaml files
  in the Metalsmith files array
