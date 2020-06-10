# Cucumber and Appium Example
This project demonstrates usage of Cucumber and Appium for Mobile Automation using JavaScript as Programming language.
Project is associated with the Blog  # Cucumber and Appium Example - <>

This example will cover:

Basic Test for Mobile Automation using Cucumber and Appium with JavaScript as programming language and Visual Studio Code as IDE

### Steps to run demo test

1. Clone this git repository

	```
	git clone
	```

2. Start Appium Server using Appium Desktop installed in your PC.
   The project expects the Appium Server to run on localhost:4723. If you run the server to different host and port. Please change the code.

3. Download the Eribank application using URL : https://experitest.s3.amazonaws.com/eribank.apk to c:\\  (The code uses the Application from c:\\ (in windows). Please change the code in case you   change the download location)

. Modify following variables in the code if necessary
   Open EribankLogin.js and modify the code if necessary,

      Appium Server listening host and port.

      ```
       driver = await new wd.Builder().usingServer("http://localhost:4723/wd/hub").withCapabilities(desiredCaps).build();
      ```

      Device name (After executing adb devices. See "Initializing the driver" in the blog)

      ```
      deviceName: "a3ae1c63"
      ```


5. To know how to use and execute the test,
      * Open the cloned project in Visual Studio Code
      * Please follow the section "Getting Started with Cucumber and Appium Example" in the blog.

