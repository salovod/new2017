* TestNG
* Selenide
* ??Selenium Grid
* Appium
* Gradle
* Allure


----------------------


POP => 
a) PageRules  => (extends) any class with locators action
b)  DriverInitialize =>BeforeClass  => (extends) TestClass








API => ENV interface => 


Required:
# APPIUM:
https://github.com/appium/appium-desktop/releases/tag/v1.2.0-beta.1

# Android SDK
http://www.softportal.com/get-9680-android-sdk.html
And update required from SDK Manager + install HAXM in Extras folder.

For Intel: 
https://software.intel.com/en-us/android/articles/intel-hardware-accelerated-execution-manager


Add system variables:
ANDROID_HOME  => e.g. G:\Android
Add to PATH:
* %ANDROID_HOME%\tools
* %ANDROID_HOME%\platform-tools
#Install NodeJS
https://nodejs.org/uk/download/


# Run next:
npm install -g appium
npm install appium-doctor -g
appium


# Run SDK Manager and Configure:
- Create new Device.

# Download Chrome.apk
https://www.apkmirror.com/apk/google-inc/chrome/chrome-58-0-3029-83-release/chrome-browser-58-0-3029-83-6-android-apk-download/

move to C:/Users/%USER%

then:
adb install %FILE_NAME%
