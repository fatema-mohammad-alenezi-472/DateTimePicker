# DateTimePicker

A nicer iOS UI component for picking date and time.

![Screenshot](screenshot.jpg)

## Features

- Date and Time Picker / Date Picker only / Time Picker only - your choice!
- Limit selected date within a defined range of time
- Show or hide month on date cell
- Inifnite scrolling for time
- Customize colors and date format

## Requirements

- Swift 4.0 & xCode 9 
- For Swift 3.0, please use version 1.1.4
- iOS 9 and later

## Installation

#### Using Cocoapod

Just add the following to your `podfile`
> pod 'DateTimePicker'

#### Manual install

Drag and drop folder `Source` to your project.


## Usage

You can easily show and customize the component's colors

```Swift
let picker = DateTimePicker.show()
picker.highlightColor = UIColor(red: 255.0/255.0, green: 138.0/255.0, blue: 138.0/255.0, alpha: 1)
picker.isDatePickerOnly = true // to hide time and show only date picker
picker.completionHandler = { date in
    // do something after tapping done
}
```

## Licence

DateTimePicker is available under the MIT license. See the LICENSE file for more info.
