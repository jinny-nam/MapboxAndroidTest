# MapboxAndroidTest
Mapbox home assignment for technical support engineer


## Screenshot of MapboxTest Android App
![Screenshot_mapboxtest](https://user-images.githubusercontent.com/17017042/125205215-77976080-e281-11eb-9269-f15e016fae9b.png)

## Test environment
  * Android Studio Emulator with API24(Nougat), Pixel2(5.0 1080x1920) - worked succesfully!
 
## Comments
* Location of the file I mainly worked on: 
  * [MainActivity.java](https://github.com/jin0639/MapboxAndroidTest/tree/master/app/src/main/java/com/jinny/mapboxtest)
  
* Error with an API30 Emulator
  * Running on Android Studio Emulator with API30 was not working, facing "terminating with uncaught exception of type jni::PendingJavaException" issue.
  * I suspected that it's releated to lack of location permissions so I tried to add PermissionsManager (due to the logcat message 'Location permissions are not granted'). But I could not resolve the issue.
  * The source code with PermissionsManager can be found [here](https://github.com/jin0639/MapboxAndroidTest-with-PermissionsManager).


## References
  * [First steps with the Mapbox Maps SDK for Android](https://docs.mapbox.com/help/tutorials/first-steps-android-sdk)
  * [Android SDK installation](https://docs.mapbox.com/android/maps/guides/install/)
  * [Android Places Plugin](https://docs.mapbox.com/android/plugins/guides/places/)
  * [Android Plugins Example - Global location search](https://docs.mapbox.com/android/plugins/examples/global-location-search/)
