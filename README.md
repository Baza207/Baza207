```swift
import Foundation

struct Developer {
    let name: String
    let dateOfBirth: Date
    let liveApps: [App]
}

struct App {
    let name: String
    let link: String
}

let me = Developer(
    name: "James Barrow",
    dateOfBirth: Date(timeIntervalSince1970: 589075200),
    liveApps: [
        App(name: "Dog Bins", link: "https://apps.apple.com/app/apple-store/id538357667")
    ]
)
```
