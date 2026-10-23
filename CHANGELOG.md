## 1.0.1

* iOS: every WCSession delegate callback is forwarded to Dart on the main thread (platform
  channel messages sent from WCSession's background queue could be dropped silently).
* iOS: received files are moved to `Application Support/flutter_watch_os_connectivity/received/`
  instead of `NSTemporaryDirectory()`, so a file cannot be purged before Dart copies it out.

## 1.0.0

* Add watch connectivity methods to communicate with WatchOS apps.
* Create new WatchOS companion app.

## 0.0.1

* Push temp package.
