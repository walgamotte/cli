# set java home
Variable name: JAVA_HOME
Variable value: Paste the folder path (e.g., C:\Program Files\Android\Android Studio\jbr)
or
$env:JAVA_HOME="C:\Program Files\Android\Android Studio\jbr" in terminal 

# compile apk
# Compiles a standard testable Debug APK using the Gradle wrapper
.\gradlew.bat assembleDebug
