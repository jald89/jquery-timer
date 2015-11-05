# Update: February 16, 2013 #

**This project is now on Github:** https://github.com/jchavannes/jquery-timer


---


# jQuery Timer #

jQuery Timer adds the class $.timer().


---


## $.timer() ##

**$.timer( `[` _action_ `]` , `[` _time_ `]`, `[` _autostart_ `]` )**

**action** A Function to be called by the timer.

**time** A Number determining how long between actions in milliseconds.

**autostart** A Boolean indicating whether to start the timer. Defaults to false.

### Usage ###
```
	var timer = $.timer(function() {
		alert('This message was sent by a timer.');
	});

	timer.set({ time : 5000, autostart : true });
```
```
	timer.set(options);
	timer.play(reset);  // Boolean. Defaults to false.
	timer.pause();
	timer.stop();  // Pause and resets
	timer.toggle(reset);  // Boolean. Defaults to false.
	timer.once(time);  // Number. Defaults to 0.
	timer.isActive  // Returns true if timer is running
	timer.remaining // Remaining time when paused
```


---


### Demo ###
http://jchavannes.com/jquery-timer/demo

### Download ###
[http://code.google.com/p/jquery-timer/downloads/detail?name=jquery-timer.zip](http://code.google.com/p/jquery-timer/downloads/detail?name=jquery-timer.zip&ref=gcode#home)

### View Source ###
[http://code.google.com/p/jquery-timer/source/browse/](http://code.google.com/p/jquery-timer/source/browse/trunk/jquery.timer.js)