<div align="center">

# sandbox-ios

[![Swift](https://img.shields.io/badge/Swift-5.9-orange.svg)](https://swift.org)
[![iOS](https://img.shields.io/badge/iOS-17.0+-blue.svg)](https://developer.apple.com/ios/)
[![Xcode](https://img.shields.io/badge/Xcode-15+-blue.svg)](https://developer.apple.com/xcode/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**Minimal SwiftUI sandbox for rapid iOS experimentation and prototyping**

</div>

## Overview

A lightweight iOS starter project for quickly testing SwiftUI concepts, experimenting with new APIs, and prototyping features without the overhead of a full application setup.

## Quick Start

```bash
# Clone and build
git clone https://github.com/tsilva/sandbox-ios.git
cd sandbox-ios
xcodebuild -project HelloWorld/HelloWorld.xcodeproj -scheme HelloWorld -sdk iphonesimulator build
```

Or open `HelloWorld/HelloWorld.xcodeproj` in Xcode and press `⌘R`.

## Requirements

| Requirement | Version |
|-------------|---------|
| iOS | 17.0+ |
| Xcode | 15+ |
| Swift | 5.9+ |

## Project Structure

```
HelloWorld/
├── HelloWorld/
│   ├── HelloWorldApp.swift    # @main app entry point
│   ├── ContentView.swift      # Main SwiftUI view
│   └── Info.plist             # App configuration
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
