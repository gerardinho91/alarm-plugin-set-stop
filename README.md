alarm-plugin-set-stop
===========
alarm-plugin-set-stop for Cordova/PhoneGap.

To install the plugin:

    cordova plugins add https://github.com/gerardinho91/alarm-plugin-set-stop.git

To invoke the plugin: 

var newDate = new Date();
newDate.setSeconds(newDate.getSeconds() + 60);
 
				  
	//start
     navigator.plugins.alarm.set(newDate,  
      function(){
        // SUCCESS
      }, 
      function(){
        // ERROR
      })
 
 
 //stop
  navigator.plugins.alarm.stop( 
      function(){
        // SUCCESS
      }, 
      function(){
        // ERROR
      })
	

```newDate``` is the date that the application will wake up. This will happen even if the device has been rebooted.
 
