**NOTE:  DenonAVPControl now supports the [Logitech Media Server](http://www.mysqueezebox.com/download)**

This plugin assumes that your Squeezebox player is connected to the AVP/AVR via a digital connection to one of the Denon audio ports and that you have confirmed that audio can be heard from the player through the Denon to your speakers.

This Squeezebox plugin will turn on and off a Denon amplifier/receiver when the Squeezebox is turned on/off or a song is played.  When the user adjusts the volume on the Squeezebox, the amplifier volume is adjusted accordingly.  The plugin will optionally set one of the Quick Select modes, and set the volume of the Squeezebox to match the amplifier volume when the users chooses to use that volume control instead of the Squeezebox.  The user can also set an optional on or off delay timer and set the maximum volume level they wish the amplifier to be set to when controlling the Squeezebox.

The user can select from either the Main or Zone 2, 3 or 4.  The user also has the option of having the plugin set the Squeezebox volume from the Denon at every track change.  This will allow the user to set the volume either by the amplifier or the [Logitech Media Server](http://www.mysqueezebox.com/download).  Using the [iPeng](http://penguinlovesmusic.de/) application for the iTouch devices, DenonAVPControl will allow the user to change audio settings on the AVP/AVR during playback.

The plugin uses the Denon serial protocol over a wireless or wired network and therefore a network connection between the [Squeezebox Server](http://www.logitech.com/en-us/speakers-audio/wireless-music-systems) and the Denon amplifier must be available.

The plugin has only been tested with the Denon AVP-A1HD and the Squeezebox Receiver but it should work with any Denon receiver that supports the serial protocol over a network and the Squeezebox Classic as well.  The plugin has also been tested with the Apple iOS devices using the [iPeng](http://penguinlovesmusic.de/) native application.

**Note**:  This plugin requires at least version 7.0 of [Logitech Media Server](http://www.mysqueezebox.com/download).  It has been tested with Version: 7.7.2.