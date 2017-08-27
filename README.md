# sample-android-fingerprint

Steps to use fingerprint api to implement fingerprint authentication in android application.

Android 6.0 (M) release of new APIs, authenticating users with help of fingerprint sensors on various devices is possible. To authenticate users using the fingerprint sensor, you need to get an instance of the newly implemented FingerprintManager class and call the authenticate() method. However your app must be running on a compatible device which includes a fingerprint sensor. Moreover you must implement the user interface for the fingerprint authentication flow on your app, and use the standard Android fingerprint icon in your UI.

generateKey() function which generates an encryption key which is then stored securely on the device.

cipherInit() function that initializes the cipher that will be used to create the encrypted FingerprintManager.

CryptoObject instance and various other checks before initiating the authentication process which is implemented inside onCreate() method.
