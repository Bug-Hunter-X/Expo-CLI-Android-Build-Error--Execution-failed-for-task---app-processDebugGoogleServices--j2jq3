# Expo CLI Android Build Error: Execution failed for task ':app:processDebugGoogleServices'

This repository demonstrates a common error encountered when building Android APKs using the Expo CLI, specifically the `Execution failed for task ':app:processDebugGoogleServices'` error. This error typically arises from inconsistencies between the `google-services.json` file and project dependencies.

## Problem

The bug.js file illustrates a scenario where the `google-services.json` configuration is incorrect, leading to a failed build process.

## Solution

The bugSolution.js file provides a solution by outlining how to correct the `google-services.json` configuration and resolve dependency conflicts.

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Attempt to build the Android APK using `expo build:android`. Observe the error.
4. Apply the solution steps from bugSolution.js.
5. Re-run the build command and verify successful compilation.

## Solution Details

The solution usually involves verifying the accuracy of the `google-services.json` file, ensuring compatibility with the Firebase SDK version, and resolving any dependency conflicts between Google services and other project libraries. The file should be updated from your Firebase project to reflect the correct configurations for your project.