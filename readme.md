# iOS Backup & Restore App

## Overview
This is an iOS application that allows users to **backup** and **restore** their photos and contacts to and from **Google Drive**. The app uses **Google Sign-In** for authentication and integrates with the **Google Drive API** for cloud storage.

## Features
- **Sign in with Google Drive**
- **Backup Photos** to Google Drive
- **Backup Contacts** to Google Drive
- **Restore Photos** from Google Drive
- **Restore Contacts** from Google Drive

## Technologies Used
- **SwiftUI** for the user interface
- **GoogleSignIn** for authentication
- **GoogleAPIClientForREST** for interacting with Google Drive
- **Contacts Framework** for managing contacts
- **Photos Framework** for accessing photos

## Setup & Installation
### Prerequisites
1. Install **Xcode** (latest version).
2. Install **CocoaPods** (if not installed):
   ```bash
   sudo gem install cocoapods
   ```
3. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ios-backup-app.git
   cd ios-backup-app
   ```
4. Install dependencies:
   ```bash
   pod install
   ```

### Google API Setup
1. Create a **Google Cloud Project**.
2. Enable the **Google Drive API**.
3. Create OAuth 2.0 credentials and download the `GoogleService-Info.plist` file.
4. Add `GoogleService-Info.plist` to your Xcode project.

## Running the App
1. Open `ios-backup-app.xcworkspace` in Xcode.
2. Select a simulator or connect a real device.
3. Click **Run** (`Cmd + R`).

## Usage
1. **Sign in** to Google Drive.
2. Tap **Backup Photos** to upload images to Drive.
3. Tap **Backup Contacts** to save contacts.
4. Tap **Restore Photos** to download photos from Drive.
5. Tap **Restore Contacts** to retrieve contacts from Drive.

## Contributing
Feel free to fork this repository and submit pull requests for improvements.

## License
This project is licensed under the **MIT License**.

