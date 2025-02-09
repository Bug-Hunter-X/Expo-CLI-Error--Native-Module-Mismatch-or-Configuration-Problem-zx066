# Expo CLI Error: Native Module Incompatibility

This repository demonstrates a common Expo CLI error related to native module mismatches or configuration problems.  The error often involves `@react-native-community/masked-view`, but could be related to other native modules as well.  The `bug.js` file shows example code that might trigger the error, and `bugSolution.js` provides a potential solution.

## Reproducing the Error

1. Clone this repository.
2. Follow the instructions to install dependencies.
3. Run `expo start`.  You should encounter an error related to native modules.

## Solution

The solution file shows how to fix the error. Common fixes include updating dependencies, ensuring the correct configuration in `app.json` and `package.json`, and checking for conflicting packages.  See the solution for more detailed steps.