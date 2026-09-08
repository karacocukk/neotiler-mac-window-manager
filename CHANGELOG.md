# Changelog

All notable changes to NeoTiler will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

---

## [2.3.1] — 2026-09-01

### Fixed
- Resolved a rare crash when switching between monitors with different DPI settings
- Fixed drag-to-edge overlay not appearing correctly on external monitors with notch displays
- Improved stability of cursor sync when rapidly moving between 3+ monitors

### Improved
- Reduced memory footprint by ~15% during idle state
- Smoother snap animations on Apple Silicon Macs (M3/M4/M5)

---

## [2.3.0] — 2026-08-15

### Added
- **Windows-Style Taskbar** — A familiar bottom taskbar for quick window switching and previews
- **Auto-Snap Rules** — Define default positions for specific apps (e.g., Safari always opens on the left)
- **Magnetic Grid Snap** — Windows snap to nearby grid lines as you drag them

### Improved
- Advanced App Switcher now shows window thumbnails in real-time
- Reduced startup time by 40%
- Better compatibility with macOS 26 Tahoe beta

### Fixed
- Fixed workspace restoration failing when an app had been updated
- Resolved keyboard shortcut conflicts with some third-party apps

---

## [2.2.9] — 2026-07-20

### Added
- **Cursor Sync** — Seamlessly teleport your cursor between multi-monitor setups
- **Custom Snap Areas** — Define any arbitrary region on your screen as a snap target

### Improved
- Drag-to-edge snap now supports all four corners for quarter-screen layouts
- Updated localization for all 11 supported languages
- Improved accessibility VoiceOver support

### Fixed
- Fixed an issue where shake-to-focus sensitivity was too high on some trackpads
- Resolved a visual glitch in the snap overlay when using dark mode with reduced transparency

---

## [2.2.0] — 2026-06-01

### Added
- **Advanced App Switcher** — Beautiful `⌘ + Tab` replacement with search and previews
- **Shake to Focus** — Shake a window to minimize all others
- **Trackpad Gestures** — Control windows with natural swipe and pinch gestures

### Improved
- Complete UI redesign of Preferences window
- Faster workspace save/restore operations
- Better Stage Manager compatibility

---

## [2.1.0] — 2026-04-15

### Added
- **Smart Workspaces** — Save and restore complete window layouts with `⌘ + ⌥ + 1/2/3`
- 11-language localization (English, Turkish, Japanese, German, Spanish, French, Italian, Danish, Dutch, Polish, Chinese)

### Improved
- Multi-monitor window moving now preserves relative positioning
- Snap animations are now buttery smooth at 120fps on ProMotion displays

---

## [2.0.0] — 2026-02-01

### Added
- Complete rewrite in SwiftUI
- Multi-monitor support with independent snap zones
- Customizable keyboard shortcuts
- Menu bar integration with quick-access snap positions
- 14-day free trial system
- Drag-to-edge snap with visual overlay
- Halves, quarters, and thirds snap layouts
- Native dark mode support
- Accessibility permission auto-management

---

[2.3.1]: https://getneotiler.com
[2.3.0]: https://getneotiler.com
[2.2.9]: https://getneotiler.com
[2.2.0]: https://getneotiler.com
[2.1.0]: https://getneotiler.com
[2.0.0]: https://getneotiler.com
