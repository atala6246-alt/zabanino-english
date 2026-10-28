Zabanino English Android app project

IMPORTANT: This ZIP is source code, not an APK. The GitHub Actions workflow builds the APK online.

PHONE STEPS:
1. Download and extract this ZIP.
2. In Chrome, open https://github.com and sign in/create an account.
3. Create a new repository named zabanino-english. Public is simplest.
4. In the repository, choose Add file > Upload files. Upload the CONTENTS of this folder, keeping folders in their original structure. Make sure the .github/workflows/build-apk.yml file is included.
5. Commit/upload the files to the main branch.
6. Open the Actions tab. If GitHub asks, enable Actions.
7. Select "Build Android APK". If you see "Run workflow", tap it and confirm.
8. Wait until the run finishes with a green check.
9. Open the completed run and download the artifact named "zabanino-english-apk".
10. Extract the downloaded artifact ZIP. Tap app-debug.apk and choose Install. If prompted, allow Chrome or Files to install unknown apps.

If the build fails, open the run and share a screenshot of the error.

This is a debug APK for personal testing, not a Play Store release. Internet is required for online vocabulary/definition resources; speaking depends on Android speech recognition support.
