# AK Dots & Boxes Android

This is an Android WebView wrapper for the uploaded game, with original sound files and icon.

## Build without Android Studio
1. Create a new **public or private** GitHub repository.
2. Upload **the contents of this ZIP** to the repository root, keeping folders intact. (GitHub's web uploader accepts files and folders via drag-and-drop.)
3. Go to **Actions** > **Build Android APK** > **Run workflow**. On first upload, a build may start automatically.
4. Wait for the green checkmark, open the workflow run, and download the **AK-Dots-Boxes-APK** artifact.
5. Unzip the artifact to get **app-debug.apk**. Copy it to your Android phone and install it, allowing installation from that source if prompted.

Note: Android build tools and Gradle dependencies are downloaded by GitHub Actions. The debug APK is installable for testing, not a Play Store release build. The game includes an external Font Awesome CDN dependency, so some interface icons may require internet access. The core game assets and audio are packaged locally.
