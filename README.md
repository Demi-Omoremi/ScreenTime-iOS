# Screen Time Management iOS App

An iOS application for parent monitoring and student productivity tracking built with SwiftUI.

## Features
- **App Usage Restrictions**: Implements Apple's Family Controls framework to enforce app limits
- **Focus Timer**: Helps students stay productive with timed focus sessions
- **Streak Tracking**: Encourages consistent usage with streak counters
- **Leaderboard**: Gamifies productivity with competitive rankings
- **Offline Support**: Uses Core Data for local persistence and reliability

## Tech Stack
- **Language**: Swift
- **UI Framework**: SwiftUI
- **Data Persistence**: Core Data
- **Device APIs**: Family Controls, Device Activity frameworks


## Note on Device Activity APIs
The Family Controls and Device Activity frameworks require physical device testing and specific provisioning profiles. Some features cannot be demonstrated in Xcode Simulator.

## Installation
1. Clone this repository
2. Open `ScreenTimeApp.xcodeproj` in Xcode
3. Build and run on a physical iOS device (iOS 15.0+)
