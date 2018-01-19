# Voice-Recog
Build Instructions
Introduction: My project is a voice recognition used through Alexa/Amazon echo. Amazon Echo is a brand of smart speakers developed by Amazon.com. The devices connect to the voice-controlled intelligent personal assistant service Alexa, which responds to the name "Alexa". To avoid any law suits, when making this version on the raspberry pi you are not allowed to use the wake word “Alexa” to begin the app. You can only use a button or a click button through a GUI.

Bill/Budget: Essentially for this project Users will need a Speaker, Microphone, Mouse, and Keyboard.

Time Commitment: Once all the parts have been assembled this project can be built in about an hour as long as the instructions are properly followed and all the required parts assembled.

Mechanical Assembly: Connect the USB keyboard to the raspberry pi, Connect the USB mouse to the raspberry pi, Connect the 3.5mm audio jack speaker to the raspberry pi, Connect the USB microphone to the raspberry pi.

PCB/Soldering: Project does not require any Soldering.

Power Up: For the process in powering up this the device I followed the following steps through this link.
https://github.com/alexa/alexa-avs-sample-app/wiki/Raspberry-Pi
Essentially to sum these steps up in as minimal as possible
-Users register for an amazon developer account
-Change the credentials in their automated_install.sh
-After they run the command to install the application onto their raspberry pi
-You will then need two terminals 1 to connect to the server 2nd to start the application.
If users follow the steps from the provided link the app should work perfectly.

Unit Testing 
Testing the application is simple
First click on the Listen button 
Second speak into the microphone by asking Alexa a question.
Third wait for Alexa to respond through the speaker 
 
Production Testing
If any production testing can really be done it will be through setting your microphone and speaker to work properly with your raspberry pi. Click on the Audio icon on the top left of your raspberry pi desktop, set up your microphone so it is on, next set up your speaker so it is a PCB.
Is the project reproducible by following your instructions?
-If users follow the steps from the provided link the app should work perfectly.
