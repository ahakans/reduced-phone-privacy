# Privacy Policy for Reduced Phone

**Effective Date:** November 25, 2026

**Reduced Phone** is a minimalist Android launcher designed to promote digital well-being and mindful smartphone usage. Your privacy is fundamental to our design.

## 1. Local-Only Data Processing (Never Leaves Your Device)
To provide core digital well-being features, Reduced Phone accesses and processes the following data **strictly locally on your device**:
- **App Usage Statistics (`PACKAGE_USAGE_STATS`):** Used exclusively on your device to display your daily screen-time summary, enforce optional daily time limits, and manage session durations. Your installed app list, screen-time durations, and session timers are **never** transmitted to any server.
- **Accessibility Service (`AccessibilityService`):** Used solely on-device to (1) lock the screen when you double-tap the home screen (`GLOBAL_ACTION_LOCK_SCREEN`) and (2) detect when a restricted app is opened—including via notifications, links, or recents—so the configured awareness pause and session duration prompt can be shown. Reduced Phone uses `canRetrieveWindowContent="false"`, does **not** read or scrape screen text/content, does **not** alter system settings on your behalf without your action, and **never** transmits accessibility data off your device.
- **Calendar & Quick Notes:** Calendar events and personal notes created inside the launcher widgets remain strictly local on your device.
- **Preferences & Settings:** Selected favorite/pinned apps, hidden or restricted app lists, swipe-up/double-tap gesture settings, custom pause durations, accent colors, and language preferences are stored locally via Android SharedPreferences / DataStore.

## 2. Optional Anonymous Analytics (Opt-In Only)
During onboarding (or anytime in Preferences), you may optionally choose to share anonymous usage metrics to help improve the app.
- **What is collected (only if you opt in):** Anonymous interaction counters (e.g., how many times the awareness pause screen was triggered, completed, or cancelled), widget/feature activation status, device brand, Android version, and a randomly generated, resettable session UUID.
- **What is NOT collected:** No names, email addresses, device identifiers (IMEI/Android ID), installed app names, screen content, or personal screen-time logs.
- **How to opt out:** You can disable anonymous analytics at any time with a single tap at the bottom of the Preferences screen inside the app, which immediately deletes the local session UUID.

## 3. User-Submitted Feedback
If you voluntarily submit feedback or feature requests through the in-app Feedback form, your message along with basic device model/OS version information is transmitted securely via HTTPS using **Formspree** solely to respond to and implement your suggestions.

## 4. Data Sharing & Third Parties
We do **not** sell, rent, or trade any user data. We do not use third-party advertising networks.

## 5. Contact
If you have any questions regarding this Privacy Policy or your data, please contact the developer via the in-app Feedback form or through GitHub (`github.com/ahakans`).
