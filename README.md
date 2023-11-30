[![Dart | Windows][dart_windows_card]][win32_pub_link]

[![Package: dartwindows_lints][package_badge]][package_link]
[![Publisher: win32.pub][publisher_badge]][publisher_link]
[![License: BSD-3-Clause][license_badge]][license_link]

A set of lints used by the Dart | Windows organization to analyze their packages
and repositories; it's built on top of `package:lints/recommended.yaml`.

Part of the [Dart | Windows][dart_windows_link] suite of Windows packages.

## Usage

To use the lints, add a dependency in your `pubspec.yaml` file:

```yaml
dev_dependencies:
  dartwindows_lints: ^1.1.0
```

then, add an `analysis_options.yaml` file to your project:

```yaml
include: package:dartwindows_lints/analysis_options.yaml
```

[dart_windows_card]: https://raw.githubusercontent.com/dart-windows/.github/main/assets/dart-windows-card-480x240.png
[dart_windows_link]: https://github.com/dart-windows
[license_badge]: https://img.shields.io/github/license/dart-windows/dartwindows_lints?color=blue
[license_link]: https://opensource.org/licenses/BSD-3-Clause
[package_badge]: https://img.shields.io/pub/v/dartwindows_lints.svg
[package_link]: https://pub.dev/packages/dartwindows_lints
[publisher_badge]: https://img.shields.io/pub/publisher/dartwindows_lints.svg
[publisher_link]: https://pub.dev/publishers/win32.pub
[win32_pub_link]: https://win32.pub
