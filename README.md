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

TODO: Put a short description of the package here that helps potential users
know whether this package might be useful for them.

## Features

Supports various image types: asset, file, network, svg, memory, gifAsset, gifMemory, gifNetwork,
jsonAsset, jsonFile, jsonNetwork, and jsonMemory.
Customizable image shape options: circle, rectangle, oval, and none.
Error builder and loader builder for better customization.
Filter quality, blend mode, alignment, scale, border radius, and other image-specific properties.

## Getting started

TODO: Add the package to your project by running the following command in your terminal:
flutter pub add custom_image
TODO: Import the package in your Dart file:
import 'package:custom_image/custom_image.dart';

## Usage

TODO: Here's a basic example of how to use the ImageService widget:
ImageService(
image: 'https://example.com/image.jpg',
imageType: ImageType.network,
imageShape: ImageShape.circle,
height: 100,
width: 100,
);
You can customize the appearance of the image by using various properties:
ImageService(
image: 'https://example.com/image.jpg',
imageType: ImageType.network,
imageShape: ImageShape.rectangle,
height: 200,
width: 300,
filterQuality: FilterQuality.high,
blendMode: BlendMode.multiply,
alignment: Alignment.center,
scale: 1.5,
borderRadius: BorderRadius.circular(10),
)
```dart

const like = 'sample';
```

## Additional information

TODO: Tell users more about the package: where to find more information, how to
contribute to the package, how to file issues, what response they can expect
from the package authors, and more.
