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

Available modifiers:

* `foregroundColor`
* `background`
* `underline`
* `font`
* `shadow`

Feel free to add any that're missing.
