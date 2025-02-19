# iOS Stack

A modern iOS development stack with **Swift 6**, but we also have long time experience with **Objective-C**.
We focus on testability and maintainability, so we mainly use modular and unidirectional architecture called Swift Composable Architecture (TCA).

## UI

- **SwiftUI** - The best way to build apps across Apple platforms
- **UIKit**

## Architecture & Dependencies

- **Unidirectional Architectures** – Ensuring predictable state management and separation of concerns  
- **[Swift Composable Architecture](https://github.com/pointfreeco/swift-composable-architecture)** – Modular and testable architecture  
- **Clean Architecture** – Layered architecture for maintainability and scalability  
- **MVVM (Model-View-ViewModel)** – Clear separation between UI and business logic  
- **[Swift Dependencies](https://github.com/pointfreeco/swift-dependencies)** – Dependency injection  
- **Modern Swift Concurrency** – `async/await`, `Task`, `Actors`, `Structured Concurrency`  


## In-app purchases & subscriptions
- **StoreKit** - Support In-App Purchases and interactions with the App Store
- **[RevenueCat](https://www.revenuecat.com)** - Simplifying the implementation and maintenance of in-app purchases & subscriptions

## Experience & Scalability

- **Large-Scale Projects** – Experience with huge codebases and complex applications  
- **Multiple Apps Sharing Code** – Efficient modularization and code reuse  
- **REST API Development & Integration** – Building and consuming APIs  

## Accessibility

- **Voice Over** – Gesture-based screen reader that enables people to experience the interface on their devices without having to see the screen
- **Dynamic type** – Allows users to choose the size of textual content displayed on the screen

## Version Control

- **Git** – Source control management  
- **Git Flow** – Branching strategy for feature development and releases  

## Testing

- **[Snapshot Testing](https://github.com/pointfreeco/swift-snapshot-testing)** – UI tests  
- **Unit Testing** – XCTest, Swift Testing  
- **Linting & Code Quality**  
  - [SwiftLint](https://github.com/realm/SwiftLint) – Enforces Swift style  
  - [SwiftGen](https://github.com/SwiftGen/SwiftGen) – Code generation  

## CI/CD

- **[Fastlane](https://fastlane.tools/)** and **GitHub Actions** for automation
- **[Xcode Cloud](https://developer.apple.com/xcode-cloud/)** Seamless continuous integration and delivery service provided by Apple

## Networking & Authentication

- **Networking**  
  - `URLSession`, [Alamofire](https://github.com/Alamofire/Alamofire)  
  - GraphQL, [Apollo](https://github.com/apollographql/apollo-ios)
  - Secure authentication using OpenID, `ASWebAuthenticationSession`  
  - Auth via access tokens and other methods  

- **Sign-in Options**  
  - Google Sign-In  
  - Apple Sign-In  
  - Microsoft Sign-In  

## Storage & Persistence

- **Local Storage**  
  - Keychain  
  - User Defaults  
  - Realm
  - CoreData
  - SwiftData

- **Cloud & Remote Storage**  
  - Firebase (Push notifications, Remote Config, Crashlytics, Analytics)  
  - Azure Storage (Upload & Download) 
  - iCloud synchronization 

## Notifications

- **Push Notifications**  
  - Firebase Cloud Messaging (FCM)  
  - Local Notifications  
  - **Push Notification Extension** – Customizing notifications with media attachments, actions, and rich content  

## Media & UI

- **Image & Video Handling**  
  - [Kingfisher](https://github.com/onevcat/Kingfisher) – Image caching  
  - [AVFoundation](https://developer.apple.com/documentation/avfoundation) – Audio/Video editing, mixing, combining, conversions. Taking photos/videos
  - Picking photos & videos, custom pickers  

- **Animations & UI Enhancements**  
  - [Lottie](https://airbnb.io/lottie/) – Animated illustrations  
  - Emojis support  
  - Document Picker for file selection  

## Extensions

- **Push Notification Extension** – Customizing push notifications  
- **Sharing Extension** – Allowing users to share content from other apps into the app  
- **App Intents Extension** – Making your app’s content and actions discoverable with system experiences like Spotlight, widgets, and enhanced action capabilities of Siri, powered by Apple Intelligence

## Cryptography & Security

- **[CryptoKit](https://developer.apple.com/documentation/cryptokit)** – Encryption & Decryption  

## Reactive Programming & Concurrency

- **RxSwift**, **Combine** and **ReactiveSwift**
- **Swift Concurrency** (`async/await`, `Task`, `Actors`, `MainActor`)  

## Real-Time Communication

- **SignalR**
- **WebSockets**  

## Logging & Debugging 

- **Logging frameworks**  
  - [XCLogger](https://github.com/DaveWoodCom/XCGLogger)  
  - [SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver)  

## Modularization

- Using **Swift Package Manager (SPM)** to modularize the app and share code across multiple apps  

## Deployment & Distribution

- **TestFlight** – Beta testing  

## Graphics & Rendering

- **Metal & OpenGL** – 2D/3D rendering, game engine 
- **CoreAnimation** - Core Animation provides high frame rates and smooth animations without burdening the CPU or slowing down your app
