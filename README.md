# Water Reminder

<p align="center">
  <a href="#features">Features</a> •
  <a href="#requirements">Requirements</a> •
  <a href="#installation">Installation</a> •
  <a href="#architecture">Architecture</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</p>

**Water Reminder** is a beautifully designed iOS app with Apple Watch support to help you stay hydrated throughout the day through gentle reminders. Track your water intake, set personalized goals, and monitor your hydration progress with elegant visualizations.

## Features

- **🔔 Friendly Reminders**: Receive gentle reminders with customizable intervals to help you stay hydrated
- **📊 Progress Tracking**: Track your daily and weekly water intake with beautiful visualizations
- **🎯 Customizable Goals**: Set personal hydration goals based on your needs
- **⌚ Apple Watch Integration**: Add water intake directly from your wrist
- **🔄 Seamless Sync**: Data syncs automatically between iPhone and Apple Watch
- **🔌 Widget Support**: View your daily progress at a glance from your home screen

## Requirements

- iOS 16.0+
- watchOS 9.0+
- Xcode 14.0+
- Swift 5.7+

## Installation

### From Source

1. Clone the repository:
```bash
git clone https://github.com/holasoymalva/waterReminderApp.git
```

2. Open the project in Xcode:
```bash
cd waterReminderApp
open WaterReminder.xcodeproj
```

3. Select the appropriate target (iOS device or simulator) and click Run

### App Store

*Coming soon to the App Store*

## Architecture

Water Reminder follows the MVVM (Model-View-ViewModel) architecture pattern and leverages SwiftUI for a clean, declarative UI.

### Key Components

- **Models**: Data structures and business logic
  - `WaterEntry`: Represents a single water intake record
  - `WaterManager`: Manages water intake data, goals, and notifications

- **Views**: User interface components
  - `HomeView`: Main screen showing progress and quick add buttons
  - `StatsView`: Visualizations of daily and weekly water intake
  - `SettingsView`: Customization options for goals and reminders

- **WatchOS Integration**: 
  - `WatchConnectivityManager`: Handles communication between iOS and watchOS
  - `WatchContentView`: Simplified interface for Apple Watch

- **Widget**:
  - `WaterReminderWidget`: Home screen widget showing current progress

## Apple Watch Features

The companion Apple Watch app provides:

- At-a-glance progress visualization
- Quick-add buttons for common amounts (100ml, 200ml, 300ml)
- Gentle haptic reminders
- Seamless synchronization with the iOS app

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Design inspired by Apple's San Francisco design language
- Icons from [SF Symbols](https://developer.apple.com/sf-symbols/)

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/holasoymalva">holasoymalva</a>
</p>
