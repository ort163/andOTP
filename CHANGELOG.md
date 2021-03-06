# Changelog

#### v0.2.7

 * New feature: require authentication again after screen lock (Issue #28)
 * New feature: make response to Panic Trigger configurable (Issue #35)
 * Update: Android SDK 26 (Oreo)
 * Update: Apache Commons Codec 1.10
 * Code: lot of internal changes (mostly due to the Android 26 update)

#### v0.2.6

 * New feature: custom password preference with confirmation (Issue #26)
 * New feature: use an individual password or PIN to lock the app (Issue #23)
 * New feature: support for Panic Trigger (PR #27 by carmebar)
 * New feature: support for variable digits lenths (PR #30 by SuperVirus)
 * Bug fix: OpenPGP with security token (Issue #20, PR #25 by carmebar)
 * Style/UI: add Contributors, Translators and Translate to About
 * Code: internal refactoring
 * Translation: German (de-rDE) thanks to SuperVirus

#### v0.2.5

 * New feature: sort the entries by label (Issue #12)
 * New feature: add support for SHA256 and SHA512 (Issue #24)
 * Bug fix: show current theme in the settings
 * Bug fix: don't show FloatingActionMenu when scrolling while searching
 * Code: lots of internal refactoring
 * Translation: Polish (pl-rPL) thanks to Daniel Pustuła
 * Translation: Spanish (es-rES) thanks to Carlos Melero

#### v0.2.4

 * New feature: make the font size of the labels configurable (Issue #18)
 * Style/UI: Dark theme (Issue #3)
 * Bug fix: make the backup activity scrollable (Issue #15)
 * Bug fix: remove swipe-to-dismiss to avoide accidental deletions (Issue #13)
 * Bug fix: use the whole card for tap-to-reveal, not just the token (Issue #10)
 * Code: internal changes (as always)

#### v0.2.3

 * New feature: encrypted backups with password
 * New feature: show a warning about backups on the first launch
 * Style/UI: rename Export and Import to Backup and Restore
 * Bug fix: don't require device authentication again after screen rotation (Issue #7)
 * Bug fix: hide the FloatingActionMenu on scroll (Issue #8)
 * Bug fix: rename the apps launcher icon to "andOTP" (Issue #6)
 * Bug fix: restrict the label size so they don't overlap with the buttons (Issue #9)
 * Code: lots of internal refactoring

#### v0.2.2

 * Bug fix: resume import and export after permission request
 * Bug fix: implement a working hashCode function for the Entry class
 * Code: add missing copyright headers
 * Code: fix some tests
 * Code: remove outdated tests

#### v0.2.1

 * New feature: encrypted backups using OpenPGP
 * Style: new about screen
 * Style: new backup screen
 * Code: a lot of refactoring

#### v0.2.0

 * New feature: copy token to clipboard
 * New feature: device credentials to unlock app
 * New feature: manually enter account details
 * New feature: search
 * New feature: settings activity
 * New feature: tap to reveal
 * Style: replace FAB with a custom FloatingActionMenu
 * Style: replace all Snackbars with Toasts
 * Update: ZXing Android Embedded v3.5.0
 * Code: a lot of internal fixes and refactoring
 * Code: initial groundwork to support different types of OTP tokens (e.g. HOTP)

#### v0.1.0

 * Initial release (beta)

