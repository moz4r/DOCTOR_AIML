# InMooV - Service launcher v 0.9.9   

This is the full configurable launcher script for Inmoov service

## Getting Started
MORE informations here : http://myrobotlab.org/service/InMoov  
  
At this time configurable things are inside the config folder.  
By default virtual environment is started, so you can test things with no risk !  
  
To start using the Finger Starter with real hardware, set :  
 ( The Finger Starter is considered here to be right index, so make sure your servo is connected to pin3 of you Arduino )  

```
ScriptType=RightSide | inside config/_InMoov.config  
MyRightPort=COMx | inside config/_service_6_Arduino.config  
isRightHandActivated=True | inside config/skeleton_rightHand.config  
voice command sample : OPEN HAND  
```

Check your configuration inside Inmoov.config ( exemple to change english to french )  
If you setup 2 arduino + configs in skeleton folder, it can run full Inmoov or separated parts ( right hand / head ... )  
   
  
### DOCUMENTATION & HELP  
http://myrobotlab.org/service/InMoov  
  
bugs report : https://github.com/MyRobotLab/inmoov/issues  
  
### CHANGELOG  
   
0.9.9  
/ Testing...  
0.7.0  
/ Chatbots enhancements & fixes...  
0.6.1  
/ add AndroidSpeechRecognizer   
