# Pose Estimation

[![Twitter](https://img.shields.io/badge/twitter-@fritzlabs-blue.svg?style=flat)](http://twitter.com/fritzlabs)

In this app, we use the Pose Estimation API by Fritz in order to identify and track the movement of different human poses.

For the full tutorial, visit [our post on Heartbeat](https://heartbeat.fritz.ai/pose-estimation-on-ios-with-fritz-60c8e5f7d195).

<img src="images/pose_estimation_ios.jpg" width="250" />

## Fritz AI

Fritz AI is the machine learning platform for iOS and Android developers. Teach your mobile apps to see, hear, sense, and think. Start with our ready-to-use feature APIs or connect and deploy your own custom models.

## Requirements

- Xcode 11.2 or later.
- Xcode project targeting iOS 10 or above. You will only be able to use features in iOS 11+, but you still can include Fritz in apps that target iOS 10+ and selectively enable for users on 11+.
- Swift projects must use Swift 4.1 or later.
- CocoaPods 1.4.0 or later.

## Getting Started

**Step 1: Create a Fritz AI Account**

[Sign up](https://app.fritz.ai/register?utm_source=github&utm_campaign=fritz-examples) for a free account on Fritz AI in order to get started.

**Step 2: Clone / Fork the fritz-examples repository and open FritzPoseEstimationDemo**

```
git clone https://github.com/fritzlabs/fritz-examples.git
```

**Step 3: Setup the project via Cocoapods**

Install dependencies via Cocoapods by running `pod install` from `fritz-examples/iOS/FritzPoseEstimationDemo`

```
cd fritz-examples/iOS/FritzPoseEstimationDemo
pod install
```

- Note you may need to run `pod update` if you already have Fritz installed locally.

**Step 4: Open up a new XCode project**

XCode > Open > FritzPoseEstimationDemo.xcworkspace

**Step 5: Run the app**

Attach a device or use an emulator to run the app. If you get the error "Please download the Fritz-Info.plist", you'll need to register the app with Fritz (See Step 2).

## Documentation

[Fritz Docs Home](https://docs.fritz.ai/?utm_source=github&utm_campaign=fritz-examples)

[iOS SDK Reference Docs](https://docs.fritz.ai/iOS/latest/index.html?utm_source=github&utm_campaign=fritz-examples)

## Join the community

[Heartbeat](https://heartbeat.fritz.ai/?utm_source=github&utm_campaign=fritz-examples) is a community of developers interested in the intersection of mobile and machine learning. [Chat with us in Slack](https://www.fritz.ai/slack?utm_source=github&utm_campaign=fritz-examples) and stay up to date on the latest mobile ML news with our [Newsletter](https://mobileml.us16.list-manage.com/subscribe?u=de53bead690affb8e9a21de8f&id=68acb5c0fd).

## Help

For any questions or issues, you can:

- Submit an issue on this repo
- Go to our [Help Center](https://docs.fritz.ai/help-center/index.html?utm_source=github&utm_campaign=fritz-examples)
- Message us directly in [Slack](https://www.fritz.ai/slack?utm_source=github&utm_campaign=fritz-examples)
