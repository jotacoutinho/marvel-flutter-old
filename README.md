![Flutter](https://img.shields.io/badge/sdk-Flutter-9cf)
![Dart](https://img.shields.io/badge/language-Dart-blue)
![Marvel](https://img.shields.io/badge/api-Marvel-red)
![Firebase](https://img.shields.io/badge/auth-Firebase-orange)

# marvel-flutter
This app is a content provider for Marvel universe (through Marvel API).

# Dependencies
This app requires CocoaPods to build the iOS version. 
Check the step-by-step instructions below to properly run the Xcode build.

* In the terminal, run ``(sudo) gem install cocoapods``

* Once it's installed, navigate to your project folder and run ``pod install``

* Open the desired IDE and run flutter's build

* You should now be able to run your app!

* If a build error occurs, try running ``pod update`` in the project folder, clean project and then build

* If the error persists: **clean** project, **revert** any changes made by CocoaPods (basically: delete Pods folder), and **delete** Podfile.lock. After that, run ``pod install``, ``pod update`` and **then** build the project.