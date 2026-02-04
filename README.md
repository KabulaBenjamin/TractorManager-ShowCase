# TractorManager 🚜 | v1.0.0

**TractorManager** is a high-performance Android application built for tractor fleet owners and agricultural managers. It transforms manual bookkeeping into a data-driven operation by tracking jobs, expenses, diesel efficiency, and automated payroll in one seamless interface.

## ✨ Advanced Features

### 💰 Automated Payroll & Sync
- **Real-Time Auto-Sync**: The app automatically calculates pay for a **Driver** (350/acre) and **Two Assistants** (300/500 base) and logs them as expenses instantly.
- **Meal Allowances**: Built-in KES 100 meal allowance per person per work day.
- **Smart Recalculation**: Payroll entries update automatically if job acreage changes, ensuring 100% financial accuracy.

### 📋 Intelligent Customer Records
- **Conditional Fields**: Forms adapt dynamically—show **Acres** for Ploughing/Breaking, or **Trips & Material Type** (Sand, Bricks, etc.) for Transport.
- **Customer Directory**: Searchable database showing lifetime statistics (Total acres worked, total paid) and job history for every customer.
- **Payment Lifecycle**: Track advance payments, outstanding debts, and job completion status.

### 🛠 Maintenance & Asset Health
- **Service Logs**: Track oil changes, filter replacements, and repairs.
- **Service Reminders**: AI-driven alerts notify you when a tractor has exceeded its work acreage and needs maintenance.

### 📊 AI Insights & visual Analytics
- **Proactive Intelligence**: The dashboard features an AI Insight row that alerts you to high fuel consumption, financial burn rates, and pending maintenance.
- **Dynamic Charting**: Toggle trends between **Days, Months, and Years**. Includes a full-month stretching line graph for Income vs. Expenses.
- **Efficiency Tracking**: Real-time monitoring of **Liters per Acre** and **Cost per Acre**.

### 🛡 Data Security & Safety
- **Backup & Restore**: Easily package your entire database and save it to **Gmail or Google Drive** to prevent data loss.
- **Unique Constraints**: Advanced database rules prevent duplicate entries from skewing your financial calculations.
- **Offline First**: Works anywhere without an internet connection using a local SQLite database.

## 🛠 Tech Stack
- **UI**: Jetpack Compose (Material 3) with Dynamic Dark Mode.
- **Language**: Kotlin.
- **Architecture**: MVVM (Model-View-ViewModel).
- **Database**: Room (SQL) with specialized sync logic.
- **Concurrency**: Kotlin Coroutines & Flow.
- **Reporting**: Apache POI for Multi-Sheet Excel Export.

## 🚀 Getting Started

### Installation
To use the app on your Android device:
1. Download the latest **TractorManager.apk** from the [Releases](https://github.com/benjaminkabula/TractorManager/releases) section.
2. Open the APK on your device and follow the prompts to install.
3. Launch the app and start managing your fleet!

*(Note: Requires Android 13 or higher)*

> **📺 Watch the Demo Video**: [Link to your video here]

## 📜 License & Copyright
© 2026 **Benjamin Kabula Koikoi**. All rights reserved.  
*Professional software for the global agricultural community.*
