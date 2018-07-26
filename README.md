# Smart-Baby-Diaper

### INTRODUCTION AND OVERVIEW
Used Octabrix Dev kit for Smart baby diaper. 
Diaper detects the moisture of the diaper and at appropriate levels
of moisture sends notification to Blynk app as well as 
sends an email as well as plots a real time graph for the moisture level in the app

### COMPONENTS
#### Hardware :
- Octabrix
- FC-28 humidity sensor
- Jumper Wires
- Paper cups(for making temporary case)
- 9v DC power supply
- Android phone with Blynk App
- Baby Diaper
#### Software :
- Arduino IDE
#### Cloud platforms :
- Blynk
- IFTTT

### WORKING 
As soon as the moisture level starts increasing in the diaper
the humidity sensor FC-28 starts sending data to octabrix ,now octabrix 
these reading to blynk cloud and also plots the real time graph of the 
recieved data. At different level of moisture a notification is recieved 
in the app and well as an email notification is recieved.

### FUTURE MODIFICATIONS
1. ##### Sound Detection
  we can install sound sensors so that when baby cries it will notify the parent
  
2. ##### Tracking System
  we can also install GPS Tracking system so that parent can easily track their children when
  lost.

![screenshot_2018-07-13-14-35-56-480_cc blynk](https://user-images.githubusercontent.com/41651033/43277905-1dd2c0f2-9127-11e8-8481-4ac7a4aa7b24.png)
