# Target downloads

Android application downloads and update information for Target.

The next preview is version 0.1.2 (Android version code 3). Download links will be available here after a release is published.

## Publish an update

1. Create a release with a version tag such as v0.1.2.
2. Attach the verified APK using the exact asset name Target.apk.
3. Include the following line in the release notes for version 0.1.2.

```text
Version-Code: 3
```

4. Add concise change notes and publish the release as the latest release. The app's Check for Updates reads the latest published release and validates that Target.apk is uploaded.
5. For every later update, increase the Android versionCode in the app build and use that same number in the release note.

Keep the Android application ID and signing identity consistent across updates. The current APKs are previews using a test signing identity. Owner-controlled release signing and device upgrade acceptance are pending.

All stored sales and company data belong to each installation. Publish only the application APK.
