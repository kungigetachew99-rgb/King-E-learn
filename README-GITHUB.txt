BUILD YOUR APK USING GITHUB (PHONE ONLY)

1. Sign in or create a GitHub account at https://github.com
2. Create a NEW PUBLIC or PRIVATE repository named DailyEnglishGrowthAPK.
3. In the repository, tap Add file > Upload files and upload DailyEnglishGrowthAndroid.zip from this folder. Commit the upload.
4. Create the workflow file:
   - Tap Add file > Create new file.
   - For the filename, enter exactly: .github/workflows/build-apk.yml
   - Open build-apk.yml from this package in a text editor and copy all its text into the GitHub editor.
   - Tap Commit changes.
5. Open the repository's Actions tab. Choose "Build Android APK". If it hasn't started automatically, tap Run workflow.
6. Wait for the workflow to finish with a green check mark.
7. Open the successful workflow run and scroll to Artifacts. Download DailyEnglishGrowth-debug-apk.
8. Extract the downloaded artifact ZIP. It contains app-debug.apk.
9. Tap app-debug.apk to install it. Android may ask you to allow your browser or Files app to install unknown apps. Only allow this for the APK you built from your own repository, then turn the permission off again if you prefer.

NOTES
- The build may reveal source-code errors; if the workflow fails, open the run and share the red error text or screenshot so it can be fixed.
- This workflow builds an unsigned debug APK for testing, not a Play Store release.
- Keep your GitHub account password and verification codes private.
