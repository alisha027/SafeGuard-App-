🚨 Safeguard App

Safeguard is a feature-rich personal safety Android application developed using Kotlin, designed to help users quickly alert their trusted contacts in emergency situations. The app allows seamless management of trusted contacts and location permission handling, all wrapped in a clean, bold UI with a red and white safety theme.

✨ Features
🔴 Send Emergency Alert:
Instantly notifies all saved trusted contacts with an emergency message and your current location (if granted).

📇 Manage Trusted Contacts:
Add new contacts and perform actions on each one:

📞 Call

💬 Message

❌ Delete

📍 Request Location Permission:
The app requests location permission at launch. If denied, the user can tap this button to re-request.
If already granted, a Toast message will confirm: "Location already granted."


🚀 Tech Stack
Language: Kotlin

Platform: Android

Architecture: MVVM (optional to mention if you're using it)

UI: Jetpack Compose / XML (mention which you’re using)

Others: Toasts, Intents, SharedPreferences (for contact storage if used)

📋 How It Works
On launch, the app requests location permission.

You can manage your trusted contacts — add, call, message, or delete.

When the "Send Emergency Alert" button is pressed:

A predefined emergency message is sent to all trusted contacts.

The message may contain your current location (if permission is granted).

🔐 Permissions Used
ACCESS_FINE_LOCATION – To share your current location with trusted contacts.

SEND_SMS or SMS Intent – To send emergency alerts (based on how you've implemented messaging).

CALL_PHONE – If calling functionality uses direct dialing (optional).

🛠️ Setup Instructions
Clone the repository

bash
Copy
Edit

Open in Android Studio.

Connect your device or emulator and run the app.

Make sure to enable the required permissions on your device.

💡 Future Enhancements
Add voice command support to trigger alerts.

Add alert confirmation screen with countdown.

Firebase or cloud integration for data backup.

📬 Contact
For queries or collaborations:
Alisha Vashisht – vashishtalisha02@gmail.com
