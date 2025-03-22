# Essentia Static Libraries

This repository contains pre-built static libraries for the [Essentia](https://essentia.upf.edu/) audio analysis library, specifically compiled for use with React Native.

## Structure

- `ios/`: Contains static libraries for iOS (device and simulator)
- `android/`: Contains static libraries for Android (multiple architectures)
- `cpp/include/`: Contains C++ header files needed for compilation

## Usage

These binary files are meant to be used with [@siteed/react-native-essentia](https://www.npmjs.com/package/@siteed/react-native-essentia).

## Version

These libraries are built from Essentia version 2.1_beta5.
Last built: 2025-03-22 17:24:17
Package version: 0.3.0-beta.2

## Building

These libraries were built and published using:
1. `./setup.sh` - Sets up the Essentia source code
2. `./build-essentia-ios.sh` - Builds iOS libraries
3. `./build-essentia-android.sh --all` - Builds Android libraries
4. `./publish-static-libs.sh` - Copies libraries to this repository

## License

The Essentia library is licensed under the Affero GPLv3 license. See the [Essentia project](https://github.com/MTG/essentia) for more details.
