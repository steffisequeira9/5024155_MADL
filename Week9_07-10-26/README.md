# Week 9 — Task 9: Flutter UI Connected to Firebase
**B3 date:** 07 October 2026

Demonstrates a Flutter form that writes student records to Firebase Realtime Database and displays saved records.

Add dependencies to `pubspec.yaml` (use compatible current versions if these conflict with your Flutter SDK):
```yaml
firebase_core: ^3.15.2
firebase_database: ^11.3.10
```
Configure Firebase for your Android app using FlutterFire, generate `firebase_options.dart`, import it, and initialize with `Firebase.initializeApp(options: DefaultFirebaseOptions.currentPlatform)`. Enable Realtime Database and configure secure database rules before running. The current `main.dart` uses `Firebase.initializeApp()` as a simple starting point and may need the generated options for your app's platform.