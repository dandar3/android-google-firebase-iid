## android-google-firebase-iid

Eclipse library project based on:<br/>
`ANDROID_SDK/extras/google/m2repository/com/google/firebase/firebase-iid/9.6.1/firebase-iid-9.6.1.aar`

**Notes:**
- **_Tag &lt;category&gt; attribute name has invalid character '$'._**<br/>
  **_Tag &lt;permission&gt; attribute name has invalid character '$'._**<br/>
  **_Tag &lt;uses-permission&gt; attribute name has invalid character '$'._**<br/>
compiler errors require you to change `${applicationId}` with your Java app package in `AndroidManifest.xml`.<br/>
See [GCM Play Services](https://developers.google.com/cloud-messaging/android/client#manifest) documentation for more details.

**Requires:**
- `Android 7.0 (API 24) SDK Platform`
- [dandar3/android-google-firebase-common](https://github.com/dandar3/android-google-firebase-common/tree/9.6.1)
- [dandar3/android-google-play-services-basement](https://github.com/dandar3/android-google-play-services-basement/tree/9.6.1)

**References:**
- https://developers.google.com/android/guides/releases#september_2016_-_v96
- https://firebase.google.com/support/release-notes/android#9.6

**SVN checkout:**
- _File > Import... > Team > Team Project Set > URL:_<br/>
  https://raw.githubusercontent.com/dandar3/android-google-firebase-iid/9.6.1/.projectset
- _File > Import... > SVN > Project from SVN > Create a new repository location > URL:_<br/> 
  https://github.com/dandar3/android-google-firebase-iid/tags/9.6.1