# Version History - Computer Sentinel 🛡️

This project follows a modular development cycle to ensure system stability and real-time telemetry accuracy.

## [1.0.1] - 2026-01-09
### Added
- **Trend Tracking (Delta System):** Added real-time increase/decrease symbols (▲/▼) for CPU and RAM usage.
- **Desktop Notifications:** Integrated `plyer` for Windows/Linux system tray alerts when thresholds are exceeded.
- **Dynamic Coloring:** Implemented `get_status_color` logic (Green -> Yellow -> Red) based on resource intensity.

### Improved
- **Hardware Interface:** Optimized `psutil` calls to reduce the script's own CPU footprint.
- **Terminal UI:** Enhanced dashboard layout with ASCII dividers for better readability.

### Fixed
- Fixed a bug where battery status would crash the script on desktop PCs without a battery.
- Resolved a screen flickering issue on Unix-based terminals.

## [1.0.0] - 2026-01-09
### Added
- **Core Sentinel Engine:** Initial release with CPU, RAM, and Disk monitoring.
- **Modular Configuration:** Single-block SETTINGS and THRESHOLDS for easy user customization.
- **Auto-Installer:** Integrated `install_dependencies` to handle missing libraries on first run.
