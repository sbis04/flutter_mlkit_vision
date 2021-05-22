# Flutter ML Kit Vision

This a sample Flutter app integrated with the [ML Kit](https://developers.google.com/ml-kit) Vision API for recognition of **email addresses** from an image.

> **NOTE:** The ML Kit plugin for Flutter ([google_ml_kit](https://pub.dev/packages/google_ml_kit)) is under development and is only available for `Android` platform. 
> 
> There was [firebase_ml_vision](https://pub.dev/packages/firebase_ml_vision) package having similar functionality but providing cloud based ML solution connected to Firebase, and also supported both `Android` and `iOS` platforms. Unfortunately, it is **now discontinued** since these APIs are no longer available in the latest Firebase SDK. But it is still functional and if you want to use it check out the GitHub repo [here](https://github.com/sbis04/flutter_vision).

## Plugins

Using the following dependencies in the pubspec.yaml file:

```yaml
dependencies:
  camera: ^0.8.1
  google_ml_kit: ^0.3.0
```

> For the latest version of these plugins checkout their respective pages on `pub.dev`.

## App screenshots

![](screenshots/mlkit_screens.png)

## Usage

> Currently only `Android` platform is supported but work is going on for the `iOS` side, you can track the progress on its [GitHub repo](https://github.com/bharat-biradar/Google-Ml-Kit-plugin).

You can try out the app on your system by following these steps:

1. Clone this repo:
   
   ```bash
   git clone https://github.com/sbis04/flutter_mlkit_vision.git
   ```

2. Get packages:
   
   ```bash
   flutter pub get
   ```

3. Go to `android/app/build.gradle` and update the `minSdkVersion` to **26**:
   
   ```gradle
   minSdkVersion 26
   ```

4. Run the app:
   
   ```bash
   flutter run
   ```

## License

Copyright (c) 2021 Souvik Biswas

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
