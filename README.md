# ABGaugeViewKit
> A light weight GaugeView to make your app awesome.

[![Swift Version][swift-image]][swift-url]
[![License][license-image]][license-url]
[![CocoaPods Compatible](https://img.shields.io/cocoapods/v/EZSwiftExtensions.svg)](https://img.shields.io/cocoapods/v/LFAlertController.svg)  
[![Platform](https://img.shields.io/cocoapods/p/LFAlertController.svg?style=flat)](http://cocoapods.org/pods/LFAlertController)

 ABGaugeViewKit is a framework with a lot of access to change it's UI which will help you to add Gauge View in your iOS App.

Refer [Medium] for integration tutorial
<a href="https://imgflip.com/gif/25lu0h"><img src="https://i.imgflip.com/25lu0h.gif" title="made at imgflip.com"/></a>

## Features

- [x] Codeless Implementation
- [x] Vector Based

## Requirements

- iOS 12.0+
- Xcode 9.0
- Swift 5.0+

## Installation
#### Swift Package Manager
1. Open your Xcode project.
2. Go to File -> Swift Packages -> Add Package Dependency...
3. Search for ABGaugeViewKit or Enter the repository URL: https://github.com/AjayBhanushali/ABGaugeViewKit.git
4. Choose the version rule according to your preference.
5. Choose the target where you want to integrate ABGaugeViewKit.
6. Click Finish.

#### CocoaPods
You can use [CocoaPods](https://cocoapods.org/pods/ABGaugeViewKit) to install `ABGaugeViewKit` by adding it to your `Podfile`:

```ruby
platform :ios, '11.0'
use_frameworks!
pod 'ABGaugeViewKit'
```

## Usage example

```swift
import ABGaugeViewKit

//Create an IBOutlet from Storyboard of UIView
// Note: UIView must be a square for best output!
@IBOutlet weak var myGaugeView: ABGaugeView!

// To change needle value
// Note: Needle value should in between 0 to 100
myGaugeView.needleValue = 100
```

## Contribute

We would love you for the contribution to **ABGaugeViewKit**, check the ``LICENSE`` file for more info.

## Meta

Ajay Bhanushali – [LinkedIn](https://www.linkedin.com/in/ajaybhanushali/) – ajayrbhanushali@gmail.com

Distributed under the MIT license. See ``LICENSE`` for more information.

[GitHub](https://github.com/AjayBhanushali)

[swift-image]:https://img.shields.io/badge/swift-5.0-orange.svg
[swift-url]: https://swift.org/
[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[codebeat-image]: https://codebeat.co/badges/c19b47ea-2f9d-45df-8458-b2d952fe9dad
[codebeat-url]: https://codebeat.co/projects/github-com-vsouza-awesomeios-com
[Medium]: https://medium.com/ajay-bhanushali/create-gaugeview-speedometer-in-swift-571ff97d1a68
