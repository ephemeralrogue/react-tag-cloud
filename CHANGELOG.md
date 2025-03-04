# react-tag-cloud ☁️

Create beautiful tag/word clouds using React.

## [Unreleased]

### Overhaul

- removed yarn
- added pnpm
- moved example directory into separate project
- updated all dependencies
- replaced tslint with eslint
- added linting and security checks workflows
- added changesets for future publishing workflow
- moved repo docs into .github directory
- linting passes with warnings
- workflows yamls pass KICS
- build completes with no errors

## [1.3.2] - 2019-03-20

### Fixed

- Fixed default import error when using TypeScript

## [1.3.1] - 2019-03-13

### Added

- Updated the code to TypeScript and added typescript type definitions

### Fixed

- Fixed initial 100ms delay before the tag-cloud is shown
- Removed use of the deprecated `componentWillReceiveProps` lifecycle method

### Changed

- Updated to latest react-measure@2.2.4 package

## [1.2.0] - 2018-09-10

### Added

- Added support for older browsers (css transforms, thanks @engmagdy87)

### Changed

- Updated to latest react-measure@2.1.2 package
- Updated to latest d3-cloud@1.2.5 package
