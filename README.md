# QR Card Android App

This is an Android application for the QR Card platform, which allows users to generate QR codes and earn money.

## Features

- **User Authentication**: Register and login using Firebase Authentication
- **Dashboard**: View stats and quick actions
- **QR Code Generation**: Generate QR codes to earn money
- **Wallet**: Track earnings and withdraw funds
- **Referral System**: Refer friends to earn more
- **Profile Management**: Update profile and bank details

## Project Structure

- **app/src/main/java/com/qrcard/app/**
  - **data/**: Data layer with models and repositories
  - **ui/**: UI layer with activities, fragments, and view models
  - **QRCardApplication.kt**: Application class

## Setup Instructions

1. **Prerequisites**:
   - Android Studio (latest version)
   - JDK 8 or higher
   - Android SDK

2. **Clone the Repository**:
   ```
   git clone <repository-url>
   cd QRCardApp
   ```

3. **Open in Android Studio**:
   - Open Android Studio
   - Select "Open an existing Android Studio project"
   - Navigate to the QRCardApp directory and click "Open"

4. **Firebase Setup**:
   - The app is already configured with Firebase
   - Make sure the Firebase project is properly set up with Authentication and Firestore

5. **Build and Run**:
   - Connect an Android device or use an emulator
   - Click the "Run" button in Android Studio

## Technologies Used

- **Kotlin**: Programming language
- **Firebase**: Authentication, Firestore, and Cloud Functions
- **Material Design**: UI components and styling
- **QRGen**: QR code generation library
- **Coroutines**: Asynchronous programming
- **ViewBinding**: View binding for UI components

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Firebase for backend services
- QRGen for QR code generation
- Material Design for UI components
