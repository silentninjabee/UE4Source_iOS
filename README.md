# UE4Source_iOS

## Overview

The **UE4Source_iOS** project aims to port external Unreal Engine 4 (UE4) source code, originally developed for Windows, to be compatible with Apple's iOS platform by creating a dynamic library (`.dylib`). This enables the integration of existing UE4 functionalities into iOS applications, facilitating cross-platform development and deployment.

## Repository Contents

- `Cheats.cpp` / `Cheats.h`: Implements cheat functionalities tailored for iOS compatibility.
- `Tweak.xm`: (Equivalent to Windows' `Main.cpp`) Serves as the primary entry point for the dynamic library.
- `Memory.cpp` / `Memory.h`: Manages memory operations, ensuring efficient handling within the iOS environment.
- `Offsets.h`: Contains memory offset definitions pertinent to iOS.
- `classes.cpp`: Provides implementations for the classes defined in `Classes.h`.
- `Classes.h`: Defines core classes and data structures essential for the project.

## Build and Package

- Utilize Theos to build a dynamic library and create a jailbreak-compatible tweak package as a `.deb` file.
