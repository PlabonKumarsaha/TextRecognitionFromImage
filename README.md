# TextRecognitionFromImage
Firebase ML kit was used to develop this project ..The documentation link is given 
https://firebase.google.com/docs/ml-kit/android/recognize-text


These dependencies must be added in gradle:module
// https://firebase.google.com/support/release-notes/android
    //the below two are not free to use..you need google cloud subscription for this!this two are the latest versions..you can find them in
    //the link above
    implementation 'com.google.firebase:firebase-analytics:17.2.0'
    implementation 'com.google.firebase:firebase-ml-vision:23.0.0'

    //so insted we can use free versions like :

    implementation 'com.google.firebase:firebase-core:15.0.2'
    implementation 'com.google.firebase:firebase-ml-vision:15.0.0'
