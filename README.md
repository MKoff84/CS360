CS360

Mobile Architecture and Programming
MattB Inventory App
Overview

The MattB Inventory App is a simple Android application designed to help users manage and track inventory items. The app allows users to create an account, log in, and perform basic inventory management tasks such as adding, updating, viewing, and deleting items. This application was designed to address the need for a straightforward way to manage inventory in small-scale environments, such as personal storage or small businesses, where users need a quick and reliable way to track item quantities.

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

Alternatively, install the included APK file:

Locate app-debug.apk
Install it on an Android device
App Design and Development Reflection

The main goal of this app was to create a functional inventory system that allows users to manage items efficiently. The app addresses user needs by providing a simple interface for tracking inventory, updating quantities, and maintaining stored data. Users need a reliable way to store and retrieve item information, and this app provides that through a local database and clear user interaction flow.

To support these needs, the app includes a login screen and an inventory management screen. The login screen allows secure access, while the inventory screen provides input fields, action buttons, and a display area for stored items. The UI design was kept simple and organized so users can easily understand how to interact with the app. Clear labeling, structured layout, and straightforward navigation helped ensure the design remained user-centered and easy to use.

When developing the app, I followed a step-by-step approach by building one feature at a time. I started with the UI layout, then implemented user authentication, followed by database integration using SQLite, and finally added CRUD functionality and permission handling. This incremental approach made it easier to test each part of the application and identify issues early. These strategies can be applied in future projects to improve organization, reduce errors, and make development more manageable.

Testing was done continuously using the Android Emulator. Each feature, such as login, adding items, updating quantities, deleting items, and handling permissions, was tested individually to ensure it worked as expected. This process is important because it helps catch errors early and ensures the app behaves correctly in different scenarios. Testing also revealed issues such as duplicate data entries and permission handling behavior, which were then corrected.

One challenge I encountered was managing how data was stored and displayed without creating duplicate entries. I had to adjust the logic so that existing items would update instead of being inserted again. This required modifying the database interaction methods and ensuring the UI reflected those changes correctly. Overcoming this challenge improved both the functionality and reliability of the app.

A component where I was particularly successful was implementing the full CRUD functionality using SQLite. This demonstrated my ability to connect a user interface to a working database and manage data effectively. Additionally, implementing SMS permission handling showed my understanding of Android permissions and how to maintain app functionality regardless of user choices.

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
