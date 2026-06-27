# LAST ZONE iOS

This folder contains the Swift iOS wrapper project.

## Build On Mac

1. Open `LAST-ZONE-iOS.xcodeproj` in Xcode.
2. Choose your Apple development team under Signing & Capabilities.
3. Archive the app and export an `.ipa`.

## Build On Codemagic

1. Connect this repository to Codemagic.
2. Add your Apple signing credentials in Codemagic.
3. Run the `ios-workflow` from `codemagic.yaml`.
4. Download the generated `.ipa` artifact.

## Bundle Identifier

`SecurityHelper.swift` now reads the expected bundle identifier from `Info.plist`. Change `PRODUCT_BUNDLE_IDENTIFIER` in Xcode or Codemagic if you want a different app ID.
