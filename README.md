AutoCare - Vehicle Management App

A comprehensive Android application for tracking vehicle maintenance, expenses, and mechanic information — clean Material Design UI with intuitive navigation and robust data management.

Features
Vehicle Management

Add and manage multiple vehicles with detailed information
Photo support for vehicle identification
Edit vehicle details (make, model, year, registration, mileage)
Delete vehicles with confirmation dialogs

Maintenance Tracking

Schedule and track maintenance records
Predefined maintenance types (Oil Change, Tire Rotation, Brake Service, etc.)
Mark maintenance as completed with dates
Cost tracking for each maintenance activity
Overdue maintenance notifications

Expense Management

Track all vehicle-related expenses by category
Categories: Fuel, Maintenance, Insurance, Repairs, Registration, etc.
Detailed expense records with date, location, and odometer readings
Expense summaries with yearly and category breakdowns
Visual expense analytics

Mechanic Directory

Save favorite mechanics and service centers
Contact information and service notes
Quick access from vehicle details

Tech Stack

Kotlin - Primary development language
Android SDK - Target SDK 35, Min SDK 24
Jetpack Compose - Modern declarative UI toolkit
Material Design 3 - Consistent and accessible design system

Architecture & Libraries

MVVM Architecture with Repository pattern
Room Database - Local data persistence with SQLite
Kotlin Coroutines & Flow - Asynchronous programming
Navigation Component - Type-safe navigation
ViewModel & StateFlow - UI state management
Coil - Image loading and caching

Build System

Gradle (Kotlin DSL) with version catalogs
KSP (Kotlin Symbol Processing) for Room
Modular architecture with clean separation of concerns
