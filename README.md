<img src="http://www.testingdiaries.com/wp-content/uploads/2014/10/AndroidMonkey.png" alt="Kiwee - Ui" style="width:150px;height:150px;" width="85px" height="100px"></br> FourthMonkey v1.0
===
In software testing, monkey testing is a technique where the user tests the application or system by providing random inputs and checking the behavior, or seeing whether the application or system will crash. Monkey testing is usually implemented as random, automated unit tests.

Shell Script for run monkey command in automated way it will generates all the necessary files such as Bug report, Video recording and screenshots and place them into respective device serial number specific folders.

This script command runs on multiple devices one after the other and it doesn't need any monitoring as well as time saving and easy way to reproduce the crash bugs for perticular app on android devices.

Prerequisite:

   1. "adb" folder path has to be added into your Environment(Linux) variable path      
       
How to Configure: 

   1. Give execute permission to your script<br/>
            ex:  chmod +x /path/to/MonkeyRunner_log_collector_1.0.sh

   2. And to run your script ([app-packagename] is argument for script)<br/>
             ex: sh /path/to/MonkeyRunner_log_collector_1.0.sh [app-packagename]
             
How to execute:  
      sh MonkeyRunner_log_collector_1.0.sh [app-packagename]  
      ex: sh MonkeyRunner_log_collector_1.0.sh com.google.android.apps.maps  
             
             



