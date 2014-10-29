---
layout: post
title: #ifdef in Swift
---

# #ifdef in Swift

Check for the presence of a flag for conditional compilation in Swift using `#if` `#else` `#endif`. 

Set the symbol in the Xcode Project Build Settings under

`Swift Compiler - Custom Flags - Other Swift Flags`. 

Usage:
For example, using `-D DEBUG`

```swift
#if DEBUG
    println("debug build")
#else
    println("not a debug build")
#end
```

Found [here](http://stackoverflow.com/a/24152730/919790) 

