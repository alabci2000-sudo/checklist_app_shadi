# Checklist App (Flutter)
This Flutter project is a ready-to-build Android app for daily equipment checks (Arabic UI).

## How to build APK (short)
1. Install Flutter: https://flutter.dev/docs/get-started/install
2. Extract this project.
3. In the project folder run:
   ```
   flutter pub get
   flutter build apk --release
   ```
4. The APK will be in `build/app/outputs/flutter-apk/app-release.apk`.

## Notes
- The app saves data locally using sqflite.
- Use the calendar button to switch dates.
- Use the PDF icon to export/share a PDF for the selected date.
- You can add new devices from the + button.
