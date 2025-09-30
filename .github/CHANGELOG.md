# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Initial Node.js Dev Container implementation
- Multi-stage Dockerfile with builder and runtime stages
- Volta integration for Node.js version management
- VS Code Dev Container optimization with `vscode` user convention
- Security hardening with non-root execution
- Global TypeScript installation
- Comprehensive README with usage examples
- MIT license for open source distribution

### Features
- **Volta Integration**: Seamless Node.js version management
- **VS Code Optimized**: Pre-configured for Dev Container extension
- **Security First**: Non-root execution with hardened runtime
- **TypeScript Ready**: Global TypeScript installation
- **Multi-Stage Build**: Optimized for development and production

### Security
- Root account completely disabled (no password, nologin shell)
- Minimal attack surface with cleaned package managers
- Non-privileged user execution
- Optimized layer caching for faster rebuilds

## [1.0.0] - 2024-09-30

### Added
- Initial release of Node.js Dev Container
- Dockerfile with multi-stage build architecture
- Volta-based Node.js version management
- VS Code Dev Container integration
- Security-hardened runtime environment
- TypeScript development support

### Changed
- N/A (Initial release)

### Deprecated
- N/A (Initial release)

### Removed
- N/A (Initial release)

### Fixed
- N/A (Initial release)

### Security
- Implemented non-root user execution
- Disabled root account access
- Minimized container attack surface

---

## Version Guidelines

### Version Types
- **Major (X.0.0)**: Breaking changes to the container interface or requirements
- **Minor (X.Y.0)**: New features, tools, or significant improvements
- **Patch (X.Y.Z)**: Bug fixes, security updates, or minor improvements

### Change Categories
- **Added**: New features, tools, or capabilities
- **Changed**: Changes to existing functionality
- **Deprecated**: Features marked for removal in future versions
- **Removed**: Features removed in this version
- **Fixed**: Bug fixes and corrections
- **Security**: Security-related changes and updates