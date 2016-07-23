## android-google-firebase-iid

Eclipse library project based on:<br/>
`ANDROID_SDK/extras/google/m2repository/com/google/firebase/firebase-iid/9.2.1/firebase-iid-9.2.1.aar`

**Notes:**
- **_Tag &lt;category&gt; attribute name has invalid character '$'._**<br/>
  **_Tag &lt;permission&gt; attribute name has invalid character '$'._**<br/>
  **_Tag &lt;uses-permission&gt; attribute name has invalid character '$'._**<br/>
compiler errors require you to change `${applicationId}` with your Java app package in `AndroidManifest.xml`.<br/>
See [GCM Play Services](https://developers.google.com/cloud-messaging/android/client#manifest) documentation for more details.

**Requires:**
- `Android 2.3.1 (API 9) SDK Platform`
- [dandar3/android-google-firebase-common](https://github.com/dandar3/android-google-firebase-common)
- [dandar3/android-google-play-services-basement](https://github.com/dandar3/android-google-play-services-basement)

**References:**
- https://developers.google.com/android/guides/releases#june_2016_-_v92

**SVN checkout:**
- https://github.com/dandar3/android-google-firebase-iid/tags/9.2.1
