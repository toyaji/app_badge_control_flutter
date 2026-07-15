## 0.1.2

* Upgrade `web` dependency to `^1.0.0` for modern Flutter packages compatibility.

## 0.1.1

* Fix `removeBadge()` on Android to clear all notifications to ensure the badge is completely removed.

## 0.1.0

* Forked from [`flutter_app_badge_control`](https://github.com/funseek/flutter_app_badge_control) and republished as `app_badge_control_flutter`. See the README's "Why this fork exists" and "Migrating from `flutter_app_badge_control`" sections for details.
* Renamed the public Dart API: `FlutterAppBadgeControl` → `AppBadgeControlFlutter` (platform interface and method-channel implementation classes renamed accordingly).

## 0.0.3

* Add Swift Package Manager support for iOS while keeping CocoaPods support.
* Update Android build tooling (AGP, Kotlin, compileSdk 36, Java 17) and the example app's Gradle wrapper for compatibility with the latest stable Flutter.
* Update `flutter_lints` to ^6.0.0.

## 0.0.1

* Initial release.
