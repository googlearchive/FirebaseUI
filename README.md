FirebaseUI: Simplyify Mobile Development with Firebase
======================================================

FirebaseUI is a library that provides common UI elements when building apps. This includes a 
* basic Auth flow implementation on web, Android, and iOS
* bindings for `ListViews`, `GridViews`, and `RecyclerViews` in Android through custom Firebase Adapters
* bindings for `UITableViews` and `UICollectionVIews` on iOs through custom Data Sources.

These views are populated with the appropriate `child_added`, `child_changed`, `child_removed`, and `child_moved` events as they occur at the Firebase reference with no additional developer overhead. Additionally, the Adapters and Data Sources can easily be subclassed to add additional functionality  with little additional overhead.

FirebaseUI is built on top of [Firebase](https://www.firebase.com/?utm_source=firebaseui) for realtime data storage and synchronization. [Sign up](https://www.firebase.com/signup?utm_source=firebaseui) for a free account today!

# FirebaseUI Clients
FirebaseUI is available in:
  1. [Android](https://github.com/firebase/FirebaseUI-Android)
  1. [iOS](https://github.com/firebase/FirebaseUI-iOS)
  1. [Web](https://github.com/firebase/firebaseui-web)

Clients feature similar functionality and a similar API, though there are several platform specific differences.

# Installing FirebaseUI
## Android

Information on Android installation can be found [here](https://github.com/firebase/FirebaseUI-Android#installation).

## iOS

Information on iOS installation can be found [here](https://github.com/firebase/FirebaseUI-iOS#installing-firebaseui-for-ios).

## Web

Information on web installation can be found [here](https://github.com/firebase/firebaseui-web#user-content-installation).

# Firebase UI Features

## Android

Feature  | Description
------------- | -------------
[FirebaseListAdapter](https://firebaseui.com/docs/android/index.html)  | Binds a Firebase ref or query to a ListAdapter, which can populate a ListView or GridView.
[FirebaseRecyclerViewAdapter](https://firebaseui.com/docs/android/index.html) | Binds a Firebase ref or query to a RecyclerView.
[Firebase Auth UI](https://github.com/firebase/FirebaseUI-Android/tree/master/auth) | UI flows for Authentication

## iOS

Feature  | Description
------------- | -------------
[UITableViewDataSource](https://firebaseui.com/docs/ios/Classes/FirebaseTableViewDataSource.html)  | Binds a Firebase ref or query to a UITableView.
[UICollectionViewDataSource](https://firebaseui.com/docs/ios/Classes/FirebaseCollectionViewDataSource.html) | Binds a Firebase ref or query to a UICollectionView.
[Firebase Auth UI](https://github.com/firebase/FirebaseUI-iOS/tree/master/FirebaseAuthUI) | UI flows for Authentication

## Web
Feature  | Description
------------- | -------------
[Firebase Auth UI](https://github.com/firebase/firebaseui-web) | UI flows for Authentication


## Roadmap
FirebaseUI plans to add several more features, including standard auth controls, pagination/infinite scroll, and navigation. See [Contributing](https://github.com/firebase/FirebaseUI#contributing) below for more information on how to get involved.

# Website
This repo contains the source for the [FirebaseUI](https://firebaseui.firebaseapp.com) main website, which was build with [Material Lite](https://www.getmdl.io) and inspired by the [Android Material template](http://www.getmdl.io/templates/android-dot-com/index.html) and the [Android](https://www.android.com) main site. The site is hosted on [Firebase Hosting](https://www.firebase.com/hosting.html?utm_source=firebaseui).

# Support
Firebase has excellent community driven support to help you develop amazing apps.
  1. [Stack Overflow](http://stackoverflow.com/questions/tagged/firebase)
  1. [Firebase Talk Google Group](https://groups.google.com/forum/#!forum/firebase-talk)
  1. GitHub Issues for [Android](https://github.com/firebase/FirebaseUI-Android/issues) and [iOS](https://github.com/firebase/FirebaseUI-iOS/issues)
  1. The [Firebase Community on Slack](http://firebase-community.appspot.com/)

# Contributing
We would love for you to contribute to FirebaseUI! Please see the [Android](https://github.com/firebase/FirebaseUI-Android#contributing-a-patch) or [iOS](https://github.com/firebase/FirebaseUI-iOS#contributing-to-firebaseui) repos for more information on contributing to each project.
