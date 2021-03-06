# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2020-11-24
### Added
 - support for **PHP 7.2**
 - **Whoops** for error handling

### Removed
 - custom **Composer** command `serve` which fails due to **PHP** `max_execution_time` ini directive.

## [1.0.0] - 2020-11-22
### Added
 - basic project structure (configuration, web entrypoint, source code, templating)
 - **Slim** v4 + **PHP-DI** integration
 - **Twig** and **Doctrine** setup
 - `AbstractController` with templating and redirecting methods
 - default homepage
 - development web server command

[Unreleased]: https://github.com/AymDev/Slim-Starter/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/AymDev/Slim-Starter/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/AymDev/Slim-Starter/releases/tag/v1.0.0