# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Support for grabbing the content of widgets as a picture

### Changed
- Refactor model/view related classes (moved/renamed several methods)

### Fixed
- Random failures of ComboBox.model_items()

## [1.1.5] - 2018-12-06
### Added
- Support for macOS
- Custom host for funq server
- Trigger QAction
- Enable middle/right click
- Build system support for multiple platforms and Qt versions

### Changed
- Functional app from python, PySide or PyQt to Qt and C++
- Documentation improved

### Removed

### Fixed
- Center calculation after clicking a QuickItem
- Wrong message length in multibyte characters
- Waiting for server data makes clients hang
- Build system test failures
