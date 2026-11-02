SCHOOL FEE MANAGER — ANDROID APK BUILD PROJECT

This is a starter Android WebView wrapper around the School Manager MVP.
It loads the app from local Android assets, so the app itself can open offline.

BUILD APK USING GITHUB ACTIONS (can be done from a phone):
1. Create/sign in to a GitHub account.
2. Create a new repository, e.g. school-fee-manager.
3. Upload ALL files and folders from this project ZIP to the repository (keep folder structure).
4. Open the repository -> Actions tab.
5. Select "Build School Fee Manager APK" -> Run workflow.
6. Wait for the workflow to finish successfully.
7. Open the completed workflow run -> Artifacts -> SchoolFeeManager-debug-apk.
8. Download the artifact ZIP, extract it, and install app-debug.apk on Android.
   Android may ask to allow installation from that browser/file manager.

IMPORTANT LIMITATIONS:
- This is an initial MVP/debug APK build project, not a signed Play Store release.
- Each installation stores data locally on that device.
- Automatic mobile-to-laptop online sync, separate school cloud accounts, secure multi-school hosting,
  and production-grade authentication are NOT implemented yet.
- Back up data before uninstalling or changing devices.
- Test with dummy records first. Do not enter real student personal data until privacy/security work is complete.
