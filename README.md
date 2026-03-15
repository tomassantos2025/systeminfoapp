# SystemInfoApp

An Android application that displays detailed information about the current device build using the `android.os.Build` class.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Install on Device](#install-on-device)
- [Contributing](#contributing)
- [License](#license)

## Description

SystemInfoApp is a simple Android app that retrieves and shows various system build properties such as manufacturer, model, brand, SDK version, and more in a multiline TextView.

This app was created for the project **“Building a System Info App [AC YES, AI NO]”**, which requires displaying device build information using the `android.os.Build` object.

## Features

- Display device manufacturer, model, and brand
- Show build type, user, SDK version, and other details
- Clean, minimal UI with a multiline TextView
- Works on most Android devices

## Installation

1. Clone this repository:

```bash
git clone https://github.com/tomassantos2025/SystemInfoApp.git
```

2. Open the project in Android Studio.
3. Build and run the app on an emulator or physical device.

## Usage

- Launch the app.
- The main screen displays current device build information extracted from system properties.

## Install on Device

To install SystemInfoApp directly on your Android device without Android Studio:

1. Download the `app-debug.apk` file from the `app/build/outputs/apk/debug/` directory or from the repository releases if available.

   [Download SystemInfoApp APK](https://github.com/tomassantos2025/SystemInfoApp/releases/latest/download/SystemInfoApp-v1.apk)

3. On your Android device, enable installation from unknown sources:  
   - Go to **Settings → Security → Install unknown apps**  
   - Allow your file manager or browser to install APKs.

4. Open the APK file and follow the prompts to install the app.

5. Launch SystemInfoApp from your app drawer.

## Contributing

Contributions are welcome! Please fork the repository, create a feature branch, commit your changes, and open a pull request.

## License

This project is licensed under the MIT License.
