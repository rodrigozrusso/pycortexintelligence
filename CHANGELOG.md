# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

## [Unreleased]

### Added
- CLI to Download Cube/Form from Cortex
- Release 0.1.0 as a Branch
- Releases as a Branch

### Changed
- Improve error handling of functions
- Adjust standardization of function nomenclature

## [0.0.9] - 2020-12-14

### Added

- adding developer guidelines to contributions
- adding CHANGELOG.md file
- adding support to download file from Cortex Application

### Added

- create core/messages.py file to index messages

## [0.0.8] - 2020-10-30

### Changed

- using logging module instead of print()
- update on file creation to `utf-8`
- update README.md

### Added

- create core/messages.py file to index messages

## [0.0.7] - 2020-10-30

### Added

- creating a CLI for pycortexintelligence

```bash
cortex.py --help
```

## [0.0.6] - 2020-10-27

### Fixed

- fix bug with calling _upload_local_2_cube_ function.

## [0.0.5] - 2020-10-26

### Added

- added support to data_format on upload_to_cortex

```python
dafault_data_format = {
    "charset": "UTF-8",
    "quote": "\"",
    "escape": "\/\/",
    "delimiter": ",",
    "fileType": "CSV"
}
```

## [0.0.4] - 2020-10-13

### Added

- Create README.md

## [0.0.3] - 2020-10-13

### Added

- Using format to string concatenation.

## [0.0.2] - 2020-10-08

### Added

- Ajust requirements.txt file and configuration to [Pypi](https://pypi.org/)

## [0.0.1] - 2020-10-08

### Added

- Birth of the project in order to simplify the use of Cortex's APIs.

# TODO Version Compare
[unreleased]: 