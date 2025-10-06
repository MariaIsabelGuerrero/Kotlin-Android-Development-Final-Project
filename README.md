AutoCare - Vehicle Management App
📱 Overview
AutoCare is a comprehensive Android application built with Kotlin and Jetpack Compose. It helps vehicle owners track maintenance schedules, manage expenses, and keep records of mechanics and service centers. The app features a clean Material Design UI with intuitive navigation and robust data management powered by Room Database.
🚀 Features
Vehicle Management

🚗 Add and manage multiple vehicles with detailed information
📸 Photo support for vehicle identification
✏️ Edit vehicle details (make, model, year, registration, mileage)
🗑️ Delete vehicles with confirmation dialogs

Maintenance Tracking

📅 Schedule and track maintenance records
🔧 Predefined maintenance types (Oil Change, Tire Rotation, Brake Service, etc.)
✅ Mark maintenance as completed with dates
💰 Cost tracking for each maintenance activity
⚠️ Overdue maintenance notifications

Expense Management

📊 Track all vehicle-related expenses by category
🏷️ Categories: Fuel, Maintenance, Insurance, Repairs, Registration, and more
📝 Detailed expense records with date, location, and odometer readings
📈 Expense summaries with yearly and category breakdowns
🎯 Visual expense analytics

Mechanic Directory

👨‍🔧 Save favorite mechanics and service centers
📞 Store contact information and service notes
🔗 Quick access from vehicle details

🛠️ Tech Stack

Language: Kotlin
UI: Jetpack Compose with Material Design 3
Database: Room Database with SQLite
Architecture: MVVM with Repository pattern
Async Programming: Kotlin Coroutines & Flow
Navigation: Navigation Component (type-safe)
State Management: ViewModel & StateFlow
Image Loading: Coil
Build System: Gradle (Kotlin DSL) with version catalogs
Code Generation: KSP (Kotlin Symbol Processing)

📦 Installation

Clone the repository:

bashgit clone https://github.com/yourusername/AutoCare.git

Open the project in Android Studio.
Sync Gradle and build the project.
Run the app on an emulator or physical device (Min SDK 24, Target SDK 35).

🔑 Requirements

Android Studio: Hedgehog or newer
JDK: 11+
Minimum Android SDK: 24 (Android 7.0)
Target Android SDK: 35
Kotlin: 2.0.21

📐 Architecture
The app follows MVVM (Model-View-ViewModel) architecture with a repository pattern:
├── data/
│   ├── entity/          # Room entities (Car, Maintenance, Expense, Mechanic)
│   ├── database/        # DAOs and Database
│   └── repository/      # Repository layer
├── ui/
│   ├── screens/         # Composable screens
│   ├── components/      # Reusable UI components
│   ├── navigation/      # Navigation setup
│   └── theme/           # Material Design theme
└── viewmodel/           # ViewModels for UI state management
📷 Screenshots
Add screenshots here to showcase the app UI.
🤝 Contributing
Contributions are welcome! Feel free to:

Fork this repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📝 Future Enhancements

 Cloud backup and sync
 Export data to CSV/PDF
 Fuel efficiency tracking
 Service reminder notifications
 Dark theme support
 Multi-language support

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.
👨‍💻 Author
Created with ❤️ for vehicle owners who want to stay organized
