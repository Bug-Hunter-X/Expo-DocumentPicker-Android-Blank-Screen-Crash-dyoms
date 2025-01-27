# Expo DocumentPicker Android Blank Screen/Crash

This repository demonstrates a bug in the Expo DocumentPicker API on Android, where launching the file picker results in a blank screen or an immediate app crash.  The issue lacks informative error messages, making debugging difficult.

The `bug.js` file contains the problematic code. The `bugSolution.js` file provides a workaround.

## Setup

1. Clone this repo.
2. `expo install expo-document-picker`
3. Run the app on an Android device or emulator.

## Reproduction

Run the `bug.js` example and attempt to select a file.  You'll likely encounter a blank screen or immediate app crash.

## Solution

The `bugSolution.js` file provides a solution that improves the chance of success.  It focuses on using alternative permissions requests and handling potential errors more robustly.

## Note

This bug might be related to specific Android versions, device configurations, or interactions with other libraries. Please report any additional information that may help in resolving the issue.