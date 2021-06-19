
![Alt text](/img/logo.png)

Realm is a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the iOS, macOS, tvOS & watchOS versions of Realm Swift & Realm Objective-C.

##### Features
___

- Mobile-first: Realm is the first database built from the ground up to run directly inside phones, tablets and wearables.
- Simple: Data is directly exposed as objects and queryable by code, removing the need for ORM's riddled with performance & maintenance issues. Most of our users pick it up intuitively, getting simple apps up & running in minutes.
- Modern: Realm supports relationships, generics, vectorization and Swift.
- Fast: Realm is faster than even raw SQLite on common operations, while maintaining an extremely rich feature set.

##### Getting Started
___
Please see the detailed instructions in our docs to add [Realm Objective-C](https://docs.mongodb.com/realm-legacy/docs/objc/latest/#installation) or [Realm Swift](https://docs.mongodb.com/realm-legacy/docs/swift/latest/#installation) to your Xcode project.

##### Documentation
___
#### Realm Objective-C
The documentation can be found at [realm.io/docs/objc/latest.](https://docs.mongodb.com/realm-legacy/docs/objc/latest/)
The API reference is located at [realm.io/docs/objc/latest/api/.](https://docs.mongodb.com/realm-legacy/docs/objc/latest/)

#### Realm Swift
The documentation can be found at [realm.io/docs/swift/latest.](https://docs.mongodb.com/realm-legacy/docs/objc/latest/)
The API reference is located at [realm.io/docs/swift/latest/api/.](https://docs.mongodb.com/realm-legacy/docs/objc/latest/)

##### Getting Help
___
- Need help with your code?: Look for previous questions with therealm tag on Stack Overflow or ask a new question. For general discussion that might be considered too broad for Stack Overflow, use the Community Forum.
- Have a bug to report? Open a GitHub issue. If possible, include the version of Realm, a full log, the Realm file, and a project that shows the issue.
- Have a feature request? Open a GitHub issue. Tell us what the feature should do and why you want the feature.

#### Building Realm
___

In case you don't want to use the precompiled version, you can build Realm yourself from source.

Prerequisites:

- Building Realm requires Xcode 11.x or newer.
- Building Realm documentation requires [jazzy](https://github.com/realm/jazzy)
Once you have all the necessary prerequisites, building Realm.framework just takes a single command: sh build.sh build. You'll need an internet connection the first time you build Realm to download the core binary.

Run sh build.sh help to see all the actions you can perform (build ios/osx, generate docs, test, etc.).

#### Contributing
___
See [CONTRIBUTING.md](https://github.com/realm/realm-cocoa/blob/master/CONTRIBUTING.md) for more details!

This project adheres to the [Contributor Covenant Code of Conduct.](https://github.com/realm/realm-cocoa/blob/master/CONTRIBUTING.md) By participating, you are expected to uphold this code. Please report unacceptable behavior to info@realm.io.

#### License
___
Realm Objective-C & Realm Swift are published under the Apache 2.0 license.
Realm Core is also published under the Apache 2.0 license and is available [here.](https://github.com/realm/realm-core)

This product is not being made available to any person located in Cuba, Iran, North Korea, Sudan, Syria or the Crimea region, or to any other person that is not eligible to receive the product under U.S. law.

#### Feedback
___
*** If you use Realm and are happy with it, all we ask is that you please consider sending out a tweet mentioning [@realm](https://twitter.com/realm) to share your thoughts!

And if you don't like it, please let us know what you would like improved, so we can fix it! ***