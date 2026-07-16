# Changelog

User-facing changes to PulseCore. It's beta, so expect frequent updates.

## Unreleased

### Added
- **Auto power-off:** the controller now turns itself off when you fully quit PulseCore
  (minimizing to the tray keeps it on).
- The controller **microphone** is available to Windows by default.

### Fixed
- The **mute-button light** now turns off correctly when the mic is on.
- **Battery** now shows the real level in Steam — no more false "low battery" warnings.
- The dashboard and diagnostics no longer show the connection as "stopped" while it's actually active.

### Changed
- **Audio output** (controller speaker vs. plugged-in headset) is now fully automatic — the manual
  switch was removed since detection is reliable.
