## android-google-firebase-iid

Eclipse library project based on:<br/>
https://maven.google.com/com/google/firebase/firebase-iid/12.0.1/firebase-iid-12.0.1.aar

**Notes:**
- **_Tag &lt;category&gt; attribute name has invalid character '$'._**<br/>
  **_Tag &lt;permission&gt; attribute name has invalid character '$'._**<br/>
  **_Tag &lt;uses-permission&gt; attribute name has invalid character '$'._**<br/>
compiler errors require you to change `${applicationId}` with your Java app package in `AndroidManifest.xml`.<br/>
See [GCM Play Services](https://developers.google.com/cloud-messaging/android/client#manifest) documentation for more details.

**Requires:**
- `Android 8.1 (API 27) SDK Platform`
- [dandar3/android-google-firebase-common](https://github.com/dandar3/android-google-firebase-common/tree/12.0.1)
- [dandar3/android-google-play-services-basement](https://github.com/dandar3/android-google-play-services-basement/tree/12.0.1)
- [dandar3/android-google-play-services-tasks](https://github.com/dandar3/android-google-play-services-tasks/tree/12.0.1)

**References:**
- https://firebase.google.com/support/release-notes/android#sdk_version_1201_march_28_2018
- https://developers.google.com/android/guides/releases#march_28_2018_-_version_1201

**SVN checkout:**
- _File > Import... > Team > Team Project Set > URL:_<br/>
  https://raw.githubusercontent.com/dandar3/android-google-firebase-iid/12.0.1/.projectset
- _File > Import... > SVN > Project from SVN > Create a new repository location > URL:_<br/> 
  https://github.com/dandar3/android-google-firebase-iid/tags/12.0.1