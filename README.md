# kotlin-native-example 

Usage kotlin multiplatform feature to create an Android and iOS app in which whole business logic is wirtten in Kotlin language

View layer is written in platform specific languages

Presenter and Model layer is written in Kotlin language



<img src="https://raw.githubusercontent.com/sangeetsuresh/sangeet.github.io/master/kotlinnative.png">

* app module is for android app code
* common module is for common code which is shared between Android and iOS

   * common module consist of 
        + commonMain  - kotlin code 
        + iOSMain - kotlin plaform specific code for iOS
        + androidMain - kotlin platform specific code for Android
        
* iOSApp is for iOS app code

If you getting sdk.dir not found error during building, create `local.properties` in root project folder and add `sdk.dir=<android sdk path>` into that file. This is because it need android sdk to build this project
