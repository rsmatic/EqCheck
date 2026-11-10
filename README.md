# Ring Out EQ (Android)

31-band graphic EQ, live spectrum and feedback finder for a microphone.
Android 8.0 or newer.

## Get the APK without installing anything (GitHub, in a browser)

1. Sign in at github.com (a free account is fine) and create a **new repository** (Public or Private).
2. On the new repo page, choose **uploading an existing file**, then drag in **everything inside this
   RingOutEQ folder** (including the `.github` folder) and click **Commit changes**.
   - If the `.github` folder doesn't upload, open the **Actions** tab, choose
     **set up a workflow yourself**, paste the contents of `.github/workflows/build-apk.yml`, and commit.
3. Open the **Actions** tab. The **Build APK** job runs by itself (about 3–5 minutes).
   If it doesn't start, click **Build APK** › **Run workflow**.
4. When it shows a green check, open the run and download **RingOutEQ-apk** under *Artifacts*.
   It's a .zip with `RingOutEQ.apk` inside.
5. Copy the APK to your phone, tap it, and allow **Install unknown apps** when Android asks.

## Or build with Android Studio

Open this folder in Android Studio, wait for Gradle sync, then
**Build › Build App Bundle(s) / APK(s) › Build APK(s)**.

## Using it

Tap **Start mic** and allow the microphone. Slowly raise your mixer gain until a tone rings;
the frequency appears in red. Tap **Notch** or **Cut band −3**, then repeat.
**Monitor out** sends the processed mic to the phone's headphone/USB output.
