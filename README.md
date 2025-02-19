# iOS Stack

A modern iOS development stack with **Swift 6** and **Objective-C**.

## Architecture & Dependencies

- **[Swift Composable Architecture](https://github.com/pointfreeco/swift-composable-architecture)** – Modular and testable architecture  
- **[Swift Dependencies](https://github.com/pointfreeco/swift-dependencies)** – Dependency injection  
- **Modern Swift Concurrency** – `async/await`, `Task`, `Actors`, `Structured Concurrency`  

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

## Networking & Authentication

- **Networking**  
  - `URLSession`, [Alamofire](https://github.com/Alamofire/Alamofire)  
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
  - Realm, CoreData  

- **Cloud & Remote Storage**  
  - Firebase (Push notifications, Remote Config, Crashlytics, Analytics)  
  - Azure Storage (Upload & Download)  

## Notifications

- **Push Notifications**  
  - Firebase Cloud Messaging (FCM)  
  - Local Notifications  
  - **Push Notification Extension** – Customizing notifications with media attachments, actions, and rich content  

## Media & UI

- **Image & Video Handling**  
  - [Kingfisher](https://github.com/onevcat/Kingfisher) – Image caching  
  - [AVFoundation](https://developer.apple.com/documentation/avfoundation) – Audio/Video editing, mixing, combining, conversions  
  - Picking photos & videos, custom pickers  

- **Animations & UI Enhancements**  
  - [Lottie](https://airbnb.io/lottie/) – Animated illustrations  
  - Emojis support  
  - Document Picker for file selection  

## Extensions

- **Push Notification Extension** – Customizing push notifications  
- **Sharing Extension** – Allowing users to share content from other apps into the app  

## Cryptography & Security

- **[CryptoKit](https://developer.apple.com/documentation/cryptokit)** – Encryption & Decryption  

## Reactive Programming & Concurrency

- **RxSwift** and **Combine**  
- **Swift Concurrency** (`async/await`, `Task`, `Actors`, `MainActor`)  

## Real-Time Communication

- **SignalR**  

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

---

This stack provides a solid foundation for modern iOS development, ensuring scalability, testability, and maintainability. 🚀
