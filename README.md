<div align="center">
  <img src="logo.png" alt="sandbox-ios" width="200"/>

  # sandbox-ios

  [![Swift](https://img.shields.io/badge/Swift-5.9-F05138.svg?style=flat&logo=swift&logoColor=white)](https://swift.org)
  [![iOS](https://img.shields.io/badge/iOS-17.0+-007AFF.svg?style=flat&logo=apple&logoColor=white)](https://developer.apple.com/ios/)
  [![Xcode](https://img.shields.io/badge/Xcode-15+-147EFB.svg?style=flat&logo=xcode&logoColor=white)](https://developer.apple.com/xcode/)
  [![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat)](LICENSE)

  **Skip the boilerplate and start building iOS apps in seconds**

</div>

## Overview

A minimal SwiftUI starter for rapid iOS experimentation. Open in Xcode and run immediately - no configuration, no setup ceremony, just a clean foundation for testing concepts and prototyping features.

## Features

- **Zero configuration** - Clone, open, run. That's it.
- **Modern SwiftUI** - `@main` app lifecycle with latest Swift 5.9 features
- **iOS 17+ ready** - Target the newest platform capabilities out of the box
- **Minimal footprint** - Just the essentials, add what you need

## Quick Start

```bash
open HelloWorld/HelloWorld.xcodeproj
```

Press `Cmd+R` to build and run.

### Command Line Build

```bash
xcodebuild -project HelloWorld/HelloWorld.xcodeproj \
  -scheme HelloWorld \
  -sdk iphonesimulator \
  -configuration Debug build
```

## Requirements

| Requirement | Version |
|-------------|---------|
| iOS | 17.0+ |
| Xcode | 15+ |
| Swift | 5.9+ |
| macOS | Sonoma 14.0+ |

## Project Structure

```
HelloWorld/
├── HelloWorld/
│   ├── HelloWorldApp.swift    # @main app entry point
│   ├── ContentView.swift      # Main SwiftUI view
│   └── Assets.xcassets/       # App assets
└── HelloWorld.xcodeproj/      # Xcode project
```

## Build Commands

```bash
# Debug build for simulator
xcodebuild -project HelloWorld/HelloWorld.xcodeproj \
  -scheme HelloWorld -sdk iphonesimulator -configuration Debug build

# Release build
xcodebuild -project HelloWorld/HelloWorld.xcodeproj \
  -scheme HelloWorld -configuration Release build

# Clean
xcodebuild -project HelloWorld/HelloWorld.xcodeproj \
  -scheme HelloWorld clean
```

## License

MIT
