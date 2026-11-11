# flutter cache player

A Flutter video player plugin built upon the official [`video_player`](https://pub.dev/packages/video_player) and [`cached_video_player`](https://pub.dev/packages/cached_video_player) packages. It combines their core functionality with caching support for Android and iOS, while ensuring compatibility with the latest Flutter SDK versions through ongoing maintenance and updates.

On Web, it uses the same behavior as the official `video_player` package, without caching support.
## Installation

First, add `flutter_cache_player` as a [dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/).

Follow the Android and iOS configuration steps of the official [video_player](https://pub.dev/packages/video_player#installation) package. This plugin won't work in Desktop.

### Issues
* `maxFileSize` and `maxCacheSize` are hardcoded at 100MiB and 1GiB respectively in Android.

### Contributors

* [Rehan Butt](https://github.com/RehanButt177)