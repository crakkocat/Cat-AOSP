#🐱 Cat-AOSP

Cat-AOSP is a custom fork of Dolphin Emulator (based on build 2512).

It focuses on:

Stability

Performance tuning

Cross-platform builds

iOS support

Community-driven improvements

📦 Downloads

Prebuilt binaries are available for:

Windows (x64 / ARM64)

macOS

Linux

Android (APK)

iOS (IPA – sideload required)

🍎 iOS Installation Guide

⚠️ The IPA cannot be installed directly. It must be sideloaded.

🪟 Windows Setup
Requirements

Windows 10 or later

iTunes (non-Microsoft Store version):
https://support.apple.com/en-us/106372

iCloud (non-Microsoft Store version):
http://updates-http.cdn-apple.com/2020/windows/001-39935-20200911-1A70AA56-F448-11EA-8CC0-99D41950005E/iCloudSetup.exe

⚠️ Do NOT use Microsoft Store versions.

Sideloading Tools

3uTools

AltServer

Sideloadly (Recommended – supports automatic re-signing)

Installation Steps

Install iTunes and iCloud.

Install a sideload tool.

Connect your iOS device.

Sign the Cat-AOSP IPA.

Install to device.

On device:

Settings → General → VPN & Device Management

Trust your developer profile.

Launch Cat-AOSP.

🍎 macOS Setup
Requirements

macOS 10.14 or lower (iTunes required)

iCloud (pre-installed)

Tools

3uTools

AltServer

Sideloadly (Recommended)

Steps

Install sideload tool.

Connect device.

Sideload the IPA.

Trust developer profile.

Launch the app.

🐧 Linux Setup
Requirements

Any Linux distribution

Legacy-iOS-Kit

Installation Steps
cd <LegacyiOSKit>
bash restore.sh

Or:

./restore.sh

Enter your password if prompted.

Select App Management

Choose the Cat-AOSP IPA

Sign the app

Launch it on your device

⚠️ Important Notes

Free Apple developer accounts expire every 7 days.

Re-signing is required unless using a paid Apple Developer account.

Sideloadly auto-refresh is recommended for convenience.



