# 🚘 AutoCare — Vehicle Management App

A modern **Android app** built with **Kotlin** and **Jetpack Compose**, designed to help vehicle owners **track maintenance**, **manage expenses**, and **organize mechanic records** — all with a smooth Material Design experience.

---

## 🌟 Overview

**AutoCare** empowers drivers to stay on top of their vehicle’s health and expenses.  
From scheduling oil changes to tracking yearly costs, every feature is built for clarity, simplicity, and performance.  
The app leverages **Room Database**, **MVVM architecture**, and **Jetpack Compose** for a seamless offline experience.

---

## 🚀 Key Features

### 🏎 Vehicle Management
- 🚗 Add and manage multiple vehicles with detailed specs  
- 📸 Upload photos for quick identification  
- ✏️ Edit or delete vehicles easily with confirmation prompts  

### 🧰 Maintenance Tracking
- 📅 Schedule and log maintenance records  
- 🔧 Predefined types (Oil Change, Tire Rotation, Brake Service, etc.)  
- ✅ Mark maintenance as completed with cost and date  
- ⚠️ Get alerts for overdue tasks  

### 💸 Expense Management
- 📊 Categorize all vehicle-related expenses  
- 🏷️ Categories: Fuel, Maintenance, Insurance, Repairs, Registration, etc.  
- 📝 Record details like date, location, and odometer readings  
- 📈 View visual analytics with yearly and category summaries  

### 🧑‍🔧 Mechanic Directory
- 👨‍🔧 Save favorite mechanics and service centers  
- 📞 Store contact info and personal notes  
- 🔗 Access mechanics quickly from any vehicle profile  

---

## 🛠 Tech Stack

| Layer | Technology |
|------:|------------|
| **Language** | Kotlin |
| **UI** | Jetpack Compose (Material 3) |
| **Architecture** | MVVM + Repository Pattern |
| **Database** | Room (SQLite) |
| **Async/State** | Coroutines, Flow, ViewModel, StateFlow |
| **Navigation** | Navigation Component |
| **Images** | Coil |
| **Build System** | Gradle (Kotlin DSL + Version Catalogs) |
| **Code Gen** | KSP (Kotlin Symbol Processing) |

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MariaIsabelGuerrero/AutoCare.git
   ```
2. **Open the project** in **Android Studio**  
3. **Sync Gradle** and **build** the project  
4. **Run the app** on an **emulator** or **physical device**  
   *(Min SDK 24, Target SDK 35)*

---

## 🔑 Requirements

- **Android Studio:** Hedgehog or newer  
- **JDK:** 11+  
- **Minimum Android SDK:** 24 (Android 7.0)  
- **Target Android SDK:** 35  
- **Kotlin:** 2.0.21  

---

## 📐 Architecture

The project follows the **MVVM (Model–View–ViewModel)** architecture with a repository pattern for clean separation of concerns and easy testing:

```
app/
├── data/
│   ├── entity/          # Room entities (Car, Maintenance, Expense, Mechanic)
│   ├── database/        # DAOs and Database setup
│   └── repository/      # Repository layer handling data operations
├── ui/
│   ├── screens/        # Composable UI screens
│   ├── components/     # Reusable UI components
│   ├── navigation/     # Navigation setup
│   └── theme/          # Material Design theme configuration
└── viewmodel/          # ViewModels for UI state management
```

---

## 📸 Screenshots

_Add screenshots or GIFs here to showcase your UI and key flows._

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo, create a feature branch, and submit a pull request.

