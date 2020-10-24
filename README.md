# neighborhood-alerts
[![Build Status](https://travis-ci.com/jeffw16/neighborhood-alerts.svg?token=K8cPugKdgwZ3CAtTDsHu&branch=master)](https://travis-ci.com/jeffw16/neighborhood-alerts)

Neighborhood Alerts is an app that delivers time-sensitive alerts to geographically relevant recipients.  Published on the iOS App Store, download at: https://apps.apple.com/us/app/neighborhood-alerts/id1521202368

## Development

This is an iOS app written in Swift 5. (One dependency is written in Swift 4.) All new improvements should be written with Swift 5 whenever possible.

This project's dependencies are managed through CocoaPods. To install them, type `pod install` in the root directory of your local copy of this repo.

When making changes to this project, be sure you're in the workspace rather than the project. You can do so by opening the `Neighborhood Alerts.xcworkspace` file rather than the `Neighborhood Alerts.xcodeproj` file.

This app is published to the App Store by MyWikis LLC. By making changes to this repo, you agree to release your changes to the ownership of MyWikis LLC, in order to publish the changes to the app to the App Store.

## Dependencies

* Firebase
  * Firebase Auth
  * Firebase Firestore
  * Firebase Storage
* LocationPicker with edits, available at https://github.com/jeffw16/LocationPicker

## Credits

Original code contributions by Jeffrey Wang (@jeffw16) and Amit Joshi (@amitjoshi24), with additional contributions by Gunjan Bhattarai (@Gunjan-Bhattarai). This app was developed as the final project for UT Austin's CS 371L iOS Mobile Computing class in Summer 2020.
