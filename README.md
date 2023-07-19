# rn_create_apk

## Generate apk in 3 steps !

### Step 1: Go to the root of the project in the terminal and run the below command:

npx react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res

### Step 2: Go to android directory:

cd android

### Step 3: Now in this android folder, run this command

./gradlew assembleDebug

There! you’ll find the apk file in the following path:
yourProject/android/app/build/outputs/apk/debug/app-debug.apk


#### Small notes for beginers : 
APK files are compiled with Android Studio, which is the official integrated development environment for building Android software. 
Once the software completes development, Android Studio compiles the app and places it in an APK file. 
Android Studio is available on Windows, Mac and Linux.
