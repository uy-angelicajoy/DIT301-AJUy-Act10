# Troubleshooting Guide

## NDK Installation Issues

If you encounter "Install NDK failed" errors, try these solutions:

### Solution 1: Install NDK via Android Studio
1. Open Android Studio
2. Go to Tools → SDK Manager
3. Click on "SDK Tools" tab
4. Check "NDK (Side by side)"
5. Click "Apply" to install

### Solution 2: Use Web or Windows Instead
If Android is giving you trouble, Flutter can run on other platforms:

```bash
# Run on Windows (fastest for testing)
flutter run -d windows

# Run on Web (no installation needed)
flutter run -d chrome
```

### Solution 3: Clean and Rebuild
```bash
flutter clean
flutter pub get
flutter run -d emulator-5554
```

## Common Issues

### Gradle Build Timeout
- First builds can take 5-10 minutes
- Be patient and let it complete

### Emulator Not Found
```bash
# List available devices
flutter devices

# Start an emulator from Android Studio first
```

### Dependencies Issues
```bash
flutter doctor
flutter pub get
```

## Quick Test on Windows

The fastest way to see the app working:

```bash
flutter run -d windows
```

This bypasses all Android/NDK issues and runs natively on Windows!
