# CS360
Mobile Architecture and Programming
MattB Inventory App
Overview

The MattB Inventory App is a simple Android application designed to help users manage and track inventory items. The app allows users to create an account, log in, and perform basic inventory management tasks such as adding, updating, viewing, and deleting items. It was built using Android Studio and demonstrates core mobile development concepts including user authentication, database integration, and permission handling.

Features
User account creation and login
Add new inventory items
Update existing item quantities
Delete items from the inventory
View all stored items in a clean display
Local data storage using SQLite
SMS permission handling and alert functionality
Technologies Used
Java
Android Studio
SQLite Database
Android SDK
How to Run the App
Clone or download the repository
Open the project in Android Studio
Allow Gradle to sync
Run the app using an Android Emulator or physical device

Alternatively, you can install the included APK file:

Locate app-debug.apk
Install it on an Android device
App Functionality

The app uses a local SQLite database to store user credentials and inventory items. After logging in, users can enter an item name and quantity to add it to the database. If the item already exists, the app updates the quantity instead of creating a duplicate entry. Users can also delete items and view a list of all stored inventory.

The SMS feature demonstrates runtime permission handling. If permission is granted, the app can send a simple SMS alert. If denied, the app continues to function normally without interruption.

Monetization Concept

Although this version of the app is not monetized, future improvements could include:

Ad integration
Premium features (such as analytics or cloud sync)
Subscription-based enhancements
Future Improvements
Dynamic list using RecyclerView
Cloud database integration (Firebase)
Improved UI/UX design
Input validation and error handling enhancements
Real-time notifications
Author

Matt Biletnikoff
