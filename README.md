Join our community on Spectrum to ask your doubts on the way:
[![Join the community on Spectrum](https://withspectrum.github.io/badge/badge.svg)](https://spectrum.chat/upskilldev)


# Flutter

[Flutter](https://flutter.dev) is an open-source UI SDK created and used by Google in most of their projects. It is used to develop applications for mobile, web and desktop. It was developed and first ran on Android with the name of **Sky**.

[Flutter](https://flutter.dev) is now being developed by the its community on [GitHub](https://github.com/flutter/flutter) which makes it stable and better everyday.

# Preparing for Flutter

Flutter runs on top of Android and iOS core which gives it Native-like performance. Being stacked on top Android/iOS/Web core, it's always better to have a basic experience in working with any of these platforms: **Android, iOS, React Native or Web**. This guide assumes you have a basic knowledge of any one platform mentioned above.

Flutter provides official documentation for the the Android, iOS, React Native and Web developers:
- [Flutter for Android Devs](https://flutter.dev/docs/get-started/flutter-for/android-devs).
- [Flutter for iOS Devs](https://flutter.dev/docs/get-started/flutter-for/ios-devs).
- [Flutter for React Native](https://flutter.dev/docs/get-started/flutter-for/react-native-devs).
- [Flutter for web Devs](https://flutter.dev/docs/get-started/flutter-for/web-devs).


# Getting Started

Flutter can be easily installed and run on Windows, macOS and Linux platforms.

## Windows 

### System Requirements

Operating Systems: Windows 7 SP1 or later (64-bit).
Disk Space: 400 MB (excluding IDE/Android SDK/tools)
Tools: 
- Windows PowerShell 5.0 or newer (Comes preinstalled on Windows 10)
- Git for Windows

Make Sure `git` is executable from cmd prompt or PS.

### Get the Flutter SDK

The best way to download and install flutter is by cloning directly from flutter repository.
Run these commands on Command Prompt/Windows PowerShell to clone the flutter repo to **C:/flutter**.
```
git clone https://github.com/flutter/flutter.git -b stable C:/flutter
```

> Note: To use other flutter channels, replace `stable` with the one you want.

Now Flutter SDK has to be added to the environment variables :
- From the Start search bar, enter ‘env’ and select Edit environment variables for your account.
- Under User variables check if there is an entry called Path:
- If the entry exists, append the full path to flutter\bin using ; as a separator from existing values.
- If the entry doesn’t exist, create a new user variable named Path with the full path to flutter\bin as its value.

Note that you have to close and reopen any existing console windows for these changes to take effect.

Lastly, run this command in a new cmd window to verify flutter is working well.
```
flutter doctor
```
It should gereate output similar to this:
```
[-] Android toolchain - develop for Android devices
    • Android SDK at C:\Android\sdk
    ✗ Android SDK is missing command line tools; download from https://goo.gl/XxQghQ
    • Try re-installing or updating your Android SDK,
      visit https://flutter.dev/setup/#android-setup for detailed instructions.
```

### Install Android Studio and SDK

- Download and install [Android Studio](https://developer.android.com/studio).
- Run Android Studio, and go through the 'Android Studio Setup Wizard'. This installs the latest Android SDK and its tools which are required by Flutter when developing for Android.

Now you are ready to learn flutter!

# Resources to start learning Flutter

- Official Flutter Documentation to write your very first app: https://flutter.dev/docs/get-started/codelab
- Basic Flutter Layout concepts: https://flutter.dev/docs/codelabs/layout-basics
- Building beautiful UIs with Flutter: https://codelabs.developers.google.com/codelabs/flutter
- Building Cupertino app with Flutter: https://codelabs.developers.google.com/codelabs/flutter-cupertino

# Kick-Starter Projects

- https://codelabs.developers.google.com/codelabs/google-photos-sharing
- https://github.com/nisrulz/flutter-examples/tree/master/tip_calculator
- https://github.com/nisrulz/flutter-examples/tree/master/expense_planner

