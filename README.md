Our platform is designed to help rural SMEs connect with investors, venture capitalists, and students. We’re bringing AI-driven investment insights, automated loan assistance chatbots, and seamless communication tools to the table. Built with Flutter, Firebase, and Vertex AI, this app is all about simplicity and scalability. Features

Secure Firebase Authentication
AI-Driven Investment Insights
Automated Loan Assistance Chatbot
Video/Voice Chat and Forums
Exclusive SME and Investor Feed
Investment Communities
Student Dashboard
Seamless UI for Easy Navigation
App Access
APK link: download the app from this link (https://gofile.io/d/lqWNe2)

Download and Install the apk on your phone to run the flutter mobile application

How to Build and Run the Android App
System Requirements

Operating System: Windows, macOS, or Linux Disk Space: At least 1.64 GB Tools: Flutter SDK, Android SDK, Git

Install Flutter SDK

Download Flutter: Grab the latest Flutter SDK from Flutter's official website.

Extract and Setup PATH: Extract it to a folder and add the Flutter SDK path to your system’s PATH.

For Windows:

set PATH=%PATH%;<flutter_install_directory>\bin
For macOS/Linux:

bash

export PATH="$PATH:<flutter_install_directory>/bin"
Verify Installation: Open your terminal and run:

flutter doctor
Follow the instructions to fix any missing dependencies.

Install Android Studio

Download and Install Android Studio: Download it from the Android Studio website and install it.

Configure Android SDK: After installing, open Android Studio and go to Configure > SDK Manager. Make sure the following are installed: Android SDK Android SDK Platform-Tools Android Emulator Android Virtual Device (AVD) Manager

Install Android Device Tools: Ensure you’ve downloaded the SDK for your Android version (e.g., API Level 30 or higher). Enable USB debugging on your physical device (Settings > Developer Options > Enable USB Debugging).

Run an Android Emulator or Connect a Device: You can set up an Android emulator through AVD Manager in Android Studio or connect a real device via USB.

Set Up an Android Device

Enable Developer Options: On your Android device, go to Settings > About Phone and tap the Build Number seven times to unlock developer options.

Enable USB Debugging: Go to Developer Options and enable USB Debugging.

Connect the Device: Plug your device into your computer via USB.

Running the App on Android

Open Terminal in the Project Directory: Navigate to your project folder and run:

Get all the dependencies by running

flutter pub get
Run the application

flutter run
Flutter will detect the connected Android device or emulator and build your app.

Select Your Target Device: If you have multiple devices (like an emulator and a physical device), you can list them with:

flutter devices

Choose the device by its index.

Run and Test the App: The app will be installed and launched on the device. You’ll see the log output in your terminal.
Building APK for Android Release
When you’re ready to release your app, create a release APK:

Build the APK:
flutter build apk --release
This command will generate the release APK.

Locate the APK: The generated APK will be located at:

<project_directory>/build/app/outputs/flutter-apk/app-release.apk
