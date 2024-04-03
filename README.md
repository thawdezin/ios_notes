# iOS

### Suppressing Layout Warning in Xcode

If you encounter a layout warning in Xcode that you want to temporarily suppress in your console output, you can follow these steps:

1. Open your Xcode project.
2. Go to the "Product" menu, then select "Scheme" > "Edit Scheme...".
3. In the left sidebar of the Scheme editor, select "Run" (or whichever action you're using).
4. In the "Environment Variables" section, click the "+" button to add a new environment variable.
5. Enter `OS_ACTIVITY_MODE` for the "Name" and set its value to `disable`.

Keep in mind that suppressing warnings should be done with caution and only as a temporary measure. It's recommended to address the underlying issues causing the warnings for a more robust and maintainable solution.


### Multiple commands produce
Could not build the precompiled application for the device.
Error (Xcode): Multiple commands produce '/Users/mac/StudioProjects/april/build/ios/Debug-iphoneos/Runner.app/GoogleService-Info.plist'

Target > Build Phase > Copy Bundle Resoures မှာ .plist တွေ ထပ်နေလို့
