<p align="center"><img src="https://github.com/bhansmeyer/WWDC-2021-Community-Wishlist/blob/main/wishlist_header.jpg?raw=true" width="600" alt="WWDC 2021 Community Wishlist"></p>

A compilation of predictions and wishlists for WWDC 2021.

## Blog Posts, Articles & Tweets
- [Luke Filipowicz, iMore](https://www.imore.com/these-are-features-i-want-see-watchos-8) (watchOS 8)
- [Becky Hansmeyer](https://beckyhansmeyer.com/2021/05/12/wishes-for-wwdc-2021/)
- [Casey Liss](https://www.caseyliss.com/2021/5/11/wwdc-wishes)
- [Federico Zanetello, Five Stars](https://www.fivestars.blog/articles/wwdc21-wishlist/)
- [Majid Jabrayilov](https://swiftwithmajid.com/2021/05/26/swiftui-wishlist-for-wwdc21/) (SwiftUI Wishlist)
- [Matt VanOrmer, Peer Reviewed](https://www.peerreviewed.io/blog/2021/5/4/my-hope-filled-wish-list-for-wwdc-2021)
- [Ryan Jones (@rjonesy)](https://twitter.com/rjonesy/status/1391079898077437954)
- [Simon Nickel (@simonnickel)](https://twitter.com/simonnickel/status/1352206945927761921?s=20)
- [Simon B. Støvring (@simonbs)](https://twitter.com/simonbs/status/1396931887403315203)
- [Zac Hall, 9to5Mac](https://9to5mac.com/2021/05/30/ipados-15-wish-list-for-improving-ipad-quality-of-life-sans-mac/) (iPadOS 15)
- [Zack Apiratitham](https://vatthikorn.com/wwdc-2021-wish-list)

## Podcast Episodes
- [AppStories Episode 217: Our macOS WWDC Wishes](https://appstories.net/episodes/217/)
- [AppStories Episode 218: Our iOS 15 Wishes](https://appstories.net/episodes/218/)
- [AppStories Episode 220: Our iPadOS 15 Wishes](https://appstories.net/episodes/220/)
- [Connected Episode 348: The Rickies (WWDC 2021)](https://www.relay.fm/connected/348) (Predictions)
- [Cup of Tech Episode 130: WWDC21 Predictions - Respect & Boos](http://cupof.tech/episode/0a165dba/130-wwdc21-predictions-respect-boos) (Predictions)
- [Swift by Sundell 97: "Anything can happen during WWDC"](https://www.swiftbysundell.com/podcast/97/) with special guest Ish ShaBazz

## Videos
- [iPadOS 15 Wishlist](https://www.youtube.com/watch?v=eU28EhV66bI) by Damian Mal
- [iPadOS 15 What to Expect & Wishlist!](https://www.youtube.com/watch?v=kW4S8pKM_jM&t=2s) by Fernando Silva
- [What iPadOS 15 Should Be...](https://www.youtube.com/watch?v=RvZU0fXbr3Y) by Christopher Lawley

## Hardware Announcements

## User-Facing Apps & Features

### iOS/iPadOS
- The ability to view and configure Smart Mailboxes in Mail for iOS. (Becky Hansmeyer)
- The ability to schedule a background task for a specific time or interval. (Darren Jones [@venderbase](https://twitter.com/venderbase))
- The ability to back up to an external drive (i.e. Time Machine)
- A method for adding third-party wallpapers that won't clutter up your Photo Library and also supports light/dark mode
- Some degree of widget interactivity, such as the ability to easily start/stop timers, check to-do items, increment a counter, etc.
- Battery Health on iPad
- App Library on iPad + ability to place widgets anywhere on home screen
- Window management using keyboard shortcuts (just copy Windows already, so Cmd + <- tiles a window to the left-half of the screen)
- Calculator app on iPad
- Multiple user profiles on iPad.

### watchOS
- Apple Watch pairing with iPad
- Third-party watch faces

### macOS
- Widgets should be moved somewhere other than the Notifications panel. (Becky Hansmeyer)
- Window management using keyboard shortcuts (just copy Windows already, so Cmd + <- tiles a window to the left-half of the screen)

### tvOS

## Developer Tools & Frameworks

### UIKit

### SwiftUI
- A way to manage First Responder (think TextField focus and tab order)
- Search Bar support or similar in `List`s or `ScrollView`s to add views to the navigation bar that appear with a scroll gesture. ([@JoshHrach](https://twitter.com/JoshHrach))
- Testing framework with support for querying Views and modifiers similar to [ViewInspector](https://github.com/nalexn/ViewInspector)
- Pull-to-refresh
- A way to change the status bar style (light/dark) at runtime using the SwiftUI app life cycle
- Accessory views for TextFields/TextViews
- Inactive/destructive states in Context Menus
- Context menu preview-providers (for showing a custom preview on long-press/right-click)
- SwiftUI version of UIVisualEffectView
- Native support for the share sheet
- Ability to add an alphabetical section index to a List
- Add pin selection detection in `Map` and add a two way binding for the selected pin.
- Ability to include `Link` within `Text`

### Other Apple Frameworks (i.e. AVFoundation, SiriKit, etc.)
- A modern successor to Core Data that plays well with Combine and SwiftUI
- A sync solution that combines CloudKit and Multipeer Connectivity or Watch Connectivity, so that sync is instantaneous when devices are nearby. ([@stevenpotato](https://twitter.com/stevenpotato))
- Improved support in NSPersistentCloudKitContainer for scheduling background uploads, improving the reliability of saving to CloudKit when used in an app extension (Josh Hrach)
- AVFoundation to support display and capture of additional video channels beyond Red, Green and Blue: Such as Alpha and Depth (Alex ‘4D’ Gollner)

### Xcode
- Xcode for iPad
- A better way to manage build numbers

### Miscellaneous (Developer Tools & Frameworks)
- SwiftUI-like simplification of 2D/3D (perhaps building on top of SpriteKit/SceneKit like SwiftUI builds on UIKit) (Josh Hrach)
- Ability to define alternate app icons as App Icon Assets instead of manually including icon images in the project. (Josh Hrach)
- Run custom code in iCloud (similar to lambda functions in AWS)
- CI/CD tools
- Reorganize documentation in a way that reduces duplication of functions that are common between all SwiftUI views
- SwiftUI hot-reloading similar to Flutter (Simulator and on device)
- New flavors of ProRes: ProRes 444D to encode depth maps, ProRes AR to encode detected environment at capture time (Alex ‘4D’ Gollner)
- Swift Playground for developing FxPlug 4 extensions to video applications (Alex ‘4D’ Gollner [@alex4D](https://twitter.com/alex4D))
- Reduce/remove Developer Program membership fee
- Ability to build watch faces

## App Store Policy, Tools, and APIs
- TestFlight for macOS

## Augmented Reality, Virtual Reality, or Mixed Reality
- Support ARKit replay data in simulators

## Other
- Improvements to music storage and syncing with Apple Music that will hopefully mean reliable song integrity when dealing with artists with multiple live concerts, especially when uploading song versions not found on Apple Music. (Apple Music currently can't handle this and destroys music libraries as a result.) (Josh Hrach)
