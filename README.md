# My Expenses — GitHub Android APK Build

A simple mobile expense tracker with:
- Multiple expenses on the same date
- Amount, date, Grocery/Others category
- Manual Details field
- Total, Today, This Month, Grocery and Others summaries
- Filtering and daily grouping
- Persistent local storage

## GitHub build
This repository is configured for a GitHub Actions Android build. Upload the contents of this folder to a GitHub repository, then open **Actions** and run **Build Android APK**.

The workflow creates an `app-debug.apk` artifact that can be downloaded and installed on an Android phone.

## Important
The APK stores data locally on the device. It does not sync expenses between devices.
