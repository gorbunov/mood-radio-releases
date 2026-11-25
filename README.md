# Mood Radio releases

Builds of [Mood Radio](https://mood-radio.gorbunov.dev), a mood-driven radio for Apple Music on the Mac.

- **Download:** the DMG under [the latest release](https://github.com/gorbunov/mood-radio-releases/releases/latest).
  It needs macOS 27 and an Apple Music subscription.
- **Updates:** the app checks `appcast.xml` here once a day (Sparkle) and asks before installing.
- Each build is signed with Developer ID and notarized by Apple. Each update is also signed with an EdDSA key
  whose public half ships in the app.

The source is not public. This repository holds only the builds and the update feed, and is written by a
release script.
