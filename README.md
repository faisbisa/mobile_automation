# mobile_automation
Mobile Automation Diet Meal in Sanbercode 

How to Start

Install

Node JS
Java SDK & JAVA_HOME
Android Studio & ANDROID_HOME
Appium Desktop
Install package.json with command
  npm install
How to run

Connect to your device android or IOS
Setup desired capabilities in file wdio.conf.js
Run test
  npm run wdio
  
  nb from Dani_A sanber :
  mungkin yg lain bisa coba.
1. Aku coba download dan coba setup mobil automation mas alvin
https://github.com/alvintrianto/sanber-mobileAutomation
2. Bikin Folder di desktop: Desktop\Workdocs\TOOL QA\Abbtools\android-sdk-windows
3. Copas isian android sdk dari android studio dan java JRE ke folder android-sdk-windows diatas:
C:\Users\Username\AppData\Local\Android\Sdk > android
C:\Program Files\Java\jre1.8.0_231
4. Install <npm install appium> via VSCode
5. Jangan run appium dan appium inspector, karena appium jalan sendiri dari command npm run wdio
6. Udah jalankan npm run wdio

  Set capabilities :
  capabilities: [{
        platformName                : "Android",
        "appium:automationName"     : 'UiAutomator2',
        "appium:deviceName"         : 'emulator-5554',
        "appium:platformVersion"    : '11.0',
        "appium:app"                : path.join(process.cwd(),'./test/apk/Diet_meal.apk'),
        "appium:appPackage"         : "io.appium.android.apis",
        "appium:appActivity"        : ".ApiDemos",
        "appium:noReset"            : true,
        "appium:forceAppLaunch"     : true,
