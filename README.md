# NOTE: This fork made to fix the following issue.

Build error: 'React/RCTImageLoaderProtocol.h' file not found.

[Issue discussion](https://github.com/itinance/react-native-fs/issues/791)

### Enviroment
react-native: 0.60.3

react-native-fs: 2.16.6

react-native-maps: 0.27.1


### Changed #import <React/RCTImageLoaderProtocol.h> -> #import <React/RCTImageLoader.h> in following files:

lib/ios/AirGoogleMaps/AIRGoogleMapMarker.m

lib/ios/AirGoogleMaps/AIRGoogleMapOverlay.m

lib/ios/AirMaps/AIRMapMarker.m

lib/ios/AirMaps/AIRMapOverlay.m


# react-native-maps [![npm version](https://img.shields.io/npm/v/react-native-maps.svg?style=flat)](https://www.npmjs.com/package/react-native-maps)

React Native Map components for iOS + Android

## Installation

See [Installation Instructions](docs/installation.md).

See [Setup Instructions for the Included Example Project](docs/examples-setup.md).

## Compatibility

Due to the rapid changes being made in the React Native ecosystem, we are not officially going to
support this module on anything but the latest version of React Native. With that said, we will do
our best to stay compatible with older versions as much that is practical, and the peer dependency
of this requirement is set to `"react-native": "*"` explicitly for this reason. If you are using
an older version of React Native with this module though, some features may be buggy.

### Note about React requires

Since react-native 0.25.0, `React` should be required from `node_modules`.
React Native versions from 0.18 should be working out of the box, for lower
versions you should add `react` as a dependency in your `package.json`.

## Forked from [react-native-maps](https://github.com/react-native-community/react-native-maps)
