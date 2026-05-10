# Changelog

All notable changes to the **Tab Out** extension will be documented in this file.

## [1.0.2] - 2026-05-10

### Added
- **Domain Grouping for Saved Items**: "Saved for later" items are now automatically grouped by domain into cards, matching the "Open tabs" logic.
- **Card-based Aesthetic**: Refactored the "Saved for later" and "Archive" sections with a premium card design, including top accent bars and hover shadows.
- **Masonry Layout**: "Saved for later" cards now use a multi-column grid layout for better screen utilization.
- **Recency Sorting**: Domain groups in "Saved for later" and "Archive" are now sorted by the latest interaction time.
- **Archive Deletion**: Added a "Delete" (X) button to archived items for easier cleanup.

### Fixed
- **History Section Visibility**: Resolved a bug where the "Recently visited" section would disappear after closing a tab in the "Open tabs" section.
- **History Refresh Timing**: Added a 1.5s delay to history queries after tab closure to ensure Chrome has finished writing to its database.
- **CSS Layout**: Fixed a major layout breakage in the checklist column by adding missing component styles to `style.css`.

### Changed
- **Dashboard Layout**: Reordered the main sections to a vertical stacked layout for better readability on larger screens.

---

## [1.0.1] - 2026-05-03

### Added
- **Theme Switching**: Added support for 'Light', 'Dark', and 'System' appearance modes.
- **Bookmark Bar Enhancements**: Improved the high-fidelity bookmark bar with overflow management and hover dropdowns.

### Fixed
- **Settings Persistence**: Fixed an issue where extension settings were not correctly saved to `chrome.storage.local`.

---

## [1.0.0] - 2026-04-25

### Added
- Initial release of **Tab Out**.
- Domain-based tab grouping.
- "Save for later" basic checklist.
- Satisfying close animations with sound and confetti.
