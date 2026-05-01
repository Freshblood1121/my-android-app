# HelloWorld Android App (Skeleton)

This repository now contains a minimal Android app skeleton (Kotlin) that builds to an APK when using Android Studio or Gradle.

How to build your APK (locally with Android Studio):
- Install Android Studio (with Android SDK and emulator/tools).
- Open the project root and let Gradle sync run.
- Run or Build -> Build APK(s) to generate the APK in
  app/build/outputs/apk/debug/app-debug.apk

Build from the command line (if you have Android SDK/Gradle installed):
- From repo root, run: ./gradlew :app:assembleDebug
- The APK will be at: app/build/outputs/apk/debug/app-debug.apk

Note: This is a minimal HelloWorld app. You can customize package name, application name, and UI easily by editing the Kotlin code and XML layouts.
