# Changelog

All notable changes to NeoTiler will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

---

## [2.3.2] - 2026-09-08
### Added
- Complete localization parity across 11 languages for trial and error messages.
### Improved
- Streamlined licensing flow by removing the trial modal gate on the website.
- Added direct download capabilities directly from `getneotiler.com`.

## [2.3.1] - 2026-09-08
### Improved
- General stability improvements and safe checkpointing.

## [2.3.0] - 2026-09-07
### Added
- Finder can now be added to the ignore list, preventing unwanted snapping of Finder windows.
### Improved
- Updated Trial Feedback View with email input and styling fixes.

## [2.2.7] - 2026-09-06
### Added
- Multi-monitor support for custom snap areas.
### Fixed
- UI bug fixes for localization and custom snap builder.
- Resolved shortcut deletion issues.
- Fixed screen detection issues.
- Fixed Dock overlap when snapping windows to the right/left/bottom of the screen.

## [2.2.4] - 2026-09-05
### Added
- 24-hour background validation timer for subscription licenses.
### Improved
- Continuous tracking of trial expiration alongside license validation.

## [2.2.3] - 2026-09-04
### Fixed
- Ignored hidden apps on save and unminimized docked windows on workspace restore.
- Fixed SwiftUI alert bug by using NSAlert for shortcut conflicts.

## [2.2.2] - 2026-09-03
### Added
- Sparkle critical update system.
- Critical update translations for all supported languages.

## [2.2.1] - 2026-09-02
### Fixed
- Fixed duplicate translations and updated missing languages.

## [2.2.0] - 2026-09-01
### Added
- **Keyboard Lock Feature** — Quickly lock your keyboard using a shortcut.
- Simplified Chinese localization added to the language selection.

## [2.1.2] - 2026-08-28
### Fixed
- Added CoreFoundation type safety checks (CFGetTypeID) to prevent AXUIElement casting crashes.

## [2.1.1] - 2026-08-25
### Improved
- Completed all localizations for Trial Feedback View.

## [2.1.0] - 2026-08-20
### Improved
- Full localization parity.
- Enhanced hotkey conflict resolution logic.
- Reduced global tooltip delay to 0.5s for faster interactions.

## [2.0.1] - 2026-08-15
### Fixed
- Filtered closed application windows from the App Switcher to prevent ghost apps.

## [2.0.0] - 2026-08-10
### Added
- Complete rewrite and major version release.
- **Custom Snap Area Management** — Delete, deactivate, and manage snap areas easily.
- Smart Snapshot Memory (WindowID based) and log cleaning.

## [1.9.1] - 2026-08-05
### Fixed
- Resolved ghost window thumbnails issue.
- Fixed shadow styling glitches.
- Fixed AppleScript close handler bugs.

## [1.9.0] - 2026-08-01
### Added
- License security layer update (Keychain + Machine ID + Clone protection).
### Improved
- Refactored license handling to single-bundle Keychain JSON.
- Optimized dock previews with close buttons, right-click support, and better performance.

## [1.1.7] - 2026-07-28
### Added
- Auto-update system (Sparkle Integration).
### Fixed
- Multi-monitor layout restore fixes.

## [1.1.6] - 2026-07-25
### Added
- Implement trial system, upsell UI, and instance-based license deactivation tracking.
### Fixed
- Multi-window layout fix and AppleScript automation permissions.

## [1.1.2] - 2026-07-20
### Added
- Cursor Sync feature with localization and improvements.
- Input device selection (Trackpad/Mouse) to Gesture Recorder.

## [1.1.1] - 2026-07-15
### Added
- Custom Trackpad Gesture System and translations.
### Improved
- Optimize workspace restoration timing (0.2s delay).
- Flattened OpenMultitouchSupportXCF framework to resolve signing ambiguity.

## [1.1.0] - 2026-07-10
### Added
- Customizable App Switcher Hotkey & UI/Localization Improvements.

## [1.0.9] - 2026-07-05
### Added
- First public stable release of NeoTiler.
- License Activation & Verification System.
- Preferences UI styling improvements.
### Fixed
- Localization detection issues in DMG builds.
- Fixed Ignore List to only block manual snap while auto-rules work independently.
- Hotkey system improvements and conflict resolution.
