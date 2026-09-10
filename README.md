MAD Practical 4 - Alarm Application

An Android application developed as part of the Mobile Application Development (MAD) course. This project demonstrates the implementation of an alarm system using AlarmManager, BroadcastReceiver, and Service in Android.
📱 Features

    Real-time Clock: Displays a live digital clock with date and time.
    Create Alarm: Allows users to set an alarm time using a TimePickerDialog.
    Alarm Notification: Plays a sound in the background when the alarm goes off.
    Cancel Alarm: Option to cancel the scheduled alarm or stop the alarm sound currently playing.
    Material Design: Beautiful UI built with Material3 components and cards.

🛠️ Technologies Used

    Language: Kotlin
    UI Framework: Android XML (Material Design)
    Key Components:
        AlarmManager: For scheduling exact alarms.
        BroadcastReceiver: To receive alarm events.
        Service: To play the alarm audio in the background.
        MediaPlayer: For audio playback.

🔑 Permissions

The application requires the following permissions to function correctly on modern Android versions:

    android.permission.SCHEDULE_EXACT_ALARM
    android.permission.USE_EXACT_ALARM

🚀 Getting Started

    Clone the repository or download the project files.
    Open the project in Android Studio.
    Sync the project with Gradle files.
    Run the application on an Android Emulator or a physical device.

📁 Project Structure

    MainActivity.kt: Handles the UI logic and alarm scheduling.
    AlarmService.kt: Background service for playing the alarm sound.
    AlarmBroadcastReceiver.kt: Triggers the service when the alarm time is reached.
    activity_main.xml: The layout design using ConstraintLayout and Material Cards.

Author: Saumya (25172022067) Project: MAD Practical 4
