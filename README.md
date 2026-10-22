# Zoya AI Voice Assistant - Android Studio Project

This directory contains the complete native Android project configured for **Zoya - AI Voice Assistant** created by **Aadil**.

---

## 🚀 Quick Setup in Android Studio

1. **Open Android Studio**.
2. Click **File > Open** (or on the welcome screen choose **Open**).
3. Select this folder: `android` (or the extracted `ZoyaAndroidApp` folder).
4. Wait for Android Studio to sync Gradle dependencies.
5. Connect your Android phone with USB (with USB Debugging turned ON) or select an Android Emulator.
6. Click the green **Run (▶)** button!

---

## 📦 How to Build an APK file (.apk)

1. In Android Studio's top menu, go to:
   **Build > Build Bundle(s) / APK(s) > Build APK(s)**
2. Once the build finishes, click the **"locate"** link in the bottom-right notification popup.
3. You will find `app-debug.apk`!
4. Transfer this `.apk` to any Android device or share it via WhatsApp/Drive and install it directly!

---

## 🎙️ Microphone & Audio Permissions

The app has already been configured with:
- `android.permission.RECORD_AUDIO`
- `android.permission.INTERNET`
- `android.permission.MODIFY_AUDIO_SETTINGS`
- `WebChromeClient.onPermissionRequest` automatic audio grant

When the app launches for the first time, it will prompt for microphone permission. Once allowed, Zoya can hear you in real-time and answer with voice!
