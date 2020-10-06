# ActivityIndicator

ActivityIndicator for iOS 13 in SwiftUI

## Installation

### SPM

```swift
.package(url: "https://github.com/LukasHromadnik/ActivityIndicator.git", .upToNextMajor(from: "1.0.0"))
```

## Usage

```swift
import ActivityIndicator

@State var isLoading = true

let activityIndicator = ActivityIndicator(isLoading: $isLoading)
```

### Customization

If you want to add some **color**, just specify it as the second parameter:

```swift
import ActivityIndicator

@State var isLoading = true

let activityIndicator = ActivityIndicator(isLoading: $isLoading, color: .red)
```

Also if you wish to have the **large** activity indicator use the last parameter:

```swift
import ActivityIndicator

@State var isLoading = true

let activityIndicator = ActivityIndicator(isLoading: $isLoading, style: .large)
```
