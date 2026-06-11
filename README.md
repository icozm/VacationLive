# VacationLive Mobile Application

Purpose

VacationLive is a mobile application designed to help users plan, organize, and manage their vacations in one convenient place. Users can create vacations, associate excursions with each trip, set alerts for important dates, and share their travel details.

This application helped me learn and demonstrate Android development skills, including user interface design, local data persistence using Room Database, and mobile application functionality.


How to Operate the Application
1. Launching the Application
Install the signed APK on an Android device or emulator.
Open the app to view the main screen displaying a list of vacations.


2. Adding a Vacation
Tap the Add (+) option.
Enter the following details:
Vacation Title
Hotel Name
Start Date
End Date
Save the vacation to add it to the list.

3. Viewing and Editing a Vacation
Select a vacation from the list.
On the Vacation Details screen, you can:
Edit vacation details
Delete the vacation (only if no excursions are associated)
Set alerts for start and end dates
Share vacation details

4. Managing Excursions
Open a vacation to view its associated excursions.
Add a new excursion:
Enter excursion title and date
Ensure the date falls within the vacation start and end dates
Edit or delete excursions as needed.
The application supports adding, updating, and deleting multiple excursions per vacation.


5. Alerts and Notifications
Users can set alerts for:
Vacation start and end dates
Excursion dates
Notifications are delivered using Android’s AlarmManager and will trigger at the scheduled time.


6. Sharing Vacation Details
From the Vacation Details screen:
Use the share feature to send vacation information via:
Email
SMS
Other compatible applications
The message is automatically populated with all relevant vacation details.


7. Sample Data Feature
Use the menu option to generate sample excursion data.
The app will automatically navigate to the associated vacation where the data was added.


Android Version
Minimum SDK: API 26 (Android 8.0)
Target SDK: API 36


Git Repository
Repository Link:
https:


Features Implemented:
Full CRUD operations for vacations and excursions
Room Database integration for persistent data storage
RecyclerView for displaying dynamic lists
Input validation for dates and required fields
AlertManager for scheduled notifications
Intent-based navigation between activities
Built-in sharing functionality for vacation details

Author:
Developed by Ivan Cozmulici
