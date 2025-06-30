# Liquido 🌊✨

![Liquido](https://img.shields.io/badge/Liquido-Liquid%20Glass%20Effect-blue)

Welcome to **Liquido**! This project provides a way to implement the stunning Liquid Glass effect on Flutter-rendered surfaces. With Liquido, you can enhance your Flutter applications with a visually appealing and modern aesthetic.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Beautiful Liquid Glass Effect**: Create visually stunning surfaces that mimic glass.
- **Easy to Use**: Simple integration with existing Flutter projects.
- **Customizable**: Adjust parameters to fit your design needs.
- **Cross-Platform**: Works seamlessly on both iOS and Android.

## Installation

To get started with Liquido, you need to add it to your Flutter project. Open your `pubspec.yaml` file and add the following dependency:

```yaml
dependencies:
  liquido: ^1.0.0
```

After saving the file, run:

```bash
flutter pub get
```

## Usage

Using Liquido is straightforward. Here’s a simple example to help you get started.

### Step 1: Import the Package

In your Dart file, import the Liquido package:

```dart
import 'package:liquido/liquido.dart';
```

### Step 2: Create a Liquid Glass Widget

You can create a Liquid Glass effect using the `LiquidGlass` widget. Here’s a basic example:

```dart
LiquidGlass(
  child: Container(
    height: 200,
    width: 200,
    color: Colors.blue,
    child: Center(
      child: Text(
        'Hello, Liquido!',
        style: TextStyle(color: Colors.white, fontSize: 20),
      ),
    ),
  ),
),
```

### Step 3: Customize Your Effect

You can customize the appearance of the Liquid Glass effect by adjusting properties such as `blur`, `opacity`, and `borderRadius`. Here’s an example:

```dart
LiquidGlass(
  blur: 10.0,
  opacity: 0.8,
  borderRadius: BorderRadius.circular(15),
  child: Container(
    height: 200,
    width: 200,
    color: Colors.blue,
    child: Center(
      child: Text(
        'Stylish Glass!',
        style: TextStyle(color: Colors.white, fontSize: 20),
      ),
    ),
  ),
),
```

## Examples

### Example 1: Simple Liquid Glass Effect

This example shows a simple Liquid Glass effect on a button.

```dart
ElevatedButton(
  onPressed: () {},
  child: LiquidGlass(
    child: Text('Click Me'),
  ),
),
```

### Example 2: Customizable Liquid Glass Card

This example demonstrates how to create a card with a Liquid Glass effect.

```dart
Card(
  child: LiquidGlass(
    blur: 15.0,
    opacity: 0.9,
    borderRadius: BorderRadius.circular(20),
    child: Padding(
      padding: const EdgeInsets.all(16.0),
      child: Text('This is a card with Liquid Glass effect.'),
    ),
  ),
),
```

## Contributing

We welcome contributions to Liquido! If you want to help, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Create a pull request.

## License

Liquido is open-source software licensed under the MIT License. Feel free to use, modify, and distribute it.

## Releases

To download the latest version of Liquido, please visit the [Releases](https://github.com/Mukaramkhan919/liquido/releases) section. You can find the necessary files to download and execute there.

For updates and changes, keep an eye on the [Releases](https://github.com/Mukaramkhan919/liquido/releases) page.

## Acknowledgments

Thanks to the Flutter community for their support and contributions. Your feedback helps improve Liquido.

## Contact

If you have any questions or suggestions, feel free to reach out via GitHub Issues or directly through my profile.

## Conclusion

Liquido brings a modern and stylish Liquid Glass effect to your Flutter applications. With its easy integration and customization options, you can create stunning interfaces that stand out. Happy coding!