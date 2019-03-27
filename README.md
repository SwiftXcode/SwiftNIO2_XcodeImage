<h2>SwiftXcode Image for Swift NIO 2
  <img src="http://zeezide.com/img/SwiftXcodePkgIcon.svg"
       align="right" width="128" height="128" />
</h2>

![Swift5](https://img.shields.io/badge/swift-5-blue.svg)
![macOS](https://img.shields.io/badge/os-macOS-green.svg?style=flat)
![Travis](https://travis-ci.org/SwiftXcode/SwiftNIO2_XcodeImage.svg?branch=master)
[![homebrew](https://img.shields.io/homebrew/v/cake.svg)](https://github.com/SwiftXcode/homebrew-swiftxcode)

SwiftXcode image for
[Swift NIO 2](https://github.com/apple/swift-nio).
(this requires Swift 5, we also provide a NIO 1 image which works with
 Swift 4.x: [Swift NIO 1 image](https://github.com/SwiftXcode/SwiftNIO1_XcodeImage)).

Swift NIO is a cross-platform asynchronous event-driven network application 
framework for rapid development of maintainable high performance protocol 
servers & clients.
It's like Netty written in Swift.

Check the main project for details: [SwiftXcode](https://SwiftXcode.github.io).

### Install Swift NIO 2 Image

```shell
brew install swiftxcode/swiftxcode/swift-xcode-nio2
swift xcode link-templates # <-- important!
```

### Use within Xcode

1. Create new project (Command-Shift-N or File/New/Project ...)
2. choose macOS / Server / Swift NIO 2 template
3. check desired options
4. build and run, and then have fun!

<img src="http://zeezide.com/img/microexpress-nio/01-new-project.jpg" align="center" />

<img src="http://zeezide.com/img/microexpress-nio/02-new-project.jpg" align="center" />


### Who

Brought to you by
[ZeeZide](http://zeezide.de).
We like
[feedback](https://twitter.com/ar_institute),
GitHub stars,
cool [contract work](http://zeezide.com/en/services/services.html),
presumably any form of praise you can think of.

### Want a Video Tutorial?

<img src="http://zeezide.com/img/swift-nio-cows.gif" />
