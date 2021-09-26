# ospos-android
This is an Android web view app to view specifically Open Source Point Of Sale program (https://github.com/opensourcepos/opensourcepos) directly from your smart devices in a user friendly interface.
To use this app you should have a working OSPOS installation and access to the program. 

Codes for this application was gathered from "Naatlyrics" https://naatlyrics.net/how-to-convert-any-website-into-an-android-app-free-using-android-studio/

This is a simple android application to view Open Source Point Of Sale program through android devices via web view without using a web browser.
This enables user to access OSPOS program directly from your smart devices without launching a web browser and typing url addresses.
This app loads Open Source Point of Sale in a very compact user friendly interface for hand held devices. You can use the system on the go without any hazzel.

Currently I have not developed a method to change the url address within the app settings. 
First you have to download this project files and open it from Android Studio
You have to edit MainActivity.java and replace following line with your installation url(Ex: localhost/opensourcepos/public).

mywebView.loadUrl("http://192.168.1.10/opensourcepos/public/");

Then compile the project and build an apk file to install on your device. 
Or else you can turn on developer options in your android device and also you have to enable "USB DEBUGGING" option.
Then connect your android device through USB and you can run the app directly from android studio. This will install the app in your device.

I hope to develop an inapp setting to define this URL within the app in the future. Then anyone will be able to install this app directly to their device & use without any of above hazzel.
Without Android studio or without any development skills. 

I invite you to help develop new features like these and improve to make this an user friendly app.

Thank You.
Janith Hemachandra, Sri Lanka.
