# android_rules
android.rules for Android SDK on linux platform

* place this file in the /etc/udev/rules.d/ folder
* sudo chmod a+r android.rules
* sudo service udev restart
* adb kill-server
* adb start-server
* adb devices 
