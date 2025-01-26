# React Native: Unhandled JS Exception: Native Module Cannot Be Null

This repository demonstrates a common React Native error related to missing native modules and provides a solution.

## Problem

When integrating native modules into a React Native application, you might encounter an error like:

```
Unhandled JS Exception: Native module cannot be null
```

This usually happens if the native module isn't correctly linked to your JavaScript code, often due to misconfiguration during the installation or build process.

## Solution

The solution involves verifying the native module installation and linking steps, ensuring proper configuration for both Android and iOS platforms. This often involves verifying the correct installation of the native module via npm/yarn and correctly performing the autolinking (if supported) or manual linking of the module.