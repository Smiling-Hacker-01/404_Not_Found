# MedBuddy
# SDG: Good Health and Well Being
Problem Statement: Connecting Urban Doctor's with Rural Village people who do not have access to quality consulation.
     expo-env.d.ts >>>This file contains the screen records of the app being run on Expo Go SDK 52 Version
MedBuddy is a **React Native (Expo)** mobile application designed to securely store and manage personal medical information and connect doctors in urban areas with people in rural areas. It helps users to connect to doctors who can easily track their patient's medical history, prescriptions, doctor consultations and health metrics efficiently.

## 📌 Features

- **User Profile Management** (Name, Phone, Email, Date of Birth, etc.)
- **Doctor Consultation**
- **Prescription & Medicine Tracking along with alarm feature reminders (OCR for handwritten prescriptions text analysis)**
- **Medical Conditions & Disease Logging**
- **Allergy Records & Immunization Tracking**
- **Health Metrics Storage** (Blood Pressure, Pulse, etc.)
- **Offline Data Storage with Cloud Sync (Firestore)**
- **Login/Sign-up with OTP Authentication**

## 🚀 Technologies Used

- **Frontend**: React Native (Expo)
- **Backend**: Firebase Firestore (Database)
- **Authentication**: Firebase Authentication (OTP-based login)
- **OCR Feature**: Google ML Kit for Text Recognition

## 🛠️ Installation & Setup

### Prerequisites:

- Node.js & npm installed
- Expo CLI installed (`npm install -g expo-cli`)
- Firebase project set up

### Steps:

1. **Clone the repository**

   ```sh
   git clone https://github.com/Smiling-Hacker-01/404_Not_Found.git
   cd MedBuddyFinal
   ```

2. **Install dependencies locally inside your project file**

   ```sh
   npm install
   ```

3. **Set up Firebase (Optional- if you want it to be offline skip this)**

   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Firestore Database & Authentication (Phone OTP)
   - Add your `firebaseConfig` inside `firebase.js`

4. **Run the application**

   ```sh
   npx expo start
   ```

## 🤝 Contributing

Feel free to submit issues or pull requests to improve MedBuddyFinal!

## 📧 Contact

For queries or collaborations, reach out to **mdkaif11894@gmail.com** email.

---

**Developed using React Native & Firebase**

