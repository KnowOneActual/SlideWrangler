# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2025-12-09

### Added

- **Logo**: Added new SVG/PNG logo assets to the project.
- **Requirements**: Added `requirements.txt` for easier dependency installation.

### Changed

- **Documentation**: Overhauled `README.md` for better readability, cleaner structure, and more professional tone.
- **Installation**: Updated installation instructions to use `pip install -r requirements.txt`.

## [1.0.0] - 2025-09-26

### Added

- **Core Script**: Initial release of `create_slideshow.py`.
  - Automated folder scanning for valid images.
  - EXIF orientation correction for portrait/landscape photos.
  - Image resizing to 1920x1080 (Full HD).
  - Conversion of all inputs (including PNGs) to JPEG.
  - Automatic generation of widescreen PowerPoint presentations.
  - Temporary folder creation and cleanup logic.
- **License**: MIT License included.
- **Documentation**: Initial `README.md` with usage instructions.
