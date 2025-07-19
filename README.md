# FindIt – Lost & Found Mobile App

FindIt is a Lost & Found app built with **Flutter** and **Firebase**, featuring Google Maps integration for accurate location tagging. Designed for campus and community use, it provides a seamless experience for reporting, browsing, and recovering lost or found items.

---

## Features

- **User Authentication:** Register and log in using email or Google.
- **Report Items:** Add lost/found items with photo, description, and Google Maps location picker.
- **Browse & Search:** Filter and search items by date, location, and category.
- **Interactive Map:** Choose or view item locations using an embedded Google Map.
- **Chat/Messaging:** Contact the owner or finder securely.
- **Push Notifications:** Stay updated about new items and status changes.
- **Modern UI:** Clean interface with white background, vivid orange-violet gradients, and glass-effect components.

---

## Screenshots

> _(Place screenshots or mockups here, e.g., UI home page, item submission, map picker.)_

---

## Tech Stack

| Purpose                  | Technology                      |
|--------------------------|---------------------------------|
| Cross-platform UI        | Flutter                         |
| Backend Database         | Firebase Firestore               |
| User Authentication      | Firebase Auth                   |
| Images/Files             | Firebase Storage                |
| Push Notifications       | Firebase Cloud Messaging        |
| Location Services        | Google Maps API (`google_maps_flutter`) |

---

## Getting Started

### Prerequisites

- Flutter SDK (latest stable)
- Dart SDK
- Firebase account & project
- Google Maps API key (enabled for Android/iOS)

### Installation Steps

1. **Clone the Repo:**

2. **Install Dependencies:**

3. **Add Firebase Configuration:**
- Add `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) from the Firebase Console to the respective folders.

4. **Set Up Google Maps:**
- Enable **Maps SDK** in your Google Cloud Console.
- Add your Maps API key(s) to `android/app/src/main/AndroidManifest.xml` and `ios/Runner/AppDelegate.swift` as per [google_maps_flutter setup](https://pub.dev/packages/google_maps_flutter).

5. **Run the App:**

---

## Configuration

- **Firebase:** Set up authentication, Firestore, storage, and messaging as per the [Firebase Flutter documentation](https://firebase.flutter.dev/).
- **Google Maps:** Place your API key as described in Installation.

---

## Contributing

Contributions welcome! Please open an issue or submit a pull request for new features or improvements.

---

## License

This project is for educational/demo purposes. For commercial use, please see the `LICENSE.md` file.

---
