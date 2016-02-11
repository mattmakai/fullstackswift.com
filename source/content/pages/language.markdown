title: Language Concepts
category: page
slug: language-concepts
sort: 01


This 
[Swift cheatsheet](http://mhm5000.gitbooks.io/swift-cheat-sheet/content/index.html)
provides loads of code examples for language syntax and constructs.


### Optionals
* [Switches and optionals](https://thatthinginswift.com/switch-unwrap-shortcut/)  explains why optionals are a good fit for reducing the clunkiness in code
  around variables that may or may not have a value.

* [Swift Optionals: When to use if let, when ? and !, when as? and as](http://www.touch-code-magazine.com/swift-optionals-use-let/)
  digs into some of the confusing details behind force unwrapping, unwrapping
  and general variable optional handling in Swift.


### Structs


### Classes


### Control Flow
* [Swift 2.0: Control Flow and Error Handling](http://austinzheng.com/2015/06/08/swift-2-control-flow/)
  examines the modification of Swift's `do-while` loop to `repeat-while` so
  the `do` statement could be introduced in 2.0. The post also covers the
  `guard` statement with a good IPv4 address parsing example, the `defer`
  keyword and wraps up with 2.0's new error handling mechanisms. A good note
  in the post is the explanation of the `try!` (force try) keyword which
  calls a function that can potentially throw an error and will terminate the
  program with a runtime exception if an exception is thrown.

* Apple's official [Swift error handling](https://developer.apple.com/library/prerelease/ios/documentation/Swift/Conceptual/Swift_Programming_Language/ErrorHandling.html)
  page goes over the basics of representing, throwing and handlinge errors in
  programs.


### Function Currying
*Function currying* is a concept Swift brings in from functional programming. 
Curried functions rewrite an existing function with multiple arguments into 
a new function with a single parameter as input and a function as returned
output.

* There is a solid 
  [language-agnostic Stack Overflow post on curried functions](http://stackoverflow.com/questions/36314/what-is-currying)
  that defines what they are and shows their background comes from algebra
  functions.

* [Curried functions in Swift](http://ijoshsmith.com/2014/06/09/curried-functions-in-swift/)
  provides a concrete simple example of a curried function versus using a
  default parameter value.

* This post explains that 
  [Instance Methods are Curried Functions in Swift](http://oleb.net/blog/2014/07/swift-instance-methods-curried-functions/)
  and provides an example of how using function currying in some cases leads
  to cleaner code than in Objective-C.
