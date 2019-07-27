# AttributedStringBuilder

A DSL for creating an `NSAttributedString`. Original created to demonstrate function builders [here](https://medium.com/@carson.katri/create-your-first-function-builder-in-5-minutes-b4a717390671).

Example:

```swift
NSAttributedString {
  "Hello "
    .foregroundColor(.blue)
  "World"
    .background(.orange)
    .underline(.red, style: .thick)
}
```

### Installation
You can install it via the Swift Package Manager in Xcode 11.

Go to File > Swift Packages > Add Package Dependency...

In the text field paste the following: `https://github.com/carson-katri/AttributedStringBuilder`.

### Documentation

Available modifiers:

* `foregroundColor`
* `background`
* `underline`
* `font`
* `shadow`

Feel free to add any that're missing.
