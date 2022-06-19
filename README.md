# Appium
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

Appium with Selenium and Android Studio

![APP](https://user-images.githubusercontent.com/33332202/174480713-51108b98-0cce-4e45-81df-a43bfdf29fe3.jpg)

Steps to use Appium from  Mobile Test Validations
==================================================
Welcome to our Appium Tutorial . 
Ths is an tutorial to provide the most comprehensive  on how to download and setup Appium from scratch for both mobile apps and mobile browsers.


1- Tools to do the Downloads -
-Android Studio (v1.4)
-Appium Jar files for Java
-Selenium (v3.14)
-Appium Server (v1.4)
-Install Java (1.8 - JDK8)

Install Android Studio please follow the steps given in the link to install android studio step by step on windows machine click here
After installation of android studio ,open android studio and create a new project - How to create android project?

2. Add the downloaded Appium jars into your project - click on project -> click on app->copy all the jars in lib. 
Select the copied jars except Selenium, Java client and Junit Jar ,then right click on it and click on "Add as Library".

3. Click on build.gradle in app you will see all the libs added like below screenshot add junit:4.12.Sync the project or 
Re-build the project. It should show "Build Successful Message"

Build.gradle code for appium setup


4. Now you are ready to write your first test case - right click on the package and click on "Create Java Class". 
Copy given test case sample.

5. Running the Test case-
Click on build variant, Select Unit Testing, Start  the appium server with Specific port "4323"
click here
Connect device with USB debugging on or start an emulator. 
Right click on the test class and click on "Run"
