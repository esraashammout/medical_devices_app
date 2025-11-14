# MedTech Mobile App (Flutter)

A comprehensive mobile application for the Medical Devices Management System, built with Flutter. This app serves clients, allowing them to browse, purchase, rent, and manage medical devices seamlessly.

---
![Uploading photo_2025-09-01_21-41-59.jpg…]()

![photo_2025-09-01_21-41-53](https://github.com/user-attachments/assets/0c5736ca-1b66-4d4e-ac00-a8b964129860)

![photo_2025-09-01_21-41-59](https://github.com/user-attac![photo_2025-09-01_21-41-56](https://github.com/user-attachments/assets/15d7fb1f-da8a-4ce8-9328-0763b2923395)
hments/assets/80f5926e-dc9b-4118-ac6c-44b5a656bee1)


## ✨ Features

*   **User Authentication:** Secure login with email/password and biometric (fingerprint) support.
*   **Product Catalog:** Browse and search for medical devices with detailed specifications and images.
*   **Shopping Cart & Checkout:** Full e-commerce functionality with Stripe integration.
*   **Rental System:** Schedule device rentals and manage maintenance appointments.
*   **Order History:** Track the status of current and past orders.
*   **Real-time Notifications:** Receive updates on orders and appointments via Firebase Cloud Messaging.
*   **User Profile Management:** Users can update their personal information and view their activity.

---

## 🛠️ Tech Stack & Architecture

*   **Framework:** Flutter
*   **Programming Language:** Dart
*   **Architecture:** Clean Architecture
*   **State Management:** Bloc
*   **Database:** Firebase (Firestore for data), SQLite (for offline caching)
*   **API Integration:** RESTful APIs using the Dio package
*   **Authentication:** Firebase Authentication
*   **Notifications:** Firebase Cloud Messaging (FCM)

---

## 🚀 How to Run

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/esraashammout/MedTechMobile-main.git
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd MedTechMobile-main
    ```
3.  **Install dependencies:**
    ```sh
    flutter pub get
    ```
4.  **Set up Firebase:**
    *   You will need to create a `google-services.json` file for Android and a `GoogleService-Info.plist` file for iOS from your own Firebase project and place them in the correct directories.

5.  **Run the app:**
    ```sh
    flutter run
    ```

---
