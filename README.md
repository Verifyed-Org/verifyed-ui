# verifyed-ui

## Run Instructions

### Android

1. Have an Android emulator running (quickest way to get started), or a device connected.
2. Run:
   ```sh
   cd app
   npx react-native run-android
   ```

### iOS

1. Run:
   ```sh
   cd app
   npx react-native run-ios
   ```
   **or**
2. Open the project in Xcode:
   ```sh
   cd app
   xed -b ios
   ```
   - Or open `app/ios/app.xcodeproj` in Xcode manually.
   - Hit the **Run** button in Xcode.

### macOS

- See [React Native Guide for macOS](https://aka.ms/ReactNativeGuideMacOS) for the latest instructions.

### Running iOS locally (Developers)

```sh
cd ios
pod install
pod install --repo-update
open open.xcworkspace
# In Xcode: CMD + R to run
cd ..
npm run start
```

---

## Running App (Non-Developers)

Contact the Tech Lead to request access.

### For iOS (TestFlight)

- Download the TestFlight app.

### For Android

- Build `.apk` or `.aab` files.
- Distribute via Firebase App Distribution.

npm install -g firebase-tools
