### Sign the APK
keytool -genkey -v -keystore my-release-key.keystore -alias myAlias -keyalg RSA -keysize 2048 -validity 10000

### Keystore to sign
jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore my-release-key.keystore newReverseMev1.apk myAlias
