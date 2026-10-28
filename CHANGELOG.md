# Changelog

All notable changes to NeoTiler will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

---

## [2.4.1] - 2026-10-29
### Fixed
- **Accidental Drag-Snap Prevention:** Fixed an issue where switching focus between windows or copying and pasting text across split windows could inadvertently trigger an unexpected corner snap.
- **Precision Window Recognition:** Implemented coordinate-based window identity verification on initial click, preventing false drag gestures and eliminating unnecessary CPU overhead.

## [2.4.0] - 2026-10-28
### Added
- **Multi-Display Window Movement:** Easily cycle active windows across connected displays using dedicated shortcuts (`⌃⌥⌘→` for Next Display and `⌃⌥⌘←` for Previous Display).
- **Smart Proportional Layouts:** Intelligently detects window layouts (Full Screen, Halves, Quarters, Thirds, Centered, or Custom) and scales them proportionally to the target monitor's resolution and visible screen area.
- **Display Shortcuts Management:** Fully integrated into **Preferences → Snap Shortcuts** with custom shortcut recording, reset to defaults, and quick removal.

### Improved
- **Zero-Flicker Screen Transfer:** Implemented WindowServer screen update suppression to ensure seamless, glitch-free window movement across monitors.
- **UI Refinements:** Polished helper text layouts and styling consistency across the Rules and Workspaces preferences tabs.
- **Localization Updates:** Native translations for new multi-display actions across all 12 supported languages.

## [2.3.9] - 2026-10-18
### Improved
- **Window Preview Filtering:** Smarter filtering in Dock Previews and App Switcher to ignore transient and auxiliary overlay windows (such as in-page find bars in browsers like Google Chrome) while preserving genuine popups and dialogues.

## [2.3.8] - 2026-10-12
### Fixed
- **Dock Context Menu Interaction:** Fixed an issue where the Dock Preview panel could inadvertently appear over native macOS right-click menus when quickly right-clicking a Dock icon.

## [2.3.7] - 2026-10-07
### Fixed
- **Trackpad Stability:** Resolved a crash issue related to multitouch event handling on MacBooks equipped with T2 security chips and Apple Silicon.

## [2.3.4] - 2026-09-19
### Added
- **Enhanced Dock Previews:** New preference to keep the Dock preview panel open after selecting a window.
- **Global Refinements & New Language:** NeoTiler now fully supports Korean (한국어)!

### Improved
- **Ultimate Efficiency:** Fundamentally re-architected background event engines, reducing CPU footprint to an absolute minimum.
- **Multi-Display & Layout Mastery:** Dock previews now seamlessly align to left, right, and bottom Dock orientations across all monitors.
- **Smart Interaction Shield:** Native right-click menus from the Dock are now supported without accidental preview overlaps.
- **Language Updates:** Comprehensive updates to all 12 supported languages.

## [2.3.2] - 2026-09-08
### Added
- Added full language support for 11 languages across all menus and dialogs.
### Improved
- Streamlined the installation and onboarding process for new users.

## [2.3.1] - 2026-09-06
### Improved
- General stability improvements and performance optimizations under the hood.

## [2.3.0] - 2026-09-01
### Added
- Finder can now be added to the ignore list, preventing unwanted snapping of Finder windows.
### Improved
- Refreshed the design of the feedback and support window.

## [2.2.4] - 2026-08-31
### Added
- Multi-monitor support for custom snap areas.
### Fixed
- UI bug fixes for localization and the custom snap builder.
- Resolved an issue where some shortcuts could not be deleted.
- Fixed screen detection issues on multi-display setups.
- Fixed Dock overlap when snapping windows to the right, left, or bottom of the screen.

## [2.2.3] - 2026-08-02
### Fixed
- Ignored hidden apps when saving workspaces and properly unminimized docked windows on restore.
- Fixed a bug where shortcut conflict alerts would not display correctly.

## [2.2.2] - 2026-07-28
### Added
- Improved the critical auto-update system for faster and more reliable updates.

## [2.2.1] - 2026-07-27
### Fixed
- Fixed duplicate translations and updated missing languages.

## [2.2.0] - 2026-07-27
### Added
- **Keyboard Lock Feature** — Quickly lock your keyboard using a shortcut.
- Added Simplified Chinese to the language selection.

## [2.1.2] - 2026-07-24
### Fixed
- Fixed a rare crash that occurred during rapid window management.

## [2.1.1] - 2026-05-13
### Improved
- Completed all localizations for the user feedback interface.

## [2.1.0] - 2026-05-09
### Improved
- Full localization parity across the entire application.
- Enhanced hotkey conflict resolution logic for a smoother setup.
- Reduced global tooltip delay for faster interactions.

## [2.0.1] - 2026-04-29
### Fixed
- Filtered closed application windows from the App Switcher to prevent ghost apps from appearing.

## [2.0.0] - 2026-04-24
### Added
- Complete architecture rewrite and major version release for maximum performance.
- **Custom Snap Area Management** — Delete, deactivate, and manage snap areas easily.
### Improved
- Optimized memory usage and improved performance during window snapshots.

## [1.2.1] - 2026-04-10
### Fixed
- Resolved an issue that caused ghost window thumbnails to appear.
- Fixed shadow styling glitches on snapped windows.
- Fixed issues with closing windows via AppleScript.

## [1.2.0] - 2026-04-03
### Improved
- Optimized dock previews with close buttons, right-click support, and significantly better performance.

## [1.1.7] - 2026-03-05
### Added
- Added built-in auto-update system to seamlessly deliver new features.
### Fixed
- Fixed multi-monitor layout restore issues.

## [1.1.6] - 2026-03-02
### Added
- Added a 14-day free trial so users can test all features before purchasing.
### Fixed
- Fixed multi-window layout alignment and improved AppleScript automation permissions.

## [1.1.2] - 2026-02-18
### Added
- Cursor Sync feature with full localization.
- Added input device selection (Trackpad/Mouse) to the Gesture Recorder.

## [1.1.1] - 2026-02-16
### Added
- Custom Trackpad Gesture System.
### Improved
- Optimized workspace restoration speed.
- Fixed a framework installation issue that caused signing ambiguity on some Macs.

## [1.1.0] - 2026-02-12
### Added
- Customizable App Switcher Hotkey & UI/Localization Improvements.

## [1.0.9] - 2026-02-08
### Added
- First public stable release of NeoTiler! 🎉
- Preferences UI styling improvements.
### Fixed
- Fixed language detection on first launch.
- Fixed Ignore List to only block manual snapping while automatic rules work independently.
- Hotkey system improvements and conflict resolution.
