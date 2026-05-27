# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Added
- Core CSS Variables foundation in webkit.css
  - Color variables (primary, secondary, backgrounds, text hierarchy)
  - Spacing scale (xs, sm, md, lg, xl based on 4px-32px)
  - Border radius scale (sm: 8px, md: 12px, lg: 16px)
  - Typography variables (system-native font stack, 16px base, 400 weight, 1.6 line-height)
  - Transition variables (fast: 300ms, slow: 600ms with ease-in-out)
- System-native font stack for cross-platform consistency
- OLED-optimized color implementation with proper contrast ratios

### Changed
- (none yet)

### Fixed
- (none yet)

---

## Released Versions

## [0.2.0] - 2026-05-26

### Added
- Core CSS Variables foundation in webkit.css
  - Color variables (primary, secondary, backgrounds, text hierarchy)
  - Spacing scale (xs, sm, md, lg, xl based on 4px-32px)
  - Border radius scale (sm: 8px, md: 12px, lg: 16px)
  - Typography variables (system-native font stack, 16px base, 400 weight, 1.6 line-height)
  - Transition variables (fast: 300ms, slow: 600ms with ease-in-out)
- System-native font stack for cross-platform consistency
- OLED-optimized color implementation with proper contrast ratios

### Changed
- N/A

### Fixed
- N/A

## [0.1.0] - 2026-05-26

### Added
- Initial project structure and repository setup
- Core theme configuration with skin.json featuring OLED-optimized color palette
  - Primary color: #C15F3C (Anthropic Crail Orange)
  - Secondary color: #6A9BCC (Anthropic Blue)
  - OLED-friendly absolute black background (#000000)
- README.md with complete installation guide and customization instructions
- Color preview HTML page (preview.html) showcasing theme palette and component styles
- Project context documentation detailing theme vision, objectives, and technical stack

### Changed
- N/A

### Fixed
- N/A

---

## Guidelines for Maintaining This Changelog

### How to Update

1. **While developing:** Add your changes to `[Unreleased]` section
   - Add under `### Added`, `### Changed`, or `### Fixed`
   - Be specific and clear

2. **When releasing a version:**
   - Move `[Unreleased]` section to new version with date: `[X.Y.Z] - YYYY-MM-DD`
   - Create new empty `[Unreleased]` section for next changes
   - Update version in `skin.json` to match

3. **Example:**
   ```markdown
   ## [Unreleased]
   
   ### Added
   - New feature X
   
   ---
   
   ## [0.3.0] - 2026-05-27
   
   ### Added
   - Previous feature Y
   ```

### Categories

- **Added** — New features, files, or functionality
- **Changed** — Changes to existing functionality or structure
- **Fixed** — Bug fixes and corrections
- **Removed** — Deprecated or deleted features (if applicable)
- **Security** — Vulnerability fixes (if applicable)

### Commit Message Format

- **feat:** Feature implementation → goes to `Added`
- **docs:** Documentation updates → goes to `Added` (or separate "Documentation" if major)
- **fix:** Bug fixes → goes to `Fixed`
- **chore:** Non-feature work (maintenance, tooling)
- **style:** Code style changes (cosmetic)

### Version Numbering

- **0.x.x** — Pre-release, unstable
- **1.0.0** — First stable release (theme fully functional)
- **MAJOR.MINOR.PATCH** — Follow [Semantic Versioning](https://semver.org/)

---

**Last Updated:** 2026-05-26  
**Maintained By:** Rafael Stevanato  
**Repository:** [steam-stvn-oled-ui](https://github.com/RafaelStevanato/steam-stvn-oled-ui)
