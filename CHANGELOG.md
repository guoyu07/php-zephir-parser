# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Changed
- Improved install script to use specific optimizations for gcc and add ability to install on Gentoo and macOS

## 1.0.1 - 2017-03-31
### Added
- Added script to build development version (Linux)
- Added ability to compile extension for PHP 7 (Windows)
- Added Windows manual (Windows)

### Changed
- Optimize build to produce smaller module
- Improved Win32 build by providing separated `bat` file  (Windows)
- Improved build and tests on Appveyor  (Windows)

### Fixed
- Fixed compiler warnings on build lemon
- Removing unused structures
- Removing unused variables

## 1.0.0 - 2017-03-26
### Added
 - Initial stable release
