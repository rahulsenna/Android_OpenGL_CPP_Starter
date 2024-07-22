# Android OpenGL C++ NDK Starter Project

Welcome to the Android OpenGL C++ NDK starter project! This project serves as a basic starting point for developing Android applications using OpenGL and the Native Development Kit (NDK) with C++. Follow the instructions below to get started.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Setup and Build](#setup-and-build)
- [Running the App](#running-the-app)
- [Project Details](#project-details)
- [Contributing](#contributing)
- [License](#license)

## Screenshot
![ScreenShot1.jpg](docs%2FScreenhots%2FScreenShot1.jpg)

## Prerequisites

Before you begin, ensure you have met the following requirements:
- **Android Studio**: Download and install [Android Studio](https://developer.android.com/studio).
- **Android NDK**: Install the NDK through the Android Studio SDK Manager.
- **CMake**: Ensure CMake is installed. It can be installed through the Android Studio SDK Manager.
- **A Physical Device or Emulator**: Set up an Android device or emulator for testing.

## Project Structure

```
AndroidOpenGLNDK/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── cpp/
│   │   │   │   ├── CMakeLists.txt
│   │   │   │   └── main.cpp
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── example/
│   │   │   │           └── android_game_dev_learn/
│   │   │   │               └── MainActivity.java
│   │   │   ├── res/
│   │   │   │   └── layout/
│   │   │   │       └── activity_main.xml
│   │   │   └── AndroidManifest.xml
│   └── build.gradle
├── build.gradle
└── settings.gradle
```

## Setup and Build

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rahulsenna/Android_OpenGL_CPP_Starter.git
   cd Android_OpenGL_CPP_Starter
   ```

2. **Open in Android Studio**:
    - Open Android Studio.
    - Click on `Open an existing Android Studio project`.
    - Navigate to the cloned repository folder and select it.

3. **Configure CMake and NDK**:
    - Open `File` > `Project Structure`.
    - Under `SDK Location`, ensure the NDK location is correctly set.
    - Sync the project by clicking on `File` > `Sync Project with Gradle Files`.

4. **Build the Project**:
    - Click on the `Build` menu and select `Make Project`.

## Running the App

1. **Connect a Device or Start an Emulator**:
    - Connect your Android device via USB, or start an Android emulator.

2. **Run the Application**:
    - Click the `Run` button (green play button) in Android Studio.
    - Select the connected device or emulator and click `OK`.

## Project Details

### MainActivity.java

The `MainActivity` class uses GameActivity from the Android Game SDK. It initializes the native library and sets up an immersive full-screen mode.

### main.cpp

This file contains the rendering code using OpenGL ES. It sets up the shaders, buffers, and renders the frame.

### CMakeLists.txt

This file defines the CMake configuration for building the native libraries.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests with your improvements.

## Reference
[https://github.com/DanAlbert/ndk-app-template](https://github.com/DanAlbert/ndk-app-template)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy coding! If you have any questions, feel free to open an issue or contact the project maintainers.