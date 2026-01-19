# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build Commands

```bash
# Build the project
xcodebuild -project HelloWorld/HelloWorld.xcodeproj -scheme HelloWorld -configuration Debug build

# Build for simulator
xcodebuild -project HelloWorld/HelloWorld.xcodeproj -scheme HelloWorld -sdk iphonesimulator -configuration Debug build

# Clean build
xcodebuild -project HelloWorld/HelloWorld.xcodeproj -scheme HelloWorld clean
```

## Architecture

This is a minimal SwiftUI iOS app targeting iOS 17.0+. The project uses the standard Xcode project structure:

- `HelloWorld/HelloWorld/` - Source files
  - `HelloWorldApp.swift` - App entry point using SwiftUI App protocol
  - `ContentView.swift` - Main view
- `HelloWorld/HelloWorld.xcodeproj/` - Xcode project configuration

The app uses SwiftUI's declarative syntax with `@main` app lifecycle.
