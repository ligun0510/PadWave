# Changelog

User-facing changes to PadWave.

## 0.9.0 — 2026-07-21

First public beta.

### Added
- **Games with built-in DualSense support now recognise the controller as a real DualSense** —
  PlayStation button icons and the game's own adaptive-trigger effects, over Bluetooth, with no
  extra setup. Verified in Cyberpunk 2077.
- **Mods:** a new tab with effect packs — ready-made sets of adaptive-trigger and haptic effects for
  a particular game, installed with one click. Packs update themselves when a better version is
  published, and the app says what changed. First up: Half-Life 2 and both episodes.
- **Auto power-off:** the controller now turns itself off when you fully quit PadWave
  (minimizing to the tray keeps it on).
- The controller **microphone** is available to Windows by default.
- **Audio player:** play your own audio file straight through the controller's speaker
  or a plugged-in headset — with play/pause, seeking and a progress bar.
- **Controller tuning:** set vibration strength, adaptive-trigger firmness and lightbar
  brightness, and pick the lightbar colour.
- **Connection quality in Diagnostics**, including a warning when your Wi-Fi is on the 2.4 GHz band.
  On laptops where Wi-Fi and Bluetooth share one card, 2.4 GHz Wi-Fi starves the controller's
  Bluetooth link — it is the most common cause of stuttering controller audio, and moving the Wi-Fi
  to 5 GHz fixes it outright.

### Fixed
- **Controller audio no longer stops after the controller reconnects** (sleep, power-cycle
  or re-pair) — sound keeps working without removing and re-adding the controller.
- **A sleeping controller is now shown as asleep**, not as connected. Windows keeps calling it
  connected long after it has stopped sending anything, which made PadWave look broken when the
  controller had simply dozed off. Press the PS button and it comes straight back.
- **Waking the controller no longer interrupts a running game.** The virtual controller stays in
  place while the real one is away, so games and controller audio survive a sleep, a walk out of
  range, or a battery swap.
- The **mute-button light** now turns off correctly when the mic is on.
- **Battery** now shows the real level in Steam — no more false "low battery" warnings.
- The dashboard and diagnostics no longer show the connection as "stopped" while it's actually active.
- **Volume no longer resets to zero** on its own.
- The **lightbar colour** now updates reliably when you change it.

### Changed
- **Audio output** (controller speaker vs. plugged-in headset) is now fully automatic — the manual
  switch was removed since detection is reliable.
- **Refreshed look:** a cleaner, darker interface across the whole app.
- **Reorganized Settings and Audio:** the most-used controls are up front, with advanced
  options moved into an "Advanced" section.
