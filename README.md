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

dump(me)
```

> ▿ Developer  
> &nbsp;&nbsp;\- name: "James Barrow"  
> &nbsp;&nbsp;▿ dateOfBirth: 1988-09-01 00:00:00 +0000  
> &nbsp;&nbsp;&nbsp;&nbsp;\- timeIntervalSinceReferenceDate: -389232000.0  
> &nbsp;&nbsp;▿ liveApps: 1 element  
> &nbsp;&nbsp;&nbsp;&nbsp;▿ App  
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\- name: "Dog Bins"  
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\- link: "[https://apps.apple.com/app/apple-store/id538357667](https://apps.apple.com/app/apple-store/id538357667?pt=446643&ct=githubgithugithub&mt=8)"  
