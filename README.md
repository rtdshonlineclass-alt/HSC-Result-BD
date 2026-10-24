# HSC Result BD Android project

This is a simple Android WebView wrapper around the supplied `index.html`.

## Build a free APK using GitHub Actions
1. Create a GitHub account and a new repository.
2. Upload the *contents* of this folder to the repository root (not the ZIP file itself).
3. Open the repository's **Actions** tab and enable Actions if asked.
4. Choose **Build HSC Result BD APK** and press **Run workflow**, or push a commit to `main`.
5. When the run finishes, open the successful workflow run and download the `HSC-Result-BD-APK` artifact.
6. Extract the downloaded artifact ZIP on your Android phone; install `app-debug.apk`.

Note: This is an unsigned debug APK for personal/testing use. Government result sites can block loading inside an iframe/WebView; the supplied HTML already includes a fallback link to open the official site. This app is not an official government app.

The workflow uses the installed `gradle` command on GitHub's runner, so no Gradle wrapper is required.
