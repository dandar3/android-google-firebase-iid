## android-google-firebase-iid

Eclipse library project based on:<br/>
`ANDROID_SDK/extras/google/m2repository/com/google/firebase/firebase-iid/10.2.4/firebase-iid-10.2.4.aar`

**Notes:**
- **_Tag &lt;category&gt; attribute name has invalid character '$'._**<br/>
  **_Tag &lt;permission&gt; attribute name has invalid character '$'._**<br/>
  **_Tag &lt;uses-permission&gt; attribute name has invalid character '$'._**<br/>
compiler errors require you to change `${applicationId}` with your Java app package in `AndroidManifest.xml`.<br/>
See [GCM Play Services](https://developers.google.com/cloud-messaging/android/client#manifest) documentation for more details.

**Requires:**
- `Android 7.1 (API 25) SDK Platform`
- [dandar3/android-google-firebase-common](https://github.com/dandar3/android-google-firebase-common/tree/10.2.4)
- [dandar3/android-google-play-services-basement](https://github.com/dandar3/android-google-play-services-basement/tree/10.2.4)

**References:**
- https://firebase.google.com/support/release-notes/android#20170428
- https://developers.google.com/android/guides/releases#april_2017_-_version_1024

**SVN checkout:**
- _File > Import... > Team > Team Project Set > URL:_<br/>
  https://raw.githubusercontent.com/dandar3/android-google-firebase-iid/10.2.4/.projectset
- _File > Import... > SVN > Project from SVN > Create a new repository location > URL:_<br/> 
  https://github.com/dandar3/android-google-firebase-iid/tags/10.2.4