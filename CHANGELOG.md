# Change Log

All notable changes to the "avego-theme" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),  
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- No unreleased changes at the moment.

## [0.0.3] - 2026-03-01

### Added
- New theme variant: "Notepad++ Avego Light" — a lighter version where only the Activity Bar remains dark, while all other panels, editor, and terminal are fully light.
- Updated README.md to describe both theme variants with explanations and additional screenshots for the new light variant.
- Added more keywords to package.json for better discoverability in the Marketplace.
- Improved terminal cursor visibility in both variants by setting "terminalCursor.foreground" to "#000000" and "terminalCursor.background" to "#0087FF".

### Changed
- Minor adjustments to colors in the original theme for better consistency (e.g., editorCursor.background updated to "#0087FF").
- Updated galleryBanner in package.json to better match the light theme style.

### Fixed
- Fixed cursor visibility issues in the integrated terminal for light backgrounds.

## [0.0.2] - 2026-02-15

### Added
- English localization for package.json and README.md (displayName, description, keywords, etc.).
- Added icon.png support in package.json for a custom extension icon.
- Added repository, homepage, and bugs URLs in package.json for better project linking.
- Enhanced README.md with screenshots (PHP, CSS, HTML+CSS+JS) and detailed installation instructions.
- Added contact information for Avego Web Studio in README.md.

### Changed
- Updated version to 0.0.2.
- Refined theme colors for better readability (e.g., editorLineNumber.foreground to "#5b8390").
- Switched to English for all documentation files.

### Fixed
- Various minor color inconsistencies to more accurately match Notepad++ syntax highlighting.

## [0.0.1] - 2026-01-10

### Added
- Initial release of the "Notepad++ Avego" theme.
- Accurate recreation of Notepad++ default syntax highlighting.
- Support for multiple languages including PHP, CSS, HTML, JS, Python, JSON, Markdown, and more.
- Basic structure: package.json, theme JSON file, README.md, CHANGELOG.md.

### Fixed
- Initial bug fixes for token colors (e.g., comments in green, keywords in bold blue).