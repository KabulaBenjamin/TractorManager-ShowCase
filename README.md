# TractorManager-ShowCase
# TractorManager 🚜

**TractorManager** is a specialized Android application designed for tractor owners and fleet managers to streamline the management of agricultural operations. It tracks customer jobs, business expenses, diesel consumption, and automates driver payroll calculations.

## ✨ Key Features

- **Operational Dashboard**: Real-time overview of daily income, expenses, net cash flow, total acres worked, and diesel consumption.
- **Customer & Job Management**: Log service types, locations, acreage, and payment status (Paid vs. Debt).
- **Automated Driver Payroll**: 
  - **Driver**: KES 350 per acre + KES 100 lunch allowance.
  - **Assistant**: KES 300 base (if < 4 acres) or KES 500 base (if ≥ 4 acres) + KES 100 lunch allowance.
  - One-click integration to save payroll as a business expense.
- **Financial Analytics**: 
  - **Monthly Stats**: Detailed text breakdown of income by service type.
  - **Visual Trends**: 7-day bar charts and a full-month stretching line graph comparing Income vs. Expenses.
- **Data Export**: Generate professional multi-sheet Excel (.xlsx) and CSV reports for bookkeeping.
- **Dark Mode Support**: Fully compatible with system-wide light and dark themes.
- **Offline First**: Powered by a local Room database to ensure data is accessible even in the field.

## 🛠 Tech Stack

- **UI**: Jetpack Compose (Material 3)
- **Language**: Kotlin
- **Architecture**: MVVM (Model-View-ViewModel)
- **Database**: Room Persistence Library
- **Concurrency**: Kotlin Coroutines & Flow
- **Navigation**: Navigation Compose
- **Reporting**: Apache POI (Excel Generation)
- **Build System**: Gradle with KSP (Kotlin Symbol Processing)

## 📸 Screenshots & Demo

| Dashboard | Visual Trends | Driver Pay |
| :---: | :---: | :---: |
| ![Dashboard Placeholder] | ![Trends Placeholder] | ![Pay Placeholder] |

> **📺 Watch the Demo Video**: [Link to your video here]

## 🚀 Getting Started

### Installation
To use the app on your Android device:
1. Download the latest **TractorManager.apk** from the [Releases](https://github.com/benjaminkabula/TractorManager/releases) section.
2. Open the APK on your device and follow the prompts to install (ensure "Install from Unknown Sources" is enabled in settings).
3. Launch the app and start managing your fleet!

*(Note: Requires Android 13 or higher)*

## 📊 Usage Tips
- **Daily Summaries**: To see data in the "Charts" section, ensure you click the **"Save Daily Summary"** button on the dashboard at the end of each work day.
- **Excel Reports**: Shared reports are saved in the app's internal storage and can be shared via WhatsApp, Email, or Google Drive.

## 📜 License & Copyright

© 2026 **Benjamin Kabula Koikoi**. All rights reserved.

Developed with ❤️ for the agricultural community.
the agricultural community.
