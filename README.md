
# Android-Fingerprint-Authentication
Android Fingerprint APIs are bringing user authentication to a whole new level, making it fast and secure. Unlocking a phone with a single touch is one of my favorite features in Marshmallow and I really wish there were more apps out there using touch identification. Fingerprint recognition itself is not new, but the OS-level support for it in Android has been much anticipated. In the near future, it’s going to eliminate the need to integrate specific fingerprint SDKs from device manufacturers like Samsung, which, without a doubt, would be a great relief for app developers.
                               
                               Advantages of Using Fingerprint Authentication

1. Doesn’t matter how sick you are or unable to recollect things, your fingerprint still stays faultless as your identity and can never be misplaced.
2. Fast , Convenient and Reliable to use.
3. Unique fingerprints assure that it’s unlocked just by you.
4. With the help of Fingerprint authentication, online transactions become more convenient, hence your just a tap away from getting verified.

1. Create a new project in Android Studio from File ⇒ New Project and set the minimum SDK version to Android 6.0 (API 23).
2. Since we are going to work with Fingerprint authentication, we need to add USE_FINGERPRINT permission to AndroidManifest.xml file
3. Create an Android Activity class and name it FingeprintActivity.java. The following class includes various methods and functions like, onCreate() method that inflates activity_fingerprint.xml.

> generateKey() function which generates an encryption key which is then stored securely on the device.

> cipherInit() function that initializes the cipher that will be used to create the encrypted FingerprintManager.

> CryptoObject instance and various other checks before initiating the authentication process which is implemented inside onCreate() method.
45. Testing the Project

Testing on a Physical Device
