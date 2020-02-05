# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.2.5] - 2020-01-06

### Added

- Snippets

### Changed

- Macro param highlighting versus eval params

## [1.2.1] - 2020-01-24

### Changed

- Moving scope to `splunk_search` instead of `splunk` in order to be compatible with official Splunk Extension
- Moving to `NOT`'s in Macro params helped to solve TODO task for this

## [1.0.3] - 2020-01-06

### Added

- Highlighting macro parameters
- Highlighting eval command parameters
- Highlighting command arguments (_dbxquery `query`=_)
- Highlighting eval variable/column names

## [1.0.0] - 2020-01-05

### Added

- Highlighting operators (AND, OR, by, etc...)
- Highlighting Macro names
- Highlighting eval commands
- Highlighting DBConnect commands
- Published to VSCE Marketplace
- Highlighting splunk built-in commands
- Highlighting stats commands
