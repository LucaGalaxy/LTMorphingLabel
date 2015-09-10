# LTMorphingLabel

[![CircleCI](https://img.shields.io/circleci/project/lexrus/LTMorphingLabel.svg)](https://github.com/lexrus/LTMorphingLabel)
[![CocoaPods](https://img.shields.io/cocoapods/v/LTMorphingLabel.svg?style=flat)](https://github.com/lexrus/LTMorphingLabel)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
![License](https://img.shields.io/github/license/lexrus/LTMorphingLabel.svg?style=flat)

[![Git](https://img.shields.io/badge/GitHub-lexrus-blue.svg?style=flat)](https://github.com/lexrus)
[![Twitter](https://img.shields.io/badge/twitter-@lexrus-blue.svg?style=flat)](http://twitter.com/lexrus)
[![LinkedIn](https://img.shields.io/badge/linkedin-Lex Tang-blue.svg?style=flat)](https://cn.linkedin.com/in/lexrus/en)
[![eMail](https://img.shields.io/badge/email-lexrus@gmail.com-blue.svg?style=flat)](mailto:lexrus@gmail.com?SUBJECT=About LTMorphingLabel)

A morphing UILabel subclass written in Swift.
The ```.Scale``` effect is originally introduced by Apple in WWDC 2014. New morphing effects are available as Swift extensions.

## enum LTMorphingEffect: Int, Printable

#### .Scale - _default_
<img src="https://cloud.githubusercontent.com/assets/219689/3491822/96bf5de6-059d-11e4-9826-a6f82025d1af.gif" width="300" height="70" alt="LTMorphingLabel"/>

#### [.Evaporate](https://github.com/lexrus/LTMorphingLabel/blob/master/LTMorphingLabel/LTMorphingLabel%2BEvaporate.swift)
<img src="https://cloud.githubusercontent.com/assets/219689/3491838/ffc5aff2-059d-11e4-970c-6e2d7664785a.gif" width="300" height="70" alt="LTMorphingLabel-Evaporate"/>

#### [.Fall](https://github.com/lexrus/LTMorphingLabel/blob/master/LTMorphingLabel/LTMorphingLabel%2BFall.swift)
<img src="https://cloud.githubusercontent.com/assets/219689/3491840/173c2238-059e-11e4-9b33-dcd21edae9e2.gif" width="300" height="70" alt="LTMorphingLabel-Fall"/>

#### [.Pixelate](https://github.com/lexrus/LTMorphingLabel/blob/master/LTMorphingLabel/LTMorphingLabel%2BPixelate.swift)
<img src="https://cloud.githubusercontent.com/assets/219689/3491845/29bb0f8c-059e-11e4-9ef8-de56bec1baba.gif" width="300" height="70" alt="LTMorphingLabel-Pixelate"/>

#### [.Sparkle](https://github.com/lexrus/LTMorphingLabel/blob/master/LTMorphingLabel/LTMorphingLabel%2BSparkle.swift)
<img src="https://cloud.githubusercontent.com/assets/219689/3508789/31e9fafe-0690-11e4-9a76-ba3ef45eb53a.gif" width="300" height="70" alt="LTMorphingLabel-Sparkle"/>

```.Sparkle``` is built on top of QuartzCore.CAEmitterLayer. There's also a [SpriteKit powered version here](https://github.com/lexrus/LTMorphingLabel/blob/spritekit-sparkle/LTMorphingLabel/LTMorphingLabel%2BSparkle.swift).

#### [.Burn](https://github.com/lexrus/LTMorphingLabel/blob/master/LTMorphingLabel/LTMorphingLabel%2BBurn.swift)
<img src="https://cloud.githubusercontent.com/assets/219689/3582586/4fb8c52e-0bfe-11e4-9b6f-f070f7f3ab55.gif" width="300" height="70" alt="LTMorphingLabel-Burn"/>

#### [.Anvil](https://github.com/lexrus/LTMorphingLabel/blob/master/LTMorphingLabel/LTMorphingLabel%2BAnvil.swift)
<img src="https://cloud.githubusercontent.com/assets/219689/3594949/815cd3e8-0caa-11e4-9738-278a9c959478.gif" width="300" height="70" alt="LTMorphingLabel-Anvil"/>

## Requirements

1. Xcode 7
2. iOS 8.0+

## Installation

### [Carthage](https://github.com/Carthage/Carthage)

1. Add this line to your Cartfile: `github "lexrus/LTMorphingLabel"`
2. Run `carthage update` to fetch and build the `LTMorphingLabel.framework`
3. Drag `LTMorphingLabel.framework` into your iOS 8 project

### [CocoaPods](http://cocoapods.org)

1. Install the latest release of CocoaPods: `gem install cocoapods`
2. Add this line to your Podfile: `pod 'LTMorphingLabel', '~> 0.0.8'`
3. Install the pod: `pod install`

## Usage

1. Change the class of a label from UILabel to LTMorphingLabel;
2. Programatically set a new String to its text property.

## Unit tests

Open the project with Xcode then press command + u.

## Alternative

Even though this lib was used in a few products on App Store, it’s still an experimental project. Frankly, there’re some nice competitors out there guarantee both compatibility and stability. And the most outstanding one is [ZCAnimatedLabel](https://github.com/overboming/ZCAnimatedLabel). I’d like to recommend it for production use.

## License

This code is distributed under the terms and conditions of the MIT license.
