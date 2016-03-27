FirebaseUI: Simplyify Mobile Development with Firebase
======================================================

FirebaseUI is a library that allows developers to quickly build native mobile applications with Firebase by binding common UI views to Firebase references or queries. Currently FirebaseUI supports `ListViews`, `GridViews`, and `RecyclerViews` on Android through custom Firebase Adapters and `UITableViews` and `UICollectionViews` on iOS through custom Data Sources.

These views are populated with the appropriate `child_added`, `child_changed`, `child_removed`, and `child_moved` events as they occur at the Firebase reference with no additional developer overhead. Additionally, the Adapters and Data Sources can easily be subclassed to add additional functionality  with little additional overhead.

FirebaseUI is built on top of [Firebase](https://www.firebase.com/?utm_source=firebaseui) for realtime data storage and synchronization. [Sign up](https://www.firebase.com/signup?utm_source=firebaseui) for a free account today!

# FirebaseUI Clients
FirebaseUI is available for both native mobile clients:
  1. [Android](https://github.com/firebase/FirebaseUI-Android)
  1. [iOS](https://github.com/firebase/FirebaseUI-iOS)

Clients feature similar functionality and a similar API, though there are several platform specific differences.

# Installing FirebaseUI
## Android
Add the following line to your `build.gradle` dependencies:
```
compile 'com.firebaseui.firebase-ui:0.3.1'
```
Resync your project and you should be able to use FirebaseUI.

More information on Android installation can be found [here](https://github.com/firebase/FirebaseUI-Android#installation).

## iOS
Add the following line to your `Podfile`:
```
pod 'FirebaseUI', '~> 0.3.2'
```

If you're using Swift, remember to add:
```
platform :ios, '8.0'
use_frameworks!
```
Run `pod install` in your terminal, open the project's workspace, and you should be able to import FirebaseUI.

More information on iOS installation can be found [here](https://github.com/firebase/FirebaseUI-iOS#installing-firebaseui-for-ios).

# Firebase UI Features

## Android

Feature  | Description
------------- | -------------
[FirebaseListAdapter](https://firebaseui.com/docs/android/index.html)  | Binds a Firebase ref or query to a ListAdapter, which can populate a ListView or GridView.
[FirebaseRecyclerViewAdapter](https://firebaseui.com/docs/android/index.html) | Binds a Firebase ref or query to a RecyclerView.

## iOS

Feature  | Description
------------- | -------------
[UITableViewDataSource](https://firebaseui.com/docs/ios/Classes/FirebaseTableViewDataSource.html)  | Binds a Firebase ref or query to a UITableView.
[UICollectionViewDataSource](https://firebaseui.com/docs/ios/Classes/FirebaseCollectionViewDataSource.html) | Binds a Firebase ref or query to a UICollectionView.

## Roadmap
FirebaseUI plans to add several more features, including standard auth controls, pagination/infinite scroll, and navigation. See [Contributing](https://github.com/firebase/FirebaseUI#contributing) below for more information on how to get involved.

# Website
This repo contains the source for the [FirebaseUI](https://firebaseui.firebaseapp.com) main website, which was build with [Material Lite](https://www.getmdl.io) and inspired by the [Android Material template](http://www.getmdl.io/templates/android-dot-com/index.html) and the [Android](https://www.android.com) main site. The site is hosted on [Firebase Hosting](https://www.firebase.com/hosting.html?utm_source=firebaseui).

# Support
Firebase has excellent community driven support to help you develop amazing apps.
  1. [Stack Overflow](http://stackoverflow.com/questions/tagged/firebase)
  1. [Firebase Talk Google Group](https://groups.google.com/forum/#!forum/firebase-talk)
  1. GitHub Issues for [Android](https://github.com/firebase/FirebaseUI-Android/issues) and [iOS](https://github.com/firebase/FirebaseUI-iOS/issues)

# Contributing
We would love for you to contribute to FirebaseUI! Please see the [Android](https://github.com/firebase/FirebaseUI-Android#contributing-a-patch) or [iOS](https://github.com/firebase/FirebaseUI-iOS#contributing-to-firebaseui) repos for more information on contributing to each project.
