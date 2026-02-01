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

## 📸 Screenshots

| Dashboard | Visual Trends | Driver Pay |
| :---: | :---: | :---: |
| ![Dashboard Placeholder] | ![Trends Placeholder] | ![Pay Placeholder] |

## 🚀 Getting Started

### Prerequisites
- Android Studio Ladybug or newer.
- Android SDK 33+.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/benjaminkabula/TractorManager.git
   ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Run the app on an emulator or physical device (Min SDK 33).

## 📊 Usage Tips
- **Daily Summaries**: To see data in the "Charts" section, ensure you click the **"Save Daily Summary"** button on the dashboard at the end of each work day.
- **Excel Reports**: Shared reports are saved in the app's internal storage and can be shared via WhatsApp, Email, or Google Drive.

## 📜 License & Copyright

© 2026 **Benjamin Kabula Koikoi**. All rights reserved.

Developed with ❤️ for the agricultural community.
