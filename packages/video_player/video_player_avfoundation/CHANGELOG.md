## 2.4.8

* Fixes missing `isPlaybackLikelyToKeepUp` check for iOS video player `bufferingEnd` event and `bufferingStart` event.

## 2.4.7

* Updates minimum supported SDK version to Flutter 3.3/Dart 2.18.
* Adds iOS exception on incorrect asset path

## 2.4.6

* Fixes hang when seeking to end of video.

## 2.4.5

* Updates functions without a prototype to avoid deprecation warning.

## 2.4.4

* Updates pigeon to fix warnings with clang 15.

## 2.4.3

* Synchronizes `VideoPlayerValue.isPlaying` with `AVPlayer`.

## 2.4.2

* Makes seekTo async and only complete when AVPlayer.seekTo completes.

## 2.4.1

* Clarifies explanation of endorsement in README.
* Aligns Dart and Flutter SDK constraints.

## 2.4.0

* Updates minimum Flutter version to 3.3 and iOS 11.

## 2.3.9

* Updates links for the merge of flutter/plugins into flutter/packages.
* Updates minimum Flutter version to 3.0.

## 2.3.8

* Adds compatibilty with version 6.0 of the platform interface.
* Fixes file URI construction in example.
* Updates code for new analysis options.
* Adds an integration test for a bug where the aspect ratios of some HLS videos are incorrectly inverted.
* Removes an unnecessary override in example code.

## 2.3.7

* Fixes a bug where the aspect ratio of some HLS videos are incorrectly inverted.
* Updates code for `no_leading_underscores_for_local_identifiers` lint.

## 2.3.6

* Fixes a bug in iOS 16 where videos from protected live streams are not shown.
* Updates minimum Flutter version to 2.10.
* Fixes violations of new analysis option use_named_constants.
* Fixes avoid_redundant_argument_values lint warnings and minor typos.
* Ignores unnecessary import warnings in preparation for [upcoming Flutter changes](https://github.com/flutter/flutter/pull/106316).

## 2.3.5

* Updates references to the obsolete master branch.

## 2.3.4

* Removes unnecessary imports.
* Fixes library_private_types_in_public_api, sort_child_properties_last and use_key_in_widget_constructors
  lint warnings.

## 2.3.3

* Fix XCUITest based on the new voice over announcement for tooltips.
  See: https://github.com/flutter/flutter/pull/87684

## 2.3.2

* Applies the standardized transform for videos with different orientations.

## 2.3.1

* Renames internal method channels to avoid potential confusion with the
  default implementation's method channel.
* Updates Pigeon to 2.0.1.

## 2.3.0

* Updates Pigeon to ^1.0.16.

## 2.2.18

* Wait to initialize m3u8 videos until size is set, fixing aspect ratio.
* Adjusts test timeouts for network-dependent native tests to avoid flake.

## 2.2.17

* Splits from `video_player` as a federated implementation.
