# Changelog

User-facing changes to PulseCore. It's beta, so expect frequent updates.

## Unreleased

### Added
- **Auto power-off:** the controller now turns itself off when you fully quit PulseCore
  (minimizing to the tray keeps it on).
- The controller **microphone** is available to Windows by default.
- **Audio player:** play your own audio file straight through the controller's speaker
  or a plugged-in headset — with play/pause, seeking and a progress bar.
- **Controller tuning:** set vibration strength, adaptive-trigger firmness and lightbar
  brightness, and pick the lightbar colour.

### Fixed
- The **mute-button light** now turns off correctly when the mic is on.
- **Battery** now shows the real level in Steam — no more false "low battery" warnings.
- The dashboard and diagnostics no longer show the connection as "stopped" while it's actually active.
- **Controller audio no longer stops after the controller reconnects** (sleep, power-cycle
  or re-pair) — sound keeps working without removing and re-adding the controller.
- **Volume no longer resets to zero** on its own.
- The **lightbar colour** now updates reliably when you change it.

### Changed
- **Audio output** (controller speaker vs. plugged-in headset) is now fully automatic — the manual
  switch was removed since detection is reliable.
- **Refreshed look:** a cleaner, darker interface across the whole app.
- **Reorganized Settings and Audio:** the most-used controls are up front, with advanced
  options moved into an "Advanced" section.
