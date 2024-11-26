# PennyWise

---
A budgeting and investment mobile application as a personal project to simplify financial management and empower users to make informed decisions.

---
## Table of Contents
- [Features](#✨-features)  
- [Installation](#🚀-installation)  
- [Technology Stack](#💻-technology-stack)
- [Screenshots](#📸-screenshots)
- [License](#📝-license)  

---

## ✨ **Features**  
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
## 🚀 **Installation**

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

## 💻 **Technology Stack**  

[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/en)  
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/)
[![Firestore](https://img.shields.io/badge/Firestore-FFBB33?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/docs/firestore)
[![Firebase Authentication](https://img.shields.io/badge/Firebase_Authentication-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/docs/auth)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)

---

## 📸 Screenshots

| Feature           | Screenshot                                                                                     |
|-------------------|------------------------------------------------------------------------------------------------|
| Home Page         | <img src="https://github.com/user-attachments/assets/b5c63e86-24b5-4550-a7bd-74b9d8137694" width="200" height="355"/> |
| Transactions Page | <img src="https://github.com/user-attachments/assets/30a880a6-61c4-4385-9d21-5a68c01c5884" width="200" height="355"/> |
| Categories Page   | <img src="https://github.com/user-attachments/assets/1c7b8816-f291-432a-b631-86a743cb8fc2" width="200" height="355"/> |
| Goals Page        | <img src="https://github.com/user-attachments/assets/e0be9a76-253f-43e1-adc4-f98b67232e4c" width="200" height="355"/>  |
| Analytics Page    | <img src="https://github.com/user-attachments/assets/faa0d51d-ea48-4a0d-b3cd-3c3c09ec55c6" width="200" height="355"/>  <img src="https://github.com/user-attachments/assets/bed37574-8668-44c1-8741-1b6e98d4633c" width="200" height="355"/> |
| Market Screen     | <img src="https://github.com/user-attachments/assets/6f97ecae-f246-43fa-9df1-76f7cb1f8df9" width="200" height="355"/> |
| Portfolio Screen  | <img src="https://github.com/user-attachments/assets/4136a44b-d517-4b63-83d7-b57f3dbb2798" width="200" height="355"/> |
| Stock Screen      | <img src="https://github.com/user-attachments/assets/b3eba4a4-9a07-4f6f-b937-c87d14498f17" width="200" height="355"/> |


---
## 📝 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and distribute it as per the license terms.



