<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages).
-->

Beautiful UI components, Over 500+ professionally designed, fully responsive, you can drop into your projects and customize it.

## Features

- Pre-build Theme and Customize it
- Pre-build UI Component and Customize it

## Getting started

### Requirement

sdk `">=2.18.0 <3.0.0"`
flutter `">=1.17.0"`

## Usage

#### Pre-build Theme

prebuild theme have color default according to UI research\
see docs for more pre-build theme

```dart

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Demo',
      theme: AppTheme.nature(),
      home: const MyHomePage(title: 'Flutter Demo Home Page'),
    );
  }
}

```

#### Custom Theme

custom theme have default color or you can customize your own color\
see docs or example for more detail how to use custom theme

```dart

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Demo',
      theme: AppTheme.custom(primary: Colors.red),
      home: const MyHomePage(title: 'Flutter Demo Home Page'),
    );
  }
}

```

#### Custom Button

custom button widget use elevated button as base button

```dart

  AppButton(
    onPressed: () {},
    borderRadius: 48.0,
    child: const Text("SUBMIT"),
  ),

```

<!-- ## Additional information

Tell users more about the package: where to find more information, how to
contribute to the package, how to file issues, what response they can expect
from the package authors, and more. -->
