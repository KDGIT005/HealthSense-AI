# HealthSenseAI – Disease Prediction App Using Smartwatch Sensor Data

HealthSenseAI is a Kotlin + XML Android app showcasing a complete UI for a future smartwatch-driven health monitoring and disease prediction platform.

## Purpose
- Present a clean, modern Material 3 UI themed for health/medical use
- Use dummy, static values for all screens
- No integrations or background services

## Future Integrations
- Google Fit data ingestion from smartwatch metrics
- Firebase storage for historical health data
- On-device ML (TensorFlow Lite) for risk prediction
- Notifications and alerts for potential health risks

## What’s Included (UI Only)
- Onboarding (3 slides + Get Started)
- Login / Signup (non-functional)
- Home Dashboard (static health metrics + Predicted Risk)
- Insights (cards with placeholder charts and 7-day dummy values)
- Predictions (coming soon message + dummy result)
- Notifications (static sample alerts)
- Profile (dummy user, watch status, app info)

## Architecture & Tech
- MVVM-style folder structure (`ui`, `viewmodel`, `adapters`, `models`, `utils`)
- Kotlin + XML
- Material 3 components
- No Firebase, Google Fit, ML, permissions, or background workers

## How to Run
1. Open the project in Android Studio (Giraffe or newer recommended).
2. Let Gradle sync.
3. Build and run the `app` module on an emulator or device.
4. The app launches to Onboarding. Tap Get Started → Login → Login button → Home.

## Notes
- All data is static and local.
- Navigation uses a BottomNavigationView with fragment transactions.
- A placeholder navigation graph XML is included under `res/navigation` for future use.