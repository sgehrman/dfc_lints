[![pub package](https://img.shields.io/pub/v/flutter_lints.svg)](https://pub.dev/packages/flutter_lints)

This package contains a recommended set of lints for [Flutter] apps, packages,
and plugins to encourage good coding practices.

This package is built on top of Dart's `recommended.yaml` set of lints from
[package:lints].

Lints are surfaced by the [dart analyzer], which statically checks dart code.
[Dart-enabled IDEs] typically present the issues identified by the analyzer in
their UI. Alternatively, the analyzer can be invoked manually by running
`flutter analyze`.

## Usage

Flutter apps, packages, and plugins created with `flutter create` starting with
Flutter version 2.3.0 are already set up to use the lints defined in this
package. Entities created before that version can use these lints by following
these instructions:

1. Depend on this package as a **dev_dependency** by running
   `flutter pub add --dev flutter_lints`.
2. Create an `analysis_options.yaml` file at the root of the package (alongside
   the `pubspec.yaml` file) and `include: package:flutter_lints/flutter.yaml`
   from it.

[flutter]: https://flutter.dev
[dart analyzer]: https://dart.dev/guides/language/analysis-options
[dart-enabled ides]: https://dart.dev/tools#ides-and-editors
[package:lints]: https://pub.dev/packages/lints
