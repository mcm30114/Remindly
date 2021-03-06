# Remindly

The quickest way to create a reminder on your iPhone™.  It starts up quickly, allows you to scribble a letter, word, or figure on the screen, enter a time (with convienent shortcuts) and then get on with your day. 

## About:
 * Enter a reminder in just a few seconds
 * Uses the UILocalNotification features found in iOs 4.0, allowing reminders to continue to fire even if Remindly isn't running
 * Can choose between multiple different sounding alarms, including voice.
 * Created by [IoGee](http://iogee.com/remindly)
 * Inspired by Palm application Diddlebug.
 * Available from [App Store](http://itunes.apple.com/us/app/remindly/id411254165?mt=8&uo=4)

## Source code includes:
 * Bezier curves for smoothing lines while drawing.  Many drawing apps don't seem to do this, they really should.
 * Background locaiton updates which fire geographical alarms when leaving or nearing a location
 * Xibless design with application created only in code.
 * Uses in-app purchase, a good reference for a often-confusing subject.  When building for yourself, you probably want to modify method -(BOOL)isAllowedMoreNotes in [NotesManager.m](https://github.com/nathanstitt/Remindly/blob/master/Classes/NotesManager.m) to always return true.

## License
 * Source code is released under the GPL v3.
 * Images, Sounds and other assets are licensed under the Creative Commons Attribution-NonCommercial license.
 
