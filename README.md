# FRIENDS & CO. — Android testing starter

This is an Android WebView wrapper around the existing HTML prototype, NOT a completed business accounting system.

## Build APK using GitHub
1. Create a new GitHub repository (e.g. `friends-co-android`).
2. Upload the **contents** of this folder to the repository root, including `.github/workflows/android-apk.yml`.
3. Open the repository's **Actions** tab, select **Build Android APK**, and click **Run workflow** (or push to main).
4. After the workflow succeeds, open its run and download artifact **FRIENDS_CO_Debug_APK**.
5. Extract the artifact ZIP to obtain `app-debug.apk`, then install it on your Android device.

## Important limitations
- This is an early local-only TEST APK. Do NOT use it for live financial records.
- No cloud backups, real accounting ledger, multi-godown stock, returns, PDF invoices, or reliable daily profit calculations yet.
- Browser/WebView local storage can be cleared on app data deletion or uninstall.
- APK is a debug build signed with a debug key; not suitable for Play Store distribution.
- The APK build has not been run in this environment. GitHub Actions will compile it.
