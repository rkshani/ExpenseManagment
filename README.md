Expense Management (Android)

A simple Android app to record and manage day-to-day expenses with a clean UI and lightweight storage.

Tech: Android (Java). APK provided under apk/release/. 
GitHub

✨ Features

Add, edit, and delete expenses

Categorize expenses (e.g., Food, Travel, Bills, Misc.)

View total spend by day/week/month

Basic filtering & search

Offline-first, lightweight, fast

📱 Screenshots
Home	Add Expense	History

📦 Download

APK: check apk/release/ in this repo for a signed build. 
GitHub

Or build locally (instructions below).

🛠️ Build & Run (Android Studio)

Clone

git clone https://github.com/rkshani/ExpenseManagment.git
cd ExpenseManagment


Open in Android Studio (Giraffe+ recommended)

Sync Gradle and Run on a device/emulator

Project language: Java (100%). 
GitHub

📁 Project Structure (high level)
ExpenseManagment/
├─ app/               # Android app module
├─ apk/release/       # Prebuilt APK(s)
├─ gradle/            # Gradle wrapper
├─ build.gradle       # Root build config
└─ settings.gradle    # Gradle settings


GitHub

🔐 Permissions

android.permission.INTERNET (if using ads/analytics or remote crash reports)

android.permission.POST_NOTIFICATIONS (Android 13+, if you send notifications)

Remove any permission you don’t use.

🗺️ Roadmap

 Export to CSV/Excel

 Multi-currency support

 Category icons & theming

 Dark mode

 Charts / insights
 

🧩 Tech Stack 

Language: Java

Min/Target SDK: fill in

Build: Gradle (Android Gradle Plugin)

Architecture: MVVP

Storage:  Room / SQLite / SharedPreferences

📄 License

This project is licensed under the MIT License.

🙌 Contributions

Pull requests and issues are welcome. Please open an issue to discuss major changes first.

👤 Author

@rkshani — Feedback and suggestions are appreciated!
