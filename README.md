<p align="center">
    <img src="readme-resources/Banner.png" style="max-height: 61px;" alt="MessengerKit for iOS">
</p>

<p align="center">
    <a href="https://opensource.org/licenses/MIT">
        <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
    </a>
</p>

---

## About

This an updated version of [MessengerKit](https://github.com/steve228uk/MessengerKit), a drop-in UI for messenger interfaces on iOS built in Swift. Centred around a single `UIViewController`, MessengerKit is themeable to fit your needs and includes a number of powerful features:

- [x] `UICollectionView` based with pre-loading and caching of size calculation for bubbles.
- [x] Auto-growing input view.
- [x] Multiple cell types: text, large-emoji, image, video, location and gifs.
- [x] Presentation of `SFSafariViewController`
- [x] Built-in, customisable themes.
- [x] A custom theming system to bring your own `UICollectionViewCell`s, headers, footers, and input views.
- [x] Avatar support (currently only in the `travamigos` theme).

The framework is actively being used and maintained in one of our apps, [Vivus](http://vivushub.com/?adFor=social&ref=github).

## Screenshots

<p align="center">
    <img src="readme-resources/screenshots/examples.png" alt="MessengerKit Examples">
</p>

## Documentation

- [Getting Started](https://github.com/steve228uk/MessengerKit/wiki/Getting-Started)
- [Customising an Existing Style](https://github.com/steve228uk/MessengerKit/wiki/Customising-an-Existing-Style)
- [Creating a Custom Style](https://github.com/steve228uk/MessengerKit/wiki/Creating-a-Custom-Style)

## Installation

MessengerKit requires Swift 4.2 and iOS 11.0 or later.

### Manual

Drag the contents of the `MessengerKit` folder into your Xcode Project.

### CocoaPods

Add the following to your project's Podfile.

```ruby
pod 'MessengerKit', :git => 'https://github.com/VivusHub/MessengerKit.git'
```

## Credits

* Orginally written by [@steve228uk](https://twitter.com/steve228uk).
* Updated by [@VivusHub](https://twitter.com/vivushub).
* It makes use of [KeyboardUtility](https://github.com/JunyuKuang/KeyboardUtility) by [@JunyuKuang](https://github.com/JunyuKuang).
