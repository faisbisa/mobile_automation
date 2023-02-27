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

SETUP :
1. Open Android Studio select file -> profile or debug apk 
2. Open vysor in hp then setting developer option
3. Open vysor in laptop
4. Open apk info, search apk want to test "diet meal"
5. this is for input app package (in title) and appActivity->app detail->app activity->select to up

START to BULID SCRIPT :
1. Build Scenario + element locator
- Click & Assert data
- Input Text in Mobile
2. Install WDIO "npm init then npm init wdio . next yes, select on my local machine, select mocha, bable, , select spect, select wait for, select appium"
3. Install Appium Configuration
4. to see error = adb uninstall io.appium.uiautomator2.server
