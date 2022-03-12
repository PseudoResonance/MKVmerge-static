# MKVMerge static builds
Static builds for MKVMerge from [MKVToolNix](https://mkvtoolnix.download/source.html) using `docker`

## Current Release
* MKVMerge version: 58.0.0 for Linux, macOS

## Current Platforms
linux-i686, linux-amd64, linux-armhf, linux-aarch64, darwin-amd64, darwin-aarch64

## darwin-aarch64 (Apple Silicon) Information
Apple silicon requires that all executables are signed in order to be executed. This means you must first sign the ARM native binary first. An adhoc signature is sufficient, and can be applied with the following command on macOS with Xcode installed.
```
codesign -s - /path/to/binary
```
