LAW STUDY CENTRE — ANDROID APK PROJECT

This project packages the Law Study Centre learning prototype into an Android app using a local WebView. The HTML is bundled inside the app, so the learning screens work offline after installation. Quiz history is stored locally on the device.

BUILD LOCALLY (computer with Android Studio):
1. Install Android Studio and Android SDK Platform 35.
2. Open this folder as an existing Android Studio project.
3. Let Gradle sync finish.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The debug APK will be at app/build/outputs/apk/debug/app-debug.apk.

BUILD USING GITHUB ACTIONS (can be started from a phone):
1. Create/sign in to a GitHub account and create a new repository named LawStudyCentreAndroid.
2. Upload all files and folders from this project ZIP to the repository root. Keep the .github/workflows/build-apk.yml file; if hidden files are not shown, enable show hidden files or upload that folder separately.
3. Push/commit the files to the main branch.
4. In the repository, open Actions > Build Law Study Centre APK. If prompted, enable Actions. Run the workflow if it has not started automatically.
5. When the workflow finishes successfully, open its run and download the artifact named Law-Study-Centre-debug-APK. Extract the downloaded artifact ZIP to get app-debug.apk.
6. Transfer/open app-debug.apk on your Android phone and approve installation from that source if Android asks. Only install APKs you built or trust.

IMPORTANT:
- This is a debug APK project, not a Play Store release. A Play Store release requires signing, store assets, privacy disclosures, testing, and a release build.
- Premium items are demo previews only. No payment processing, student login, online admin panel, or remote course delivery is implemented.
- Legal learning content is introductory and should be checked against current official statutes and judgments.
