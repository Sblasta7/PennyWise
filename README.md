# PennyWise

---
A budgeting and investment mobile application as a personal project to simplify financial management and empower users to make informed decisions.

---
## Table of Contents
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Technology Stack](#technology-stack)  
- [Contributing](#contributing)  
- [License](#license)  

---

## **Features**  
- **Expense Tracking:**  
  Log and categorize daily expenses to monitor spending habits.  

- **Budget Management:**  
  Create and manage budgets with dynamic categorization and tracking.  

- **Investment Simulation:**  
  Simulate stock investments starting with a virtual balance of $10,000, with real-time data updates.  

- **Customizable Themes:**  
  Choose between light, dark, or automatic themes to enhance usability and user experience.  

- **Secure Authentication:**  
  User data is securely managed through Firebase Authentication and Firestore database integration.  

- **Engaging Interface:**  
  Intuitive design with material components for seamless navigation.  

---
## **Installation**

Follow these steps to set up and run the Kotlin app on your local machine:

### Prerequisites

1. **Android Studio**
   - Download and install the latest version of [Android Studio](https://developer.android.com/studio).
   - Ensure the following tools and plugins are installed:
     - Kotlin plugin
     - Android SDK (version required by the app)
     - Gradle build system

2. **Java Development Kit (JDK)**
   - Install JDK 11 or later. You can download it from [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html) or [AdoptOpenJDK](https://adoptopenjdk.net/).

3. **Firebase Tools (if applicable)**
   - If the app uses Firebase, create a Firebase project and download the `google-services.json` file.
   - Place the `google-services.json` file in the `app/` directory of the project.

---

### Installation Steps

1. **Clone the Repository**
   Clone this repository to your local machine using Git:
   ```bash
   git clone https://github.com/Sblasta7/PennyWise.git
   cd PennyWise
   ```

2. **Open the Project in Android Studio**
   - Launch Android Studio.
   - Open the cloned project folder (`File > Open`).
   - Wait for Gradle to sync. If prompted, update any outdated dependencies.

3. **Sync Gradle**
   - Ensure all dependencies are downloaded and configured by syncing the Gradle files:
     - In Android Studio, navigate to `File > Sync Project with Gradle Files`.
   - Resolve any errors or missing dependencies that may appear.

4. **Connect a Device or Emulator**
   - Use a physical Android device:
     - Enable "Developer Mode" and "USB Debugging" on your device.
     - Connect the device via USB and ensure it appears in Android Studio under "Device Manager."
   - Or set up an Android Emulator:
     - In Android Studio, navigate to `Tools > Device Manager` and create a new virtual device.

5. **Run the App**
   - In Android Studio, select the device or emulator where you want to run the app.
   - Click the "Run" button (green triangle) or press **Shift + F10** to build and deploy the app.

---

### Troubleshooting

- **Gradle Sync Issues**  
  If Gradle fails to sync, ensure that:
  - You have a stable internet connection.
  - You’ve updated Android Studio and all SDK tools to their latest versions.

- **Firebase Errors**  
  If the app uses Firebase and you encounter errors:
  - Confirm that the `google-services.json` file is correctly placed in the `app/` directory.
  - Verify that your Firebase project settings match the app package name.

- **Device Not Recognized**  
  If your physical device is not detected:
  - Ensure the USB drivers for your device are installed.
  - Check that "USB Debugging" is enabled.

For further assistance, feel free to open an issue in the repository.

---

You’re all set! 🎉 If you encounter any additional issues, don’t hesitate to reach out.

---





## **Technology Stack**  

- **Frontend**:  
  - Kotlin (Android Studio)  

- **Backend**:  
  - Node.js  
  - Firebase Admin SDK  

- **Database**:  
  - Firestore  

- **Authentication**:  
  - Firebase Authentication  

- **CI/CD**:  
  - GitHub Actions for automated testing and deployment  

