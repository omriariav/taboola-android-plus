# Change Log

## [Unreleased]
### Removed
- Methods deprecated in v0.8.4

## [0.8.5] - 2018-06-26
### Changed
- `TBNotificationManager#enable()` call will be ignored if notification refresh job is already running
- Notification hint replaced with animation
- Notification content is no longer cached

### Fixed
- Internal bug fixes

## [0.8.4] - 2018-06-14
### Added
- Application name in notificaiton
- `TaboolaPlus.init()` methods that don't require context
- Transitive dependenicies are now included in pom file

### Deprecated
- `TaboolaPlus.init()` methods with context
- `TaboolaPlus.getInitializedInstance()` methods

## [0.8.3] - 2018-05-25
### Added
- Notification refresh job now survives app update

### Fixed
- Internal bug fixes