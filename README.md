# Expo Managed Workflow Native Module Incompatibility

This repository demonstrates a common issue encountered when using Expo's managed workflow: incompatibility with native modules.  Certain libraries rely on native code that isn't directly compatible with Expo Go, leading to runtime errors or unexpected behavior.

The `bug.js` file showcases example code that causes this problem. The `bugSolution.js` file provides a solution using Expo's recommended approach for handling native modules.

## Problem

Directly importing and using native modules without proper consideration for Expo's environment can result in silent failures or runtime errors. This is especially true when using libraries that haven't been explicitly designed for the Expo managed workflow.