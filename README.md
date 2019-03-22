# hello_flutter

Aaron's Test Flutter Project.

# building and running notes
* needed to run `flutter doctor` and go thru checklist of installs + brew installs

* for android, had to open android studio and run SDK manager downloads, then it just worked.

* for ios, had to generate flutter project then open the xcworkspace in xcode and select provisioning profile

* also required apple developer id signin inside xcode, and generate iOS dev certificate associated with apple ID
* on iOS device, select General > Device Management and trust your Certificate when app first deploys

* also on ios... had to make sure to create a unique bundle identifier in xcode after selecting my apple id generated provision as 'my name' (personal team) - the bundle identifier is: (com.example.uniqueprojectname)

* used some of the workaround steps here
 https://github.com/flutter/flutter/issues/26123

 * key features -- had to open xcode/android studio once each to setup, but afterwards can develop and debug completely from VSCode (or Android Studio)

## Flutter Getting Started Links

Flutter project resources:
- [Lab: Write your first Flutter app](https://flutter.io/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.io/docs/cookbook)

For help getting started with Flutter, view our 
[online documentation](https://flutter.io/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
