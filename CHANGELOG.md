# iOS SDK Release Notes


## 5.0.0

  * We have released the Kount SDK for iOS version 5.0.0 with a complete rewrite in Swift with several API changes.
  * Version 5.0.0 is currently only available for Swift implementations.

## 5.0.1

  * Fix for iOS 17 & Earlier: Removed a hard dependency on an API exclusive to iOS 18+ (allowLossyConversion). This resolves a dyld linker failure that caused an immediate crash on app launch for any device running iOS 17 or earlier.
  * Expanded OS Support: The minimum supported iOS version for the Swift SDK (v5.x.x) has been lowered to iOS 15.6, broadening compatibility for more devices.
  * Repository Segmentation: To improve clarity and streamline development, the SDK repositories have been segmented by their base language. The new Swift SDK (v5.x.x) and the legacy Objective-C SDK (v4.x.x) now reside in separate repositories.
  * Documentation Segmentation: Mirroring the repository changes, the official documentation has also been segmented. You can now find dedicated documentation for the Swift SDK and the Objective-C SDK, making it easier to find the information relevant to your specific implementation.

