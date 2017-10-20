# TZDatePicker

is a simple DatePicker that easy to use

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

### the Example project
![TZDatePicker Example app](https://github.com/heart/TZDatePicker/blob/master/images/screenshot.png?raw=true)


## Requirements
Swift


## Installation

SwiftTween is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'TZDatePicker'
```

## Example
```swift
var dateComponents = DateComponents()
dateComponents.month = 7
dateComponents.day = 20

let datePicker = TZDatePicker(dateComponents: dateComponents)
datePicker.onValueChanged = {
    dateComponents in

    print( dateComponents.description )

}

view.addSubview(datePicker)
```
