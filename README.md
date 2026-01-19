<div align="center">

# sandbox-ios

[![Swift](https://img.shields.io/badge/Swift-5.9-F05138.svg?logo=swift&logoColor=white)](https://swift.org)
[![iOS](https://img.shields.io/badge/iOS-17.0+-007AFF.svg?logo=apple&logoColor=white)](https://developer.apple.com/ios/)
[![Xcode](https://img.shields.io/badge/Xcode-15+-147EFB.svg?logo=xcode&logoColor=white)](https://developer.apple.com/xcode/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**A minimal SwiftUI sandbox for rapid iOS experimentation and prototyping**

</div>

## Overview

Skip the boilerplate and start building. This lightweight iOS starter gives you a clean SwiftUI foundation for testing concepts, exploring new APIs, and prototyping features without project setup overhead.

## Features

- **Zero configuration** - Open in Xcode and run immediately
- **Modern SwiftUI** - Uses `@main` app lifecycle and latest Swift features
- **iOS 17+ ready** - Target the latest platform capabilities
- **Minimal footprint** - Just the essentials, nothing more

## Quick Start

**Option 1: Xcode**
```bash
open HelloWorld/HelloWorld.xcodeproj
```
Then press `⌘R` to build and run.

**Option 2: Command Line**
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
  -scheme HelloWorld \
  -sdk iphonesimulator \
  -configuration Debug build

# Release build
xcodebuild -project HelloWorld/HelloWorld.xcodeproj \
  -scheme HelloWorld \
  -configuration Release build

# Clean
xcodebuild -project HelloWorld/HelloWorld.xcodeproj \
  -scheme HelloWorld clean
```

## License

MIT
