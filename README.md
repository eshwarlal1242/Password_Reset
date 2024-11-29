# Password_Reset
 Reset Password 
 # Firebase Authentication: Login, Sign Up, and Password Reset

This project demonstrates how to implement Firebase authentication in a Flutter application. It includes features for **User Login**, **User Sign Up**, and **Password Reset** through email links. Firebase is used for handling user authentication and email-based password reset.

## Features

- **User Login**: Allows users to sign in using their email and password.
- **User Sign Up**: Allows new users to sign up with email and password.
- **Password Reset**: Users can reset their password via a link sent to their registered email.

## Prerequisites

Before using this app, make sure you have the following:

- **Firebase Account**: Set up Firebase for your project.
  - Go to [Firebase Console](https://console.firebase.google.com/), create a new project, and set up Firebase Authentication.
  - Enable **Email/Password Sign-In** in Firebase Authentication settings.
- **Flutter**: Install Flutter on your system if not already installed.
- **Firebase SDK**: Set up Firebase SDK in your Flutter project.

## Firebase Setup

1. Create a new Firebase project.
2. Add Firebase to your Flutter app by following the Firebase setup guide:
   - [FlutterFire Setup](https://firebase.flutter.dev/docs/overview).
3. Enable **Email/Password** authentication under the Firebase Authentication settings.
4. Configure your Firebase project with your Flutter app:
   - Add `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) to your project.
5. Install the necessary dependencies:
   ```yaml
   dependencies:
     firebase_auth: ^4.0.0
     firebase_core: ^2.0.0
     flutter:
       sdk: flutter

